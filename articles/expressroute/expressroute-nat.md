<properties
   pageTitle="ExpressRoute 线路的 NAT 要求 | Microsoft Azure"
   description="本页提供有关为 ExpressRoute 线路配置和管理 NAT 的详细要求。"
   documentationCenter="na"
   services="expressroute"
   authors="cherylmc"
   manager="carolz"
   editor=""/>
<tags
   ms.service="expressroute"
   ms.date="10/06/2015"
   wacn.date=""/>

# ExpressRoute NAT 要求

若要使用 ExpressRoute 连接到 Microsoft 云服务，你需要设置并管理 NAT。某些连接服务提供商以托管服务形式提供 NAT 的设置和管理。请咨询连接服务提供商，以确定他们是否提供此类服务。如果不提供，则你必须遵守以下所述的要求。

有关不同路由域的概述，请查看 [ExpressRoute 线路和路由域](/documentation/articles/expressroute-circuit-peerings)页。为了符合 Azure 公共和 Microsoft 对等互连的公共 IP 地址要求，建议在网络与 Microsoft 之间设置 NAT。本部分提供需要设置的 NAT 基础结构的详细描述。

## Azure 公共对等互连的 NAT 要求

Azure 公共对等互连路径可让你连接到托管于 Azure 中的所有服务的公共 IP 地址。其中包括 [ExpessRoute 常见问题](/documentation/articles/expressroute-faqs)中所列的所有服务，以及由 ISV 托管在 Microsoft Azure 上的任何服务。始终从你的网络向 Microsoft 网络发起与公共对等互连中 Microsoft Azure 服务的连接。定向到公共对等互连中 Microsoft Azure 的流量必须由 SNAT 转换成有效的公共 IPv4 地址才能进入 Microsoft 网络。下图提供了有关如何设置 NAT 以符合上述要求的综合示意图。

![](./media/expressroute-nat/expressroute-nat-azure-public.png)

### NAT IP 池和路由播发

你必须确保流量进入公共 IPv4 地址有效的 Azure 公共对等互连路径。Microsoft 必须能够根据区域路由 Internet 注册表 (RIR) 或 Internet 路由注册表 (IRR) 验证 IPv4 NAT 地址池的所有权。将会根据配对的 AS 编号和用于 NAT 的 IP 地址执行检查。有关路由注册表的详细信息，请参阅 [ExpressRoute 路由要求](/documentation/articles/expressroute-routing)页。
 
通过此对等互连播发的 NAT IP 前缀长度没有限制。你必须监视 NAT 池，并确保未耗尽 NAT 会话。

>[AZURE.IMPORTANT]向 Microsoft 播发的 NAT IP 池不得向 Internet 播发。这会中断其他 Microsoft 服务的连接。

## Microsoft 对等互连的 NAT 要求

Microsoft 对等互连路径可让你连接到不支持通过 Azure 公共对等互连路径访问的 Microsoft 云服务。服务列表包括 Office 365 服务，例如 Exchange Online、SharePoint Online、Skype for Business 和 CRM Online。Microsoft 有望在 Microsoft 对等互连上支持双向连接。定向到 Microsoft 云服务的流量必须由 SNAT 转换成有效的公共 IPv4 地址才能进入 Microsoft 网络。从 Microsoft 云服务到网络的流量必须经过 SNAT 转换才进入网络。下图提供了有关如何为 Microsoft 对等互连设置 NAT 的综合示意图。
 
![](./media/expressroute-nat/expressroute-nat-microsoft.png)


#### 从你的网络发起的，目标为 Microsoft 的流量

- 你必须确保流量进入公共 IPv4 地址有效的 Microsoft 对等互连路径。Microsoft 必须能够根据区域路由 Internet 注册表 (RIR) 或 Internet 路由注册表 (IRR) 验证 IPv4 NAT 地址池的所有权。将会根据配对的 AS 编号和用于 NAT 的 IP 地址执行检查。有关路由注册表的详细信息，请参阅 [ExpressRoute 路由要求](/documentation/articles/expressroute-routing)页。

- 用于 Azure 公共对等互连设置和其他 ExpressRoute 线路的 IP 地址不得通过 BGP 会话向 Microsoft 播发。通过此对等互连播发的 NAT IP 前缀长度没有限制。

	>[AZURE.IMPORTANT]向 Microsoft 播发的 NAT IP 池不得向 Internet 播发。这会中断其他 Microsoft 服务的连接。

#### 从 Microsoft 发起的，目标为你的网络的流量

- 在某些情况下，需要由 Microsoft 对你网络中托管的服务终结点发起连接。一个典型的示例就是从 Office 365 连接到你网络中托管的 ADFS 服务器。在这种情况下，你必须将网络中相应的前缀透露给 Microsoft 对等互连。 

- 你必须使用 SNAT 转换从 Microsoft 定向到你网络中 IP 地址的流量。

## 后续步骤

- 请参阅[路由](/documentation/articles/expressroute-routing)和 [QoS](/documentation/articles/expressroute-qos) 的要求。
- 有关工作流信息，请参阅 [ExpressRoute 线路预配工作流和线路状态](/documentation/articles/expressroute-workflows)。
- 配置 ExpressRoute 连接。

	- [创建 ExpressRoute 线路](/documentation/articles/expressroute-howto-circuit-classic)
	- [配置路由](/documentation/articles/expressroute-howto-routing-classic)
	- [将 VNet 链接到 ExpressRoute 线路](/documentation/articles/expressroute-howto-linkvnet-classic)

<!---HONumber=82-->