---
title: onMessageLosing -
---
//[echo](../../index.md)/[tech.whence.echo.job.stream.monitor](../index.md)/[Monitor](index.md)/[onMessageLosing](on-message-losing.md)



# onMessageLosing  
[jvm]  
Brief description  


消息丢弃时



#### Return  


MessageStrategy



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| message| <br><br>Message 消息<br><br>
| provider| <br><br>Provider 消息提供者<br><br>
  
  
Content  
abstract fun [onMessageLosing](on-message-losing.md)(provider: [Provider](../../tech.whence.echo.job.stream.provider/-provider/index.md), message: [Message](../../tech.whence.echo.job.stream.message/-message/index.md)): [MessageStrategy](../-message-strategy/index.md)  



