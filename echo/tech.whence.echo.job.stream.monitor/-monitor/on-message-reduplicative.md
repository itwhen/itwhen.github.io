---
title: onMessageReduplicative -
---
//[echo](../../index.md)/[tech.whence.echo.job.stream.monitor](../index.md)/[Monitor](index.md)/[onMessageReduplicative](on-message-reduplicative.md)



# onMessageReduplicative  
[jvm]  
Brief description  


消息重复时



#### Return  


MessageStrategy



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| new| <br><br>Message 新消息<br><br>
| old| <br><br>Message 老消息<br><br>
  
  
Content  
abstract fun [onMessageReduplicative](on-message-reduplicative.md)(new: [Message](../../tech.whence.echo.job.stream.message/-message/index.md), old: [Message](../../tech.whence.echo.job.stream.message/-message/index.md)): [MessageStrategy](../-message-strategy/index.md)  



