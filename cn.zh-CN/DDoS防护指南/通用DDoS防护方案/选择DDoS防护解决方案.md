# 选择DDoS防护解决方案 {#concept_827629 .concept}

阿里云基于多年的DDoS攻防经验和领先的安全技术，提供多款商业化安全解决方案供您选择，满足您业务中对各类DDoS攻击安全防护场景的需求。

## 高风险DDoS攻击防御场景 {#section_bi8_fyx_we8 .section}

| 高风险DDoS攻击防御场景具体包含以下特点：

-   遭受恶意攻击者的DDoS攻击勒索
-   遭受的DDoS攻击已经导致您的业务不可用，需要紧急恢复
-   频繁遭受DDoS攻击，需要持续的DDoS防护安全方案保护业务的稳定性

 针对这些场景，推荐您根据业务的部署情况，选择以下阿里云DDoS防护安全解决方案： -   业务部署在**中国大陆**地域，且业务的主要目标用户为**中国大陆**地区用户：
    -   推荐您选择[新BGP高防服务](https://common-buy.aliyun.com/?commodityCode=ddoscoo#/buy) 。
    -   更多详情，请参见[新BGP高防](../../../../cn.zh-CN/新BGP高防IP/产品简介/什么是新BGP高防IP.md#)。
-   业务部署在**非中国大陆**地域，且业务的主要目标用户为**非中国大陆**地区用户：
    -   推荐您选择[DDoS高防（国际）服务](https://common-buy.aliyun.com/?commodityCode=ddosDip#/buy) 。
    -   更多详情，请参见[DDoS高防（国际）](../../../../cn.zh-CN/DDoS高防（国际）/产品简介/什么是DDoS高防（国际）.md#)。
-   业务部署在**非中国大陆**地域，且业务的主要目标用户为**中国大陆**地区用户：
    -   推荐您选择[DDoS高防（国际）出海套餐](https://package-buy.aliyun.com/?planId=1019020001141701&accounttraceid=eb315d7e-bd27-4f6a-a2f2-aeab6168a552#/buy)。
    -   更多详情，请参见[DDoS高防（国际）](../../../../cn.zh-CN/DDoS高防（国际）/产品简介/什么是DDoS高防（国际）.md#)和[加速线路](../../../../cn.zh-CN/DDoS高防（国际）/产品定价/加速线路.md#)。

 | **DDoS高防安全解决方案架构** ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/669216/156152576650168_zh-CN.png)

 |

## 低风险DDoS攻击防御（大规模业务）场景 {#section_dhp_3s0_f4m .section}

| 低风险DDoS攻击防御场景具体包含以下特点：

-   业务资源部署在阿里云环境
-   业务规模较大。例如，业务带宽大于1 Gbps，HTTP/S业务QPS大于5,000
-   偶尔遭受DDoS攻击
-   具有IPv6访问流量的防护需求

 针对这些场景，推荐您选择阿里云原生DDoS防护安全解决方案[DDoS防护包](https://common-buy.aliyun.com/?commodityCode=ddosbgp#/buy)。 更多详情，请参见[DDoS防护包](../../../../cn.zh-CN/DDoS防护包/产品简介/什么是DDoS防护包.md#)。

 | **DDoS防护包安全解决方案架构** ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/669216/156152576650169_zh-CN.png)

 |

## 移动端业务为主的DDoS攻击防御场景 {#section_boz_s11_0tj .section}

移动端业务DDoS攻击防御场景具体包含以下特点：

-   主要业务为移动端游戏业务
-   具备集成阿里云SDK的能力
-   业务实时性要求高，对自定义传输协议存在精细化防护需求
-   具有网络传输加速需求
-   具有网络加密传输需求
-   需要追溯DDoS攻击的来源

针对这些场景，推荐您选择阿里云专为解决游戏行业面临的DDoS、CC攻击推出的针对性安全解决方案[游戏盾](../../../../cn.zh-CN/产品简介/什么是游戏盾.md#)。

## 阿里云DDoS防护解决方案 {#section_9lj_vni_0pk .section}

|名称|简介|应用场景|可防御的攻击流量|
|--|--|----|--------|
| [DDoS基础防护](../../../../cn.zh-CN/DDoS基础防护服务/产品简介/什么是DDoS基础防护.md#) |阿里云提供的基础服务，根据您所购买的阿里云产品免费提供最大5G的DDoS防护能力。同时，您还可以加入安全信誉联盟，根据您的安全信誉分获得更高的安全防护能力。|购买阿里云产品即可获得的基础DDoS防护能力，仅可满足最低的安全需求，对于有更高安全防护需求的用户建议额外选择其他安全方案。|支持防御不超过5G的DDoS攻击|
| [DDoS防护包](../../../../cn.zh-CN/DDoS防护包/产品简介/什么是DDoS防护包.md#) |阿里云提供的直接提升阿里云ECS、SLB、WAF、EIP等云产品DDoS防护能力的安全方案。通过简单的配置，将DDoS防护包提供的安全能力直接加载到云产品上，提升安全防护能力。| -   在线视频、直播答题等对业务流畅要求比较高（低延迟）的DDoS攻击防护
-   业务中存在大量端口、域名、IP的DDoS攻击防护

 |支持全力防御|
| [新BGP高防](../../../../cn.zh-CN/新BGP高防IP/产品简介/什么是新BGP高防IP.md#)  [DDoS高防（国际）](../../../../cn.zh-CN/DDoS高防（国际）/产品简介/什么是DDoS高防（国际）.md#) 

 |阿里云提供的解决互联网服务器（包括非阿里云主机）遭受大流量DDoS攻击的安全方案。通过配置DDoS高防，将攻击流量牵引至高防，确保源站服务器稳定可靠。| -   金融、电商、门户类网站的DDoS攻击防护
-   政府互联网出口、门户与开放平台的DDoS攻击防护
-   重大线上直播、活动推广促销场景的DDoS攻击防护
-   业务遭竞争对手恶意攻击、勒索场景的安全防护
-   移动业务（APP）遭恶意注册、刷单、刷流量场景的安全防护

 |支持全力防御|
| [游戏盾](../../../../cn.zh-CN/产品简介/什么是游戏盾.md#) |阿里云针对游戏行业面对的DDoS、CC攻击提供的行业针对性安全解决方案。相比于高防IP，除有效防御大型DDoS攻击（T级别）外，游戏盾还具备彻底解决游戏行业特有的TCP协议的CC攻击问题的能力。| -   游戏行业遭受大流量带宽压制场景的安全防护
-   游戏行业遭受海量肉鸡长时间机器人攻击（Bot attack）场景的安全防护

 |支持全力防御|

