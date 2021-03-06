## 接口描述 
**描述**：使用 userid 删除企业用户，目前暂不支持 OAuth2.0 鉴权访问。
**调用方式**：DELETE
**接口请求域名**：
```Plaintext
https://api.meeting.qq.com/v1/users/{userid}
```




## 输入参数

以下请求参数列表仅列出了接口请求参数，HTTP 请求头公共参数请参见签名验证章节的 [公共参数说明](https://cloud.tencent.com/document/product/1095/42413#.E5.85.AC.E5.85.B1.E5.8F.82.E6.95.B0)。

| 参数名称 | 必选 | 参数类型 | 参数描述 |
| -------- | ---- | -------- | -------- |
| userid   | 是   | String   | 	调用方用于标示用户的唯一 ID（例如企业用户可以为企业账户英文名、个人用户可以为手机号等）。 |



## 输出参数
无输出参数，成功返回空消息体，失败返回 [错误码](https://cloud.tencent.com/document/product/1095/43704) 和错误信息。



## 示例

#### 输入示例
```plaintext
DELETE https://api.meeting.qq.com/v1/users/9527
```

#### 输出示例
删除用户成功，返回 Body 为空。
