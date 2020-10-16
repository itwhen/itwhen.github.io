---
title: of -
---
//[echo](../../../index.md)/[tech.whence.echo.support.kafka.stream](../../index.md)/[SubscribedMessage](../index.md)/[Companion](index.md)/[of](of.md)



# of  
[jvm]  
Brief description  


构造



#### Return  


SubscribedMessage



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| context| <br><br>ProcessorContext 上下文<br><br>
| key| <br><br>String 键<br><br>
| responder| <br><br>Responder 响应器<br><br>
| value| <br><br>Accessor 值<br><br>
  
  
Content  
@[JvmStatic](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-static/index.html)()  
  
fun [of](of.md)(key: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), value: [Accessor](../../../tech.whence.echo.container.accessor/-accessor/index.md), context: ProcessorContext, responder: [Responder](../../../tech.whence.echo.job.stream.message/-responder/index.md)): [SubscribedMessage](../index.md)  


[jvm]  
Brief description  


构造



#### Return  


SubscribedMessage



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| context| <br><br>ProcessorContext 上下文<br><br>
| data| <br><br>KeyValue<String, Accessor> 数据<br><br>
| responder| <br><br>Responder 响应器<br><br>
  
  
Content  
@[JvmStatic](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-static/index.html)()  
  
fun [of](of.md)(data: KeyValue<[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), [Accessor](../../../tech.whence.echo.container.accessor/-accessor/index.md)>, context: ProcessorContext, responder: [Responder](../../../tech.whence.echo.job.stream.message/-responder/index.md)): [SubscribedMessage](../index.md)  


[jvm]  
Brief description  


构造



#### Return  


SubscribedMessage



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| key| <br><br>String 键<br><br>
| value| <br><br>Accessor 值<br><br>
  
  
Content  
@[JvmStatic](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-static/index.html)()  
  
fun [of](of.md)(key: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), value: [Accessor](../../../tech.whence.echo.container.accessor/-accessor/index.md)): [SubscribedMessage](../index.md)  


[jvm]  
Brief description  


构造



#### Return  


SubscribedMessage



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| createdAt| <br><br>Instant 创建时间<br><br>
| key| <br><br>String 键<br><br>
| value| <br><br>Accessor 值<br><br>
  
  
Content  
@[JvmStatic](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-static/index.html)()  
  
fun [of](of.md)(key: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), value: [Accessor](../../../tech.whence.echo.container.accessor/-accessor/index.md), createdAt: [Instant](https://docs.oracle.com/javase/8/docs/api/java/time/Instant.html)): [SubscribedMessage](../index.md)  



