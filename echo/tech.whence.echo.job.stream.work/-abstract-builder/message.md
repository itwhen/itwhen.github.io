---
title: message -
---
//[echo](../../index.md)/[tech.whence.echo.job.stream.work](../index.md)/[AbstractBuilder](index.md)/[message](message.md)



# message  
[jvm]  
Brief description  


设置普通任务提供者



#### Return  


A



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| provider| <br><br>MessagingProvider 指定提供者<br><br>
  
  
Content  
fun [message](message.md)(provider: [MessagingProvider](../../tech.whence.echo.job.stream.provider/-messaging-provider/index.md)): [A](index.md)  


[jvm]  
Brief description  


设置普通任务提供者



#### Return  


A



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| messager| <br><br>Messager 消息发送器<br><br>
| stamp| <br><br>String? 时间戳标记<br><br>
  
  
Content  
fun [message](message.md)(messager: [MessagingProvider.Messager](../../tech.whence.echo.job.stream.provider/-messaging-provider/-messager/index.md), stamp: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?): [A](index.md)  


[jvm]  
Brief description  


设置普通任务提供者



#### Return  


A



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| messager| <br><br>Messager 消息发送器<br><br>
| responseAt| <br><br>Set<ResponseTiming> 响应时机<br><br>
| stamp| <br><br>String? 时间戳标记<br><br>
| suppliers| <br><br>Int 提供者数量<br><br>
  
  
Content  
fun [message](message.md)(messager: [MessagingProvider.Messager](../../tech.whence.echo.job.stream.provider/-messaging-provider/-messager/index.md), stamp: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, suppliers: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), responseAt: [Set](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-set/index.html)<[ResponseTiming](../../tech.whence.echo.job.stream.message/-response-timing/index.md)>): [A](index.md)  



