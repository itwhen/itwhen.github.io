---
title: onMessageRescuing -
---
//[echo](../../index.md)/[tech.whence.echo.job.stream.monitor](../index.md)/[Monitor](index.md)/[onMessageRescuing](on-message-rescuing.md)



# onMessageRescuing  
[jvm]  
Brief description  


消息恢复时



#### Return  


MessageStrategy



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| cause| <br><br>Exception 恢复前异常<br><br>
| message| <br><br>Message 消息<br><br>
| provider| <br><br>Provider 消息提供者<br><br>
  
  
Content  
abstract fun [onMessageRescuing](on-message-rescuing.md)(provider: [Provider](../../tech.whence.echo.job.stream.provider/-provider/index.md), message: [Message](../../tech.whence.echo.job.stream.message/-message/index.md), cause: [Exception](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-exception/index.html)): [MessageStrategy](../-message-strategy/index.md)  



