# WIFI反查接口示例
>维护人员：王彩霖  
>创建时间：2017-12-02

## 接口简介
WIFI反查接口  

## 接口详情

### 请求地址
/api/customer-flow

### 请求类型
POST

### 请求参数
| 参数名 | 类型 | 必填 | 描述 | 默认值 | 参考值 |
| --- | :---: | :---: | --- | --- | --- |
| lat | string | 是 | 经度 | - | - |
| lon | string | 是 | 纬度 | - | - |
| n | string | 否 | 返回条数 | - | - |

### 返回正确JSON示例
```javascript
{
    "success": true,
    "code": 0,
    "msg": "ok",
    "data": [
      {
        "mac": "9c:21:6a:8f:33:f8",
        "acc": 83,
        "location": {
          "lon": 116.354031,
          "lat": 39.527195
        }
      }
    ]
}
```
### 返回错误JSON示例
```javascript

```

### 备注说明
无

### 修改日志
- 无
