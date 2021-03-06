# Linux软件漏洞参数说明 {#concept_akr_grq_32b .concept}

本文档介绍了Linux软件漏洞中各项参数的含义及说明，帮助您详细了解态势感知检测到的Linux软件漏洞以及相关操作。

**说明：** 态势感知**基础版**只提供漏洞检测，不提供漏洞修复的服务；如需一键修复漏洞，请开通态势感知**企业版**。基础版和企业版详细功能介绍参见[功能特性](../../../../../cn.zh-CN/产品简介/功能特性.md#)。

## 操作步骤 {#section_lst_wsc_ygb .section}

1.  登录阿里云[态势感知控制台](https://yundun.console.aliyun.com/?p=sas)。
2.  定位到**漏洞管理** \> **Linux软件漏洞**。

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/15298/155166977839856_zh-CN.png)

3.  您可以在Linux软件漏洞页面查看态势感知检测到的所有linux软件漏洞的详细信息、执行验证和修复漏洞、根据漏洞的严重程度和状态对特定漏洞进行定位、将漏洞加入白名单或忽略漏洞。
    -   **查看漏洞详情**

        单击漏洞列表中的漏洞名称打开漏洞详情页面。您可在漏洞详情页面查看该漏洞的描述、漏洞紧急程度、漏洞影响的所有资产信息、漏洞的状态，并可对漏洞执行验证、修复或忽略的操作。

        ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/15298/155166977939857_zh-CN.png)

        漏洞详情页面可展示该漏洞所有**关联漏洞**，即该漏洞影响的所有资产信息，方便您对所有相关的漏洞进行分析和批量处理。

        ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/15298/155166977939858_zh-CN.png)

        漏洞紧急程度用不同颜色的图标表示。红色图标表示**高危**漏洞、橙色图标表示**中危**漏洞、灰色图标表示**低危**漏洞。

        ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/118684/155166977939814_zh-CN.png)

        **说明：** 建议立即修复高危漏洞（紧急程度高）。

    -   **验证漏洞**

        您可在漏洞详情页面**验证**单个漏洞或对多个关联漏洞进行批量验证，检测该漏洞是否已修复成功。

        单击**验证**后，该漏洞的**状态**转为**验证中**。需要等待数秒后漏洞验证才可完成。

        ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/15298/155166977939859_zh-CN.png)

    -   **修复漏洞**

        您可在漏洞详情页面单击**立即修复**对单个漏洞进行修复或对多个关联漏洞进行批量修复。

    -   **搜索漏洞**

        您可在Linux软件漏洞页面通过筛选漏洞危险等级（高、中、低）、漏洞处理状态（已处理、未处理）或输入漏洞名称定位到相关的漏洞。

        ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/15298/155166977939860_zh-CN.png)

        **说明：** 搜索漏洞名称支持模糊查询。

    -   **将漏洞加入白名单**

        您可在Linux软件漏洞页面勾选漏洞列表左侧的复选框后单击**加入白名单**，将该漏洞加入白名单中。加入白名单后，态势感知将不再对白名单中的漏洞进行告警。

        ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/15298/155166977939861_zh-CN.png)

        加入白名单的漏洞将从Linux软件漏洞的漏洞列表中移除，并记录在[漏洞管理设置](cn.zh-CN/用户指南/漏洞管理/漏洞管理设置.md#)页面的**漏洞白名单配置**列表中。

        如需恢复态势感知对白名单中的漏洞进行检测和告警提示，可在漏洞管理设置页面**移除**该漏洞。

        ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/118684/155166977939827_zh-CN.png)

    -   **忽略漏洞**

        您可在Linux软件漏洞页面勾选漏洞列表左侧的复选框后单击**忽略**，态势感知将不再提示该漏洞。

        **说明：** 被**忽略**的漏洞状态将转为**已处理**。如需态势感知继续对该漏洞进行告警提示，可在**已处理**的漏洞列表中找到该漏洞并对其**取消忽略**。

    -   **导出漏洞**

        您可在Linux软件漏洞页面单击**导出**将态势感知检测到的所有Windows系统漏洞统一导出并保存到本地。导出的文件为Excel格式。

        **说明：** 根据您资产中漏洞数据的大小，导出漏洞列表可能需要耗费一定时间，请耐心等待。

    -   您可在漏洞详情页面单击![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/118684/155166977939821_zh-CN.png)按钮保存筛选出的所有漏洞为一个漏洞修复批次，方便您对该批次漏洞的状态进行持续跟踪。

        ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/15298/155166977939862_zh-CN.png)


## Linux软件漏洞参数描述 {#section_dhc_1vq_32b .section}

下表介绍了Linux软件漏洞详情页各参数的描述：

|参数|描述|
|--|--|
|漏洞名称|该Linux软件漏洞的名称，一般以CVE及RHSA开头。例如，CVE-2018-1123 on Ubuntu 14.04 LTS \(trustly\)|
|影响分（CVSS分值）|CVSS分值是依据行业公开标准，通用漏洞评分系统（Common Vulnerability Scoring System），对该漏洞判定的一个分值，主要用于评测漏洞的严重程度，可以帮助您确定所需反应的紧急度和重要度。在CVSS v3.0评分体系中，不同分值代表的漏洞严重程度如下：

-   0.0：无漏洞
-   0.1-3.9：低危
    -   可导致本地拒绝服务的漏洞。
    -   其他危害较低的漏洞。
-   4.0-6.9：中危
    -   需要进行交互才能影响用户的漏洞。
    -   可导致普通越权操作的漏洞。
    -   通过本地修改配置或获取信息之后，可进一步利用的漏洞。
-   7.0-8.9：高危
    -   可间接获取服务器和应用系统的普通权限的漏洞。
    -   可导致任意文件读取、下载、写入、或删除的漏洞。
    -   可导致敏感信息泄漏的漏洞。
    -   可直接导致业务中断、或远程拒绝服务的漏洞。
-   9.0-10.0：严重
    -   可直接获取服务器系统权限的漏洞。
    -   可直接获取重要的敏感信息，导致数据泄漏的漏洞。
    -   可直接导致敏感信息越权访问的漏洞。
    -   可造成大范围影响的其他漏洞。

|
|披露时间|该漏洞被披露的时间点。|
|漏洞编号|该漏洞对应的CVE漏洞号。Common Vulnerabilities & Exposures（CVE）是已被广泛认同的信息安全漏洞或者已经暴露的弱点的公共名称。通过漏洞编号（如CVE-2018-1123），您可以快速地在任何其它CVE兼容的数据库中找到相应漏洞修复的信息，帮助您解决安全问题。|
|影响资产|存在该漏洞的服务器资产信息，包括资产的公网/私网IP地址等。|
|修复必要性|根据漏洞本身等级、公开时间、ECS真实环境等因素综合分析出来的修复建议，供作参考。具体包括：-   **需尽快修复**
-   **可延后修复**
-   **暂可不修复**

**说明：** 关于漏洞修复必要性的计算方法，请查看[漏洞修复必要性说明](cn.zh-CN/用户指南/漏洞管理/漏洞修复必要性说明.md#)。

|
|影响说明|软件版本、配置详情、影响内容等。-   **软件**：该软件在当前服务器系统中的版本信息。
-   **命中**：该漏洞的匹配命中原因，一般是由于当前软件版本不满足或者小于某个版本（以小于某个版本为主）。
-   单击右侧**更多**还可以可查看**路径**：该软件在服务器上的路径。

|
|最后发现时间|该Linux软件漏洞最近一次进行态势感知漏洞检测时被发现的时间。|

