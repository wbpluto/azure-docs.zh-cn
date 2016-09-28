<properties
	pageTitle="Azure 计费和订阅常见问题 | Microsoft Azure"
	description="提供常见 Azure 计费和订阅问题的答案"
	services=""
	documentationCenter=""
	authors="genlin"
	manager="msmbaldwin"
	editor=""
	tags="billing"/>

<tags
	ms.service="billing"
	ms.date="07/27/2016"
	wacn.date=""/>

#  Azure 计费和订阅常见问题

本文将回答一些关于 Azure 计费和订阅的最常见问题。

## 帐户管理

- [如何管理新的 Azure 门户中的管理员帐户？](#how-do-i-manage-administrator-accounts-in-the-new-azure-portal)
- [通知能否发送到与我的帐户关联的帐户所有者电子邮件地址之外的电子邮件地址？](#can-notifications-be-sent-to-a-different-email-address-other-than-the-account-owner-email-address-associated-with-my-account)
- [为什么不能编辑或添加订阅详细信息？](#why-cant-i-edit-or-add-details-to-my-subscription)
- [我无法登录 Azure 门户](#i-am-unable-to-log-in-to-the-azure-portal)

## 计费

- [如何获取我的发票副本？](#how-do-i-get-a-copy-of-my-invoice)
- [我看不到最后一个计费周期的发票。为什么？](#i-do-not-see-an-invoice-for-the-last-billing-period-why)

## 免费试用版

- [能否免费试用 Azure，而不用担心被收费？](#can-i-try-azure-for-free-without-any-risk-of-being-charged)
- [什么是免费试用订阅，它能够持续多长时间？](#what-is-a-free-trial-subscription-and-how-long-does-it-last)
- [免费试用时可访问哪些资源？](#what-resources-are-available-when-using-a-free-trial)
- [移除免费试用版的支出限制会发生什么情况？](#what-happens-if-i-remove-the-spending-limit-on-my-free-trial)
- [能否在免费试用订阅期间增加配额？](#can-i-get-a-quota-increase-on-a-free-trial-subscription)
- [可从何处获取免费试用版的详细信息？](#where-can-i-get-more-details-on-free-trial)

## 如何购买 Azure

- [Microsoft Azure 在哪些国家和地区销售？哪些货币可以用来购买 Azure？](#in-which-countries-and-regions-is-microsoft-azure-commercially-available-and-what-currencies-can-be-used-to-purchase-azure)
- [我们是否限制向禁售基于 Azure 的服务的国家/地区转售该服务？](#do-we-restrict-resale-of-azure-based-service-into-countries-under-embargo)
- [是否可以通过 Microsoft 服务提供商许可协议获取 Azure 和 SQL 数据库？](#are-azure-and-sql-database-available-through-microsoft-services-provider-license-agreement)
- [可以使用在 Azure 外部购买的现有 Windows 许可证吗？](#can-i-use-my-existing-windows-licenses-that-i-bought-outside-of-azure)
- [谁可以购买 Azure 服务？](#who-can-purchase-azure-services)

## 付款

- [我在购买 Azure 时可选择哪些付款选项？](#what-payment-options-do-i-have-in-purchasing-azure)
- [如何请求发票付款方式？](#how-can-i-request-the-invoice-method-of-payment)
- [如何查看通过信用卡付款时的付款状态？](#how-do-i-check-the-status-of-a-payment-made-by-credit-card)
- [如何删除不再用作 Azure 付款方式的信用卡？](#how-do-i-remove-a-credit-card-that-i-no-longer-use-as-an-azure-payment-method)
- [如何更新或更改信用卡信息？](#how-can-i-update-or-change-my-credit-card-information)
- [如何编辑 Azure 订阅的支付信息？](#how-can-i-edit-my-payment-information-for-my-azure-subscriptions)

## Azure 定价

- [在哪里可以找到 Azure 服务的权益和定价信息？](#where-can-i-find-the-benefits-and-pricing-information-for-azure-services)
- [如何更改我的定价计划？](#how-do-i-change-my-pricing-plan)

## 服务级别协议 (SLA)

- [我们如何提前知道计划内维护导致的服务停机？](#how-do-we-know-in-advance-about-service-downtime-for-planned-maintenance)
- [针对运行时间和连接而签署的 Azure SLA 协议是什么？](#what-is-the-azure-sla-agreement-for-uptime-and-connectivity)
- [什么是 Azure SLA 信用？](#what-are-the-azure-sla-credits)
- [Azure 服务级别协议如何与当前的本地 Microsoft 许可协议一起使用？](#how-will-azure-service-level-agreements-work-with-current-on-premises-microsoft-licensing-agreements)

## Azure 支出限制

- [如果关闭支出限制，能否将其重新打开？](#can-i-turn-the-spending-limit-back-on-if-i-turn-off-it)
- [能否调整支出限制的金额？](#can-i-adjust-the-amount-of-the-spending-limit)

## 支持计划

- [我如何购买 Azure 支持？](#how-do-i-purchase-azure-support)
- [月费率是涵盖单个 Azure 计划，还是涵盖整个帐户？](#does-the-monthly-rate-cover-a-single-azure-plan-or-the-entire-account)
- [我如何升级到更高级别的 Azure 支持计划？](#how-do-i-upgrade-to-a-higher-tier-azure-support-plan)
- [Azure 支持何时对我收费？](#when-will-i-be-billed-for-azure-support)
- [期限结束后会发生什么情况？](#what-happens-at-the-end-of-the-term)
- [我如何取消 Azure 支持计划？](#how-do-i-cancel-my-azure-support-plan)

## 迁移订阅、服务和数据

- [如何将 Azure 订阅的数据和服务迁移到新的订阅？](#how-do-i-migrate-data-and-services-for-my-azure-subscription-to-a-new-subscription)
- [如何转让我的订阅的所有权？](#how-do-i-transfer-ownership-of-my-subscriptions)

## 订阅服务限制（配额）

- [能否在免费试用订阅期间增加配额？](#can-i-get-a-quota-increase-on-a-free-trial-subscription)

### 我在购买 Azure 时可选择哪些付款选项？

可以使用信用卡或借记卡购买 Azure，也可以选择通过发票进行购买的方式。

> [AZURE.NOTE]

> - 选择发票选项之后，便无法转到信用卡选项。若要注册使用发票，请参阅 [Azure 发票](https://azure.microsoft.com/pricing/invoicing/)。
> - 请注意，我们不接受预付和虚拟信用卡。
> - 所有信用卡利息或可能产生的其他信用卡费用也将完全由你负责。

### 如何请求发票付款方式？

按照 [Azure 发票](https://azure.microsoft.com//pricing/invoicing/)中的步骤提交通过发票付款的请求。请求获批以后，即可得到有关如何针对发票付款方式设置订阅的说明。

### 如何查看通过信用卡付款时的付款状态？

必须提供支持票证才能请求协助。若要创建支持票证来查看通过信用卡进行付款时的付款状态，请参阅[如何创建针对 Azure 计费和订阅问题的支持票证](billing-how-to-create-billing-support-ticket.md)。

### 如何获取我的发票副本？

身为 Azure 帐户管理员，你可以在 Azure 帐户中心查看当前帐单，以及下载过去六个计费周期的对帐单。有关详细信息，请参阅[如何下载 Azure 帐单发票和每日使用数据](billing-download-azure-invoice-daily-usage-date.md)。

### 如何删除不再用作 Azure 付款方式的信用卡？

必须提供支持票证才能请求协助。若要创建支持票证来删除信用卡，请参阅文章：[如何创建针对 Azure 计费和订阅问题的支持票证](billing-how-to-create-billing-support-ticket.md)。

### 如何更新或更改信用卡信息？

如果你更换了信用卡，但号码保持不变，则只需更新现有信用卡的详细信息即可，例如失效日期。如果你的卡号变了，或者你想要使用其他卡，则需添加新卡。可以在下面找到更新或添加信用卡的说明：[如何更改用于支付 Azure 订阅的信用卡](billing-how-to-change-credit-card.md)。

### 我们如何提前知道计划内维护导致的服务停机？

我们的可用性服务级别协议适用于至少使用两个角色实例的客户应用程序。单一实例没有 SLA。如需完整的详细信息，请参阅 [SLA 页](https://azure.microsoft.com/support/legal/sla/)。

#### 计划内维护（经典门户）

不管是单实例配置还是多实例配置，Azure 都会提前发送电子邮件通信，提醒用户即将执行计划内维护（单实例提前 1 周，多实例提前 48 小时）。电子邮件将发送到订阅中提供的帐户管理员、服务管理员和共同管理员的电子邮件帐户。

>[AZURE.NOTE] 如需特定于虚拟机的详细信息，请参阅文章：[Azure 虚拟机的计划内维护](virtual-machines/virtual-machines-linux-planned-maintenance.md)。

#### 计划外维护 

如果 Azure 平台上发生非计划服务中断，则将在[服务仪表板](http://status.azure.com/)上进行状态更新，并且客户也将在 [Azure 经典门户](https://manage.windowsazure.com/)中收到通知。

### 针对运行时间和连接而签署的 Azure SLA 协议是什么？

对于所有公开发布的不在预览版中的服务，Azure 具有单独的 SLA。服务级别协议 (SLA) 描述 Microsoft 关于运行时间和连接性方面的承诺。如需最新详细信息，请参阅 [SLA 页](https://azure.microsoft.com/support/legal/sla/)。

### 什么是 Azure SLA 信用？

Azure SLA 信用将以订阅为基础，按缺少 SLA 的月份中该服务的付费百分比计算。服务信用纳入下个月的帐单中。通常，如果低于第一个阈值（99.95% 或 99.9%，具体取决于服务），我们提供 10% 信用，如果低于下个阈值 (99%)，我们提供 25% 信用。如需完整的详细信息，请参阅 [SLA 页](https://azure.microsoft.com/support/legal/sla/)。

### Azure 服务级别协议如何与当前的本地 Microsoft 许可协议一起使用？

Azure 服务级别协议独立于我们的本地 Microsofte 许可协议。我们的针对 Azure 的 SLA 为你在云中使用的各项服务提供了每月运行时间保证，如果我们未能实现这些保证，将根据我们已向你收取的费用为你提供 SLA 信用。

### 我看不到最后一个计费周期的发票。为什么？

可能的原因包括：

- 从你订阅 Azure 开始算还不到 30 天。

- 订阅类型是“免费试用”或某项成员产品/服务 (MSDN/Open/BizSpark/DreamSpark)，因此没有信用卡或与之关联的其他付款方式。

- 还未到生成发票的日期。

### 我无法登录 Azure 门户

请参阅[无法登录管理 Azure 订阅](billing-cannot-login-subscription.md)。

>[AZURE.NOTE] 请确保以正确的管理员身份登录：帐户管理员只能访问[帐户中心](https://account.windowsazure.com/)，而服务管理员 (SA) 和共同管理员 (CA) 则只能访问 [Azure 门户](https://portal.azure.com/) 或 [Azure 经典门户](https://manage.windowsazure.com/)。

### 我如何购买 Azure 支持？

Azure 支持计划既可在线购买，又可通过企业协议进行购买。开发人员、标准或专业直接支持计划通过 [Azure 支持计划](https://azure.microsoft.com/support/plans/)页面在线提供。必须是 Microsoft Azure 帐户所有者才能购买支持计划。

如果你通过企业协议 (EA) 购买 Microsoft Azure，则可以通过与你的大客户经销商 (LAR) 联系，向你的企业协议添加标准支持计划或专业直接支持计划。开发人员支持不可通过企业协议获取。

### 月费率是涵盖单个 Azure 计划，还是涵盖整个帐户？

Azure 支持的包月费涵盖一个帐户，而不考虑该帐户中的订阅数量或用户数量。

帐户下的所有订阅均共享同一支持计划，并且对此帐户下的任意订阅具有管理员/所有者访问权限的所有用户也有资格使用其访问的特定帐户订阅的支持。

可通过 [Azure 帐户中心](https://account.windowsazure.com/Home/Index)访问 Microsoft Azure 帐户。从这里可以查看属于该帐户且有资格使用支持的订阅的列表。

### 我如何升级到更高级别的 Azure 支持计划？

[提交支持请求](billing-how-to-create-billing-support-ticket.md)并选择“订阅管理”即可升级到更高级别的计划。Microsoft 将取消你原有 Azure 支持计划的剩余付款，并以更高级别对你初始承诺的剩余月份进行收费。

### Azure 支持何时对我收费？

当你在线购买 Azure 支持计划时，我们将立即向你收取第一个月的费用。以后，将在每个后续帐期的第一天向你收取每月费用。购买企业协议 (EA) 时，将按协议计费周期收费。

### 期限结束后会发生什么情况？

在 6 个月的期限结束时，你的计划将使用相同的付款方式，自动续订 6 个月相同的 Azure 支持计划。作为帐户所有者，用户可以选择通过 [Azure 帐户中心](https://account.windowsazure.com/Home/Index)关闭自动续订功能。

如果不希望自动续订，请登录 [Azure 帐户中心](https://account.windowsazure.com/Home/Index)，选择相应的支持计划，单击“更改续订详细信息”，并取消自动续订的默认选项。

### 我如何取消 Azure 支持计划？

帐户所有者可取消 Azure 支持计划，方式是先登录 [Azure帐户中心](https://account.windowsazure.com/Home/Index)，然后选择“订阅”。如果存在订阅，则会显示订阅列表。选择要取消的订阅。然后会显示订阅的详细信息，并在屏幕右侧随附一个选项列表。选择“取消”并继续操作。如果没有订阅，则会显示“没有任何订阅”消息。

>[AZURE.NOTE] Azure 支持计划的期限为 6 个月，且 Microsoft 要求有持续的资金承诺才会延续期限。在期限到期前取消，不会免除剩余的承诺，也不会就任何预支付金额提供退款。
有关详细信息，请参阅[如何取消 Azure 订阅](billing-how-to-cancel-azure-subscription.md)。

### 如何将 Azure 订阅的数据和服务迁移到新的订阅？

有关详细信息，请联系 [Azure 支持](https://azure.microsoft.com/support/options/)。若要创建支持票证以将 Azure 订阅的数据和服务迁移到新的订阅，请参阅文章：[如何创建针对 Azure 计费和订阅问题的支持票证](billing-how-to-create-billing-support-ticket.md)。

### 如何管理新的 Azure 门户中的管理员帐户？

Azure 基于角色的访问控制 (RBAC) 可用于对 Azure 进行细致的访问管理。使用 RBAC，你可以在开发运营团队中对职责进行分配，仅向用户授予执行作业所需的访问权限。有关详细信息，请参阅 [Azure 基于角色的访问控制](.\\active-directory\\Azure Role-Based Access Control.md)。

### 如何转让我的订阅的所有权？

用户现在可以轻松地在 Microsoft Azure 帐户中心对即用即付、MSDN、Action Pack 或 BizSpark 订阅执行此操作。已增加将订阅转给其他用户的功能。换言之，用户现在可以更改所拥有的任何即用即付、MSDN、Action Pack 或 BizSpark 订阅的帐户管理员。请注意，接收方的用户帐户必须是在同一国家/地区，而且用户不能转让与应用商店购买相关联的订阅。
有关详细信息，请参阅文章：[如何转让 Azure 订阅](billing-subscription-transfer.md)。

### 可以使用在 Azure 外部购买的现有 Windows 许可证吗？

可以，如果你具有 SA，则可以通过许可移动性为所有虚拟机支持的服务器产品（Windows Server 除外）“获取自己的许可证”。有关详细信息，请参阅 [Azure 上通过软件保障实现的许可证移动性](https://azure.microsoft.com/pricing/license-mobility/)。

### 在哪里可以找到 Azure 服务的权益和定价信息？

有关 Azure 服务权益的信息，请参阅 [Microsoft Azure 产品/服务详细信息](https://azure.microsoft.com/support/legal/offer-details/)。有关定价信息，请参阅 [Azure 定价页](https://azure.microsoft.com/pricing/)。

### 如何更改我的定价计划？

用户可以将即用即付订阅转成 [12 个月预付款优惠](https://azure.microsoft.com/offers/ms-azr-0026p/)。根据此优惠，预付款购买 12 个月期限的 Azure 服务时，将可享受 5% 的 Azure 服务价格折扣。在 [Azure 帐户中心](https://account.windowsazure.com/Subscriptions)转到订阅，然后单击“改用其他优惠”。这是目前唯一可以通过帐户中心改用的优惠。另外，若要改用其他优惠，也可以联系 [Azure 支持](https://azure.microsoft.com/support/options/)。

### 通知能否发送到与我的帐户关联的帐户所有者电子邮件地址之外的电子邮件地址？

是的。如果你要指定其他电子邮件地址来接收通知，请按以下说明操作：

1.	转到 Azure 帐户门户中的[“配置文件”](https://account.windowsazure.com/Profile)选项卡。
2.	单击“编辑详细信息”，更新接收通知的电子邮件地址。

### 如何编辑 Azure 订阅的支付信息？

若要查看和编辑 Azure 帐户信息，必须以帐户管理员身份登录 Azure 帐户中心。以下是有关管理 Azure 订阅的付款方式的说明。**

1.	转到 [Azure 帐户中心](https://account.windowsazure.com/Subscriptions)。
2.	在“订阅”页上，单击需要更新付款方式的订阅。
3.	在“订阅摘要”页上，单击“更改付款方式”。“更改付款方式”工具将在单独的窗口中显示。

	**注意**：也可从 Microsoft Azure 经典门户访问帐户中心。为此，请单击你的帐户名称，然后单击“查看我的帐单”。
4.	在“选择付款方式”页上，单击下拉列表，选择要更新的付款方式，然后单击“编辑”。
5.	在详细信息页上，确保你选择的信用卡类型和卡号正确无误。
6.	对卡的详细信息进行必要的更改，然后单击“下一步”。

有关详细信息，请参阅文章：[如何更改用于支付 Azure 订阅的信用卡](billing-how-to-change-credit-card.md)。

>[AZURE.NOTE] “更改付款方式”工具当前不允许删除用作付款方式的现有信用卡。有关如何删除信用卡的信息，请参阅本文中的[如何删除不再用作 Azure 付款方式的信用卡？](#how-do-i-remove-a-credit-card-that-i-no-longer-use-as-an-azure-payment-method)。

### 为什么不能编辑或添加订阅详细信息？

若要查看和编辑 Azure 帐户信息，必须以帐户管理员身份登录 Azure 帐户中心。若是 AA 却无法编辑订阅，请提交支持票证以请求协助。若要创建支持票证，请参阅文章：[如何创建针对 Azure 计费和订阅问题的支持票证](billing-how-to-create-billing-support-ticket.md)。

### 谁可以购买 Azure 服务？

Azure 适用于旨在构建云级别应用程序和服务的企业。不过，任何人都可以购买 Azure 服务。

### 能否免费试用 Azure，而不用担心被收费？

是的。利用[支出限制功能](https://azure.microsoft.com/pricing/spending-limits/)，注册免费试用、MSDN、MPN 或 BizSpark 产品/服务的客户可以使用 Azure 而不会被收费，前提是始终启用支出限制功能。所有注册使用这些产品/服务的新客户都会启用支出限制，其金额设置为 0 美元。

有关注册 Azure 的信息，请参阅文章：[如何注册、购买、升级或激活 Azure 订阅](billing-buy-sign-up-azure-subscription.md)。

### 如果关闭支出限制，能否将其重新打开？

对于使用我们的成员优惠产品/服务（例如 MSDN）的客户，你们可在下一个计费周期开始时重新启用支出限制功能。关闭支出限制功能后，即无法在当前计费期间重新启用该功能。
有关详细信息，请参阅[更改 Azure 支出限制](https://msdn.microsoft.com/library/azure/dn465781.aspx)。

### 能否调整支出限制的金额？

对于此功能的初始版本，支出限制设置为“$0”，并且无法调整。这是为了让免费试用、MSDN、MPN 或 BizSpark 产品/服务的客户可在完全确保不被收费的情况下使用 Azure。
有关详细信息，请参阅 [Azure 支出限制](https://azure.microsoft.com/pricing/spending-limits/)。

### Microsoft Azure 在哪些国家和地区销售？哪些货币可以用来购买 Azure？

Azure 可在全球 140 多个国家/地区购买，并且我们支持多种货币的计费。单击[此处](billing-countries-and-currencies.md)查看国家/地区和货币的列表。

### 我们是否限制向禁售基于 Azure 的服务的国家/地区转售该服务？

是的。

### 是否可以通过 Microsoft 服务提供商许可协议获取 Azure 和 SQL 数据库？

当前未计划通过 SPLA 提供 Azure 或 SQL 数据库。

### 什么是免费试用订阅，它能够持续多长时间？

Azure 免费试用订阅为新客户提供一个月的免费试用期，并免费提供 200 美元的 Azure 信用额度。若要查看免费试用信用额度可用于和不可用于的服务，请参阅[免费试用促销活动页面](https://azure.microsoft.com/offers/ms-azr-0044p/)。

可在[此处](http://azure.microsoft.com/pricing/free-trial/)注册试用订阅。请参阅[本指南](billing-buy-sign-up-azure-subscription.md#sign-up-for-an-azure-free-trial-subscription)的分步说明。

### 免费试用时可访问哪些资源？

用户会收到免费试用版提供的 200 美元 Azure 信用额度，在 30 天内使用。现在你可以选择如何使用你的 Azure 信用额度。请参阅[免费试用促销活动页面](https://azure.microsoft.com/offers/ms-azr-0044p/)以了解详细信息。

可在[此处](/pricing/free-trial/)注册试用订阅。

另请参阅[免费试用版常见问题](/pricing/free-trial-faq/)。

### 移除免费试用版的支出限制会发生什么情况？

移除支出限制后，将开始对使用免费试用信用额度之外的资源收费。删除支出限制后，将不能对其进行重置。

### 能否在免费试用订阅期间增加配额？

免费试用订阅没有资格增加配额。如果有免费试用版，可将其升级到[即用即付](https://azure.microsoft.com/offers/ms-azr-0003p/)订阅。有关如何升级的详细信息，请参阅[将 Azure 免费试用升级到即用即付](billing-buy-sign-up-azure-subscription.md#UpgradeFreeToPYG)。

>[AZURE.NOTE] DreamSpark 订阅也没有资格增加配额。

### 可从何处获取免费试用版的详细信息？

请访问[免费试用促销活动页面](/offers/ms-azr-0044p/)并阅读[官方免费试用版常见问题](/pricing/free-trial-faq/)。

<!---HONumber=Mooncake_0919_2016-->