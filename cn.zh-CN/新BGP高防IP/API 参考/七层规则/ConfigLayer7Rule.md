# ConfigLayer7Rule {#reference834 .reference}

调用ConfigLayer7Rule编辑7层转发规则。

## 请求参数 { .section}

|名称|类型|是否必需|描述|
|--|--|----|--|
|Domain|String|是|要操作的域名。|
|RsType|Integer|是|源站类型，取值： -   0：IP
-   1：域名

 |
|InstanceIds.N|String|否|要绑定的实例Id。若有多个实例，依次传入InstanceIds.1, InstanceIds.2, InstanceIds.3, ... **说明：** 若不传入该参数，则只添加域名，不绑定到具体IP。

 |
|RealServers.N|String|是|源站IP。若有多个源站IP，依次传入RealServers.1, RealServers.2, RealServers.3, ...|
|ProxyTypeList|String|是|协议数组。具体结构描述见[ProxyTypeList](#ProxyTypeList)。|

|名称|类型|描述|
|--|--|--|
|ProxyType|String|协议类型。取值： -   http
-   https
-   websocket
-   websockets

 |
|ProxyPorts|Integer|协议端口。|

## 返回参数 { .section}

|名称|类型|描述|
|--|--|--|
|RequestId|String|本次请求的ID。|

## 示例 { .section}

**请求示例** 

```
{
  "Domain": "www.alibaba.com",
  "RsType" : 0,
  "RealServers.1": "1.1.1.1",
  "InstanceIds.1": "xxxx",
  "ProxyTypeList": "[{\"ProxyPorts\":[80,8080],\"ProxyType\":\"http\"},{\"ProxyPorts\":[443],\"ProxyType\":\"https\"}]"
}
				
```

**返回示例** 

```
{
  "RequestId": "0bcf28g5-d57c-11e7-9bs0-d89d6717dxbc"
}
				
```

