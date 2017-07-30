# 绑定上网卡号

* POST `/capi.php`
* c `93`

## 请求参数

| 参数名 | 参数类型 | 参数说明 | 备注 |
| :---- | :----| :----| :---- |
| sid | string | sessionid | 登录成功后返回 |
| id | string | 用户id | 登录成功后返回 |
| netcard | string | 上网卡号 |

## 返回参数

| 参数名 | 参数类型 | 参数说明 | 备注 |
| :---- | :----| :----| :---- |

## 返回实例

```JSON
{
  "status": 1,
  "info": "",
  "data": {
	"netcard":"855422483201"
  }
}
```