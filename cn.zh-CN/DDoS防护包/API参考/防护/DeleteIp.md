# DeleteIp {#reference_265081 .reference}

调用DeleteIp接口将被防护IP从防护包中移除，取消防护。

**说明：** DDoS防护包的API接口目前仅对企业版DDoS防护包用户开放。

## 请求参数 {#section_0jj_pcr_rj0 .section}

|名称|类型|是否必选|描述|
|--|--|----|--|
|Action|String|是|要执行的操作，取值：DeleteIp。|
|InstanceId|String|是|要操作的防护包ID。|
|IpList|String|是|要从防护包中移除的被防护IP，多个IP间以逗号分隔。|

## 返回参数 {#section_1as_cc1_hc5 .section}

|名称|类型|描述|
|--|--|--|
|RequestId|String|本次请求的ID。|

## 示例 {#section_b48_y6o_uop .section}

请求示例

``` {#codeblock_60x_v7t_oqo}
https://ddosbgp.aliyuncs.com/?Action=DeleteIp
&InstanceId=ddosbgp-cn-xxx
&IpList=1.1.1.1,2.2.2.2
&公共请求参数
```

正常返回示例

-   `XML`格式

    ``` {#codeblock_yok_0bb_bul}
    <?xml version='1.0' encoding='UTF-8'?>
    <DeleteIpResponse>
        <RequestId>C33EB3D5-AF96-43CA-9C7E-37A81BC06A1E</RequestId>
    </DeleteIpResponse>
    ```

-   `JSON`格式

    ``` {#codeblock_ftr_37u_bst}
    {
        "RequestId":"4C467B38-3910-447D-87BC-AC049166F216"
    }
    ```


