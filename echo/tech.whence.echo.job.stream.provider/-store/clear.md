---
title: clear -
---
//[echo](../../index.md)/[tech.whence.echo.job.stream.provider](../index.md)/[Store](index.md)/[clear](clear.md)



# clear  
[jvm]  
Brief description  


移除消息



#### Return  


Message?



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| key| <br><br>String 指定消息键名<br><br>
  
  
Content  
fun [clear](clear.md)(key: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): [Message](../../tech.whence.echo.job.stream.message/-message/index.md)?  


[jvm]  
Brief description  


移除消息



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| predicate| <br><br>Predicate<Message> 指定条件<br><br>
  
  
Content  
fun [clear](clear.md)(predicate: [Predicate](../../tech.whence.echo.function/-predicate/index.md)<[Message](../../tech.whence.echo.job.stream.message/-message/index.md)>)  


[jvm]  
Brief description  


清理全部消息

  
Content  
fun [clear](clear.md)()  



