# 如何用 Web 应用防火墙(WAF)提高云安全性？

> 原文：<http://web.archive.org/web/20230307163032/https://www.netguru.com/blog/cloud-security-waf>

 一个[云 web 应用](/web/20221206202503/https://www.netguru.com/services/cloud-application-development)防火墙(WAF)是一个保护 web 应用免受攻击的安全解决方案。

它位于互联网和 web 应用程序之间，拦截进出应用程序的流量。与内部解决方案相比，基于云的 WAF 提供了更高的安全性、更好的性能、更简单的管理和更低的成本。

如果您正在寻找云 WAF 解决方案，有几件事需要考虑:

*   首先，您想要保护什么类型的流量？呼入还是呼出？
*   第二，你需要什么级别的保护？基础、中级还是高级？
*   第三，什么功能对你很重要？

一些解决方案不仅仅提供 WAF 保护，例如 [DDoS 保护](http://web.archive.org/web/20221206202503/https://www.netguru.com/blog/infrastructure-ddos-protection)和自定义安全规则。其他功能包括速率限制和 bot 管理。额外付费，你可以购买一个托管解决方案，让[指定的安全顾问](/web/20221206202503/https://www.netguru.com/services/cybersecurity)监控你的服务。

最后，你的预算是多少？云 WAF 产品从免费到每月几千美元不等。货比三家，比较各种功能，找到最适合您需求的产品。

## 使用云 WAF 有什么好处？

使用基于云的 WAF 有几个好处:

1.  **增强的应用安全性:**WAF 位于互联网和网络应用之间，可以抵御各种攻击。
2.  **提高性能:**WAF 从 web 应用服务器上卸载安全处理，释放资源并提高性能。
3.  **简化管理:**基于云的 WAF 负责所有复杂的安全处理，使其易于管理，即使对于非技术用户也是如此。
4.  **降低成本:**基于云的 WAF 比内部解决方案更实惠，因为您不需要购买和维护硬件和软件。

## 晶片保护什么？

WAF 可以抵御各种攻击，包括:

*   **SQL 注入:**恶意代码被注入 SQL 数据库，以提取数据或破坏数据库。
*   **跨站脚本(XSS):** 恶意代码被注入网页，劫持用户会话或窃取信息。
*   **应用程序拒绝服务(DoS):**DoS 攻击通过向 web 应用程序发送大量请求来阻止合法用户访问 web 应用程序。
*   **分布式拒绝服务(DDoS):**DDoS 攻击类似于 DoS 攻击，但来自多台计算机，更难拦截。
*   **恶意软件:**恶意软件，如病毒和蠕虫，可以感染 web 应用程序，破坏它或窃取敏感数据。

WAF 还可以抵御更复杂的攻击，例如多态攻击和零日攻击。

## 云晶片是如何工作？

基于云的 WAF 的工作原理是保护 web 应用程序免受利用应用层漏洞的攻击。WAF 位于互联网和 web 应用程序之间，拦截进出应用程序的所有流量。

当用户试图访问受保护的 web 应用程序时，WAF 将首先检查用户是否被允许访问该站点。如果用户不在白名单上，请求将被阻止。如果用户在白名单上，WAF 将检查请求中是否有恶意负载。如果发现任何错误，请求将被阻止。否则，他们将被允许访问 web 应用程序。

WAF 还将监控任何可疑或恶意的活动，并阻止符合特定标准的请求。例如，如果晶片在短时间内检测到来自特定 IP 地址大量请求，它可以阻止来自该地址的所有请求。

## 云晶圆控制和功能

云 WAF 提供类似于本地 WAF 的安全控制和功能。其中包括:

1.  **流量过滤:**WAF 可以根据源 IP 地址、URL 和 HTTP 头等参数过滤流量。
2.  **安全规则:**安全规则定义应该允许或阻止哪些流量。规则可以手动创建，也可以根据 WAF 检测到的恶意活动自动生成。
3.  **速率限制:**速率限制可以通过限制用户在给定时间段内可以发出的请求数量来防止 DoS 和 DDoS 攻击。
4.  **Bot 管理:** Bot 管理功能可以阻止自动流量(如 Bot 和网络爬虫)访问 web 应用程序。
5.  **Web 应用防火墙(WAF):**WAF 引擎可以防御利用 Web 应用中漏洞的攻击，例如 SQL 注入和跨站脚本(XSS)。最流行的 WAF 规则集基于 OWASP 核心规则集(CRS)和 ModSecurity 规则。
6.  **DDoS 防护:** DDoS 防护通过在恶意流量到达 web 应用服务器之前识别并阻止恶意流量，来防御分布式拒绝服务(DDoS)攻击。
7.  **SSL/TLS 加密:** SSL/TLS 加密可用于加密进出 web 应用程序的流量。这可以保护传输中的数据不被攻击者截获和读取。

## 如何实现云 WAF？

与建立内部解决方案相比，实施基于云的 WAF 通常是一个更简单、更实惠的过程。首先，您需要注册一个 WAF 服务，并将其配置为与您的 web 应用程序一起工作。

具体细节将根据您使用的 WAF 服务而有所不同，但一般步骤如下:

1.  选择 WAF 服务:有许多不同的 WAF 服务可供选择，所以在选择之前花些时间比较一下功能和价格。
2.  **设置 WAF:** 这通常包括创建一个帐户和添加您的 web 应用程序。
3.  **配置 WAF:** 一旦 WAF 设置好了，您就需要配置它来与您的 web 应用程序一起工作。这包括指定允许或阻止哪些流量，以及设置安全规则。
4.  测试 WAF: 在使用 WAF 之前，测试它以确保它按预期工作是很重要的。向 WAF 发送一些测试流量，并检查它是否被正确处理。

## 哪款云 WAF 最适合你？

最适合您的云 WAF 将取决于您的具体需求和要求。如果您需要基本级别的保护，像 Cloudflare 这样的免费解决方案可能就足够了。如果需要高级防护，像 Imperva Incapsula 或者 Akamai Kona Site Defender 这样的一体化解决方案可能是更好的选择。最终，比较功能和价格以找到最适合您的组织是很重要的。

既然您已经知道了在云 WAF 解决方案中应该寻找什么，那么是时候比较一些首选方案了。以下是基于客户评论和专家意见的一些最佳案例:

### 云耀斑

对于寻找免费解决方案的人来说，Cloudflare 是一个受欢迎的选择。它提供基本的 WAF 保护，防止常见的攻击，如 SQL 注入和跨站脚本(XSS)。但是，它不提供更高级的功能，如 bot 管理或速率限制。

### F5 银线晶圆

F5 Silverline WAF 是需要高级保护的用户的不错选择。它提供了所有标准功能，加上 DDoS 保护和 web 应用程序防火墙。这是较贵的选择之一，每月起价 2500 美元。

### 封装企业晶圆

Incapsula Enterprise WAF 是高级保护的另一个好选择。它提供了所有的标准功能，加上 DDoS 保护和 web 应用程序防火墙。这也是较昂贵的选择之一，每月 2000 美元起。然而，它包括 14 天的免费试用。

### AWS 晶圆

对于那些寻求与其他亚马逊 Web 服务(AWS)产品集成的云 WAF 解决方案的人来说，AWS WAF 是一个不错的选择。它提供了所有的标准功能，加上 DDoS 保护和 web 应用程序防火墙。价格从每月 5 美元开始。

### 天蓝色薄饼

对于那些寻求与其他[微软 Azure 服务](/web/20221206202503/https://www.netguru.com/services/azure-managed-services)集成的云 WAF 解决方案的人来说，Azure WAF 是一个不错的选择。它提供了所有的标准功能，加上 DDoS 保护和 web 应用程序防火墙。价格从每月 5 美元开始。

### 帕洛阿尔托野火

对于那些寻求高级保护的人来说，WildFire 是一个不错的选择。它提供了所有的标准功能，加上 DDoS 保护和 web 应用程序防火墙。价格从每月 3500 美元起。

### CloudProxy 摘要

Sucuri 的 WAF 是那些寻找负担得起的解决方案的人的好选择。它提供了所有的标准功能，加上 DDoS 保护和 web 应用程序防火墙。价格从每月 200 美元起。

### 警报逻辑云卫士

对于寻求一体化解决方案的人来说，Alert Logic Cloud Defender 是一个不错的选择。它提供了所有的标准功能，加上 DDoS 保护和 web 应用程序防火墙。价格从每月 500 美元起。

### Imperva Incapsula

Imperva Incapsula 是寻求一体化解决方案的人的不错选择。它提供了所有的标准功能，加上 DDoS 保护和 web 应用程序防火墙。价格从每月 2000 美元起。

### 阿卡迈科纳遗址保卫者

Akamai KSD 是那些寻求一体化解决方案的人的好选择。它提供了所有的标准功能，加上 DDoS 保护和 web 应用程序防火墙。价格从每月 1500 美元起。

## 使用云 WAF 保护 web 应用

使用基于云的 WAF 有很多好处，包括增强安全性、提高性能、简化管理和降低成本。

选择云 WAF 解决方案时，考虑您的需求和要求非常重要。有些解决方案比其他解决方案提供更多的功能，因此在做出决定之前，一定要比较功能和价格。