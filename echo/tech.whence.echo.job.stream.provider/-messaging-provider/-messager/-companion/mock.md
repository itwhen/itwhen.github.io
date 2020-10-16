---
title: mock -
---
//[echo](../../../../index.md)/[tech.whence.echo.job.stream.provider](../../../index.md)/[MessagingProvider](../../index.md)/[Messager](../index.md)/[Companion](index.md)/[mock](mock.md)



# mock  
[jvm]  
Brief description  


模拟



#### Return  


Messager



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| delay| <br><br>Duration? 延迟<br><br>
| producer| <br><br>Producer<Iterable<Message>> 消息生产<br><br>
| times| <br><br>Int 次数<br><br>
  
  
Content  
@[JvmStatic](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-static/index.html)()  
  
fun [mock](mock.md)(producer: [Producer](../../../../tech.whence.echo.function/-producer/index.md)<[Iterable](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-iterable/index.html)<[Message](../../../../tech.whence.echo.job.stream.message/-message/index.md)>>, times: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), delay: [Duration](https://docs.oracle.com/javase/8/docs/api/java/time/Duration.html)?): [MessagingProvider.Messager](../index.md)  


[jvm]  
Brief description  


无限次数模拟



#### Return  


Messager



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| producer| <br><br>Producer<Iterable<Message>> 消息生产<br><br>
  
  
Content  
@[JvmStatic](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-static/index.html)()  
  
fun [mock](mock.md)(producer: [Producer](../../../../tech.whence.echo.function/-producer/index.md)<[Iterable](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-iterable/index.html)<[Message](../../../../tech.whence.echo.job.stream.message/-message/index.md)>>): [MessagingProvider.Messager](../index.md)  


[jvm]  
Brief description  


模拟一次



#### Return  


Messager



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| messages| <br><br>Iterable<Message> 消息集合<br><br>
  
  
Content  
@[JvmStatic](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-static/index.html)()  
  
fun [mock](mock.md)(messages: [Iterable](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-iterable/index.html)<[Message](../../../../tech.whence.echo.job.stream.message/-message/index.md)>): [MessagingProvider.Messager](../index.md)  



