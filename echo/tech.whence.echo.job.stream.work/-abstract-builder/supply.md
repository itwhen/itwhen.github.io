---
title: supply -
---
//[echo](../../index.md)/[tech.whence.echo.job.stream.work](../index.md)/[AbstractBuilder](index.md)/[supply](supply.md)



# supply  
[jvm]  
Brief description  


设置指定任务提供者



#### Return  


A



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| provider| <br><br>SupplyingProvider 指定提供者<br><br>
  
  
Content  
fun [supply](supply.md)(provider: [SupplyingProvider](../../tech.whence.echo.job.stream.provider/-supplying-provider/index.md)): [A](index.md)  


[jvm]  
Brief description  


设置指定任务提供者



#### Return  


A



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| name| <br><br>String 名称<br><br>
| producer| <br><br>Producer<List<Message>> 消息生产<br><br>
  
  
Content  
fun [supply](supply.md)(name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), producer: [Producer](../../tech.whence.echo.function/-producer/index.md)<[List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[Message](../../tech.whence.echo.job.stream.message/-message/index.md)>>): [A](index.md)  



