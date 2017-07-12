# ServerInterfaceDoc
To store some communication document



### 20.2更改押金状态
- url:{url}/business/mpos/mposLeaseTotalTrade/updateStatus
- HTTP请求方式：post
- 请求参考



 字段名 | 必填 | 名称 | 类型| 说明|
---|---|---|---|---|
psamNo | true |psam卡号|String|
isBackDeposit| true|押金状态|String

  - 备注 ：无
  - 返回参数
  
```
{retCode:'0000',regMsg:'成功'}
字段名 | 名称 | 类型| 说明|
---|---|---|---|
retCode | 返回状态码 |String|000000:成功
retMsg| 返回信息|String|成功
retData|返回数据对象|Object|
