---
title: onMessageProduced -
---
//[echo](../../index.md)/[tech.whence.echo.job.stream.monitor](../index.md)/[Monitor](index.md)/[onMessageProduced](on-message-produced.md)



# onMessageProduced  
[jvm]  
Brief description  


消息生产时



#### Return  


M?



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| producer| <br><br>Producer<M?> 消息生产<br><br>
| provider| <br><br>Provider 消息提供者<br><br>
  
  
Content  
abstract fun <[M](on-message-produced.md) : [Message](../../tech.whence.echo.job.stream.message/-message/index.md)> [onMessageProduced](on-message-produced.md)(provider: [Provider](../../tech.whence.echo.job.stream.provider/-provider/index.md), producer: [Producer](../../tech.whence.echo.function/-producer/index.md)<[M](on-message-produced.md)?>): [M](on-message-produced.md)?  



