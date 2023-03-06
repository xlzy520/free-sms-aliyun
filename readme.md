# 免费的阿里云短信(1000条)
曾经因为一些原因买了1000条短信用量，但是后面一直没有使用，今天偶然上线看到居然还有那么多条，不用可惜了，于是开源出来，如果有帮助，希望可以点个`star`

## Config
```js
// 删除中间的空格
sms.accessKeyId=LTAI5tJm2Q     jnE7Xu8Lrv2K9K  
sms.secret=9dgZRUOUzm      3Du3UKl5prkAd49PpOfd
sms.signName=洁雅康
```

## 消息模板
短信验证码
```text
sms.TemplateCode1=SMS_217436891 //
变量：code
预览：您正在申请手机注册，验证码为：${code}，5分钟内有效！
```
1. 模板1（小说更新提醒）
```text
sms.TemplateCode1=SMS_185241056 //
变量：novelName
预览：这里是执笔看墨花开，你的 ${novelName} 的最新一章更新了
```
2. 模板2 （发货通知）
```text
sms.TemplateCode1=SMS_173342058
变量：orderNumber
预览：尊敬的用户，您的订单：${orderNumber}已发货，请注意查收。
```
3. 模板3 （新订单提醒）
```text
sms.TemplateCode1=SMS_172887274 //
变量：无
预览：您有新的订单了，请及时处理。
```
