---
title: Message -
---
//[echo](../../index.md)/[tech.whence.echo.job.stream.message](../index.md)/[Message](index.md)



# Message  
 [jvm] 

消息

interface [Message](index.md) : [Traceable](../../tech.whence.echo.job/-traceable/index.md)   


## Functions  
  
|  Name|  Summary| 
|---|---|
| [die](die.md)| [jvm]  <br>Brief description  <br><br><br>失效<br><br>  <br>Content  <br>abstract fun [die](die.md)(death: [Death](../-death/index.md))  <br><br><br>
| [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)| [jvm]  <br>Content  <br>open operator override fun [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>


## Properties  
  
|  Name|  Summary| 
|---|---|
| [createdAt](index.md#tech.whence.echo.job.stream.message/Message/createdAt/#/PointingToDeclaration/)|  [jvm] <br><br>Instant 创建时间<br><br>abstract val [createdAt](index.md#tech.whence.echo.job.stream.message/Message/createdAt/#/PointingToDeclaration/): [Instant](https://docs.oracle.com/javase/8/docs/api/java/time/Instant.html)   <br>
| [data](index.md#tech.whence.echo.job.stream.message/Message/data/#/PointingToDeclaration/)|  [jvm] <br><br>Map<String, Any?> 数据<br><br>abstract val [data](index.md#tech.whence.echo.job.stream.message/Message/data/#/PointingToDeclaration/): [Map](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)<[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?>   <br>
| [dead](index.md#tech.whence.echo.job.stream.message/Message/dead/#/PointingToDeclaration/)|  [jvm] <br><br>Boolean 是否失效<br><br>open val [dead](index.md#tech.whence.echo.job.stream.message/Message/dead/#/PointingToDeclaration/): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)   <br>
| [death](index.md#tech.whence.echo.job.stream.message/Message/death/#/PointingToDeclaration/)|  [jvm] <br><br>Death? 失效方式<br><br>abstract val [death](index.md#tech.whence.echo.job.stream.message/Message/death/#/PointingToDeclaration/): [Death](../-death/index.md)?   <br>
| [diedAt](index.md#tech.whence.echo.job.stream.message/Message/diedAt/#/PointingToDeclaration/)|  [jvm] <br><br>Instant? 失效时间<br><br>abstract val [diedAt](index.md#tech.whence.echo.job.stream.message/Message/diedAt/#/PointingToDeclaration/): [Instant](https://docs.oracle.com/javase/8/docs/api/java/time/Instant.html)?   <br>
| [id](index.md#tech.whence.echo.job.stream.message/Message/id/#/PointingToDeclaration/)|  [jvm] <br><br>String 编号<br><br>abstract override val [id](index.md#tech.whence.echo.job.stream.message/Message/id/#/PointingToDeclaration/): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)   <br>
| [key](index.md#tech.whence.echo.job.stream.message/Message/key/#/PointingToDeclaration/)|  [jvm] <br><br>String 键<br><br>abstract override val [key](index.md#tech.whence.echo.job.stream.message/Message/key/#/PointingToDeclaration/): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)   <br>
| [source](index.md#tech.whence.echo.job.stream.message/Message/source/#/PointingToDeclaration/)|  [jvm] <br><br>String? 来源<br><br>abstract val [source](index.md#tech.whence.echo.job.stream.message/Message/source/#/PointingToDeclaration/): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?   <br>
| [value](index.md#tech.whence.echo.job.stream.message/Message/value/#/PointingToDeclaration/)|  [jvm] <br><br>Accessor 值<br><br>abstract override val [value](index.md#tech.whence.echo.job.stream.message/Message/value/#/PointingToDeclaration/): [Accessor](../../tech.whence.echo.container.accessor/-accessor/index.md)   <br>


## Inheritors  
  
|  Name| 
|---|
| [AbstractMessage](../-abstract-message/index.md)
| [Task](../../tech.whence.echo.job.stream.task/-task/index.md)

