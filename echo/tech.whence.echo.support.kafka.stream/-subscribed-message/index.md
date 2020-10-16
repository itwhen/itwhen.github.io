---
title: SubscribedMessage -
---
//[echo](../../index.md)/[tech.whence.echo.support.kafka.stream](../index.md)/[SubscribedMessage](index.md)



# SubscribedMessage  
 [jvm] 

已订阅消息

class [SubscribedMessage](index.md)(**key**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), **value**: [Accessor](../../tech.whence.echo.container.accessor/-accessor/index.md), **source**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, **createdAt**: [Instant](https://docs.oracle.com/javase/8/docs/api/java/time/Instant.html), **responder**: [Responder](../../tech.whence.echo.job.stream.message/-responder/index.md)) : [AbstractResponsiveMessage](../../tech.whence.echo.job.stream.message/-abstract-responsive-message/index.md)   


## Constructors  
  
|  Name|  Summary| 
|---|---|
| [SubscribedMessage](-subscribed-message.md)|  [jvm] <br><br><br><br>fun [SubscribedMessage](-subscribed-message.md)(key: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), value: [Accessor](../../tech.whence.echo.container.accessor/-accessor/index.md), source: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, createdAt: [Instant](https://docs.oracle.com/javase/8/docs/api/java/time/Instant.html), responder: [Responder](../../tech.whence.echo.job.stream.message/-responder/index.md))   <br>


## Types  
  
|  Name|  Summary| 
|---|---|
| [Companion](-companion/index.md)| [jvm]  <br>Content  <br>object [Companion](-companion/index.md)  <br><br><br>


## Functions  
  
|  Name|  Summary| 
|---|---|
| [die](../../tech.whence.echo.job.stream.message/-abstract-responsive-message/die.md)| [jvm]  <br>Brief description  <br><br><br>失效<br><br>  <br>Content  <br>open override fun [die](../../tech.whence.echo.job.stream.message/-abstract-responsive-message/die.md)(death: [Death](../../tech.whence.echo.job.stream.message/-death/index.md))  <br><br><br>
| [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)| [jvm]  <br>Content  <br>open operator override fun [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [respond](../../tech.whence.echo.job.stream.message/-abstract-responsive-message/respond.md)| [jvm]  <br>Brief description  <br><br><br>响应 默认响应失败状态<br><br>  <br>Content  <br>open override fun [respond](../../tech.whence.echo.job.stream.message/-abstract-responsive-message/respond.md)(state: [Responder.State](../../tech.whence.echo.job.stream.message/-responder/-state/index.md))  <br><br><br>
| [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>


## Properties  
  
|  Name|  Summary| 
|---|---|
| [createdAt](index.md#tech.whence.echo.support.kafka.stream/SubscribedMessage/createdAt/#/PointingToDeclaration/)|  [jvm] <br><br>Instant 创建时间<br><br>open override val [createdAt](index.md#tech.whence.echo.support.kafka.stream/SubscribedMessage/createdAt/#/PointingToDeclaration/): [Instant](https://docs.oracle.com/javase/8/docs/api/java/time/Instant.html)   <br>
| [data](index.md#tech.whence.echo.support.kafka.stream/SubscribedMessage/data/#/PointingToDeclaration/)|  [jvm] <br><br>Map<String, Any?> 数据<br><br>open override val [data](index.md#tech.whence.echo.support.kafka.stream/SubscribedMessage/data/#/PointingToDeclaration/): [Map](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)<[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?>   <br>
| [dead](index.md#tech.whence.echo.support.kafka.stream/SubscribedMessage/dead/#/PointingToDeclaration/)|  [jvm] <br><br>Boolean 是否失效<br><br>open override val [dead](index.md#tech.whence.echo.support.kafka.stream/SubscribedMessage/dead/#/PointingToDeclaration/): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)   <br>
| [death](index.md#tech.whence.echo.support.kafka.stream/SubscribedMessage/death/#/PointingToDeclaration/)|  [jvm] <br><br>Death? 失效方式<br><br>open override var [death](index.md#tech.whence.echo.support.kafka.stream/SubscribedMessage/death/#/PointingToDeclaration/): [Death](../../tech.whence.echo.job.stream.message/-death/index.md)?   <br>
| [diedAt](index.md#tech.whence.echo.support.kafka.stream/SubscribedMessage/diedAt/#/PointingToDeclaration/)|  [jvm] <br><br>Instant? 失效时间<br><br>open override var [diedAt](index.md#tech.whence.echo.support.kafka.stream/SubscribedMessage/diedAt/#/PointingToDeclaration/): [Instant](https://docs.oracle.com/javase/8/docs/api/java/time/Instant.html)?   <br>
| [id](index.md#tech.whence.echo.support.kafka.stream/SubscribedMessage/id/#/PointingToDeclaration/)|  [jvm] <br><br>String 编号<br><br>open override val [id](index.md#tech.whence.echo.support.kafka.stream/SubscribedMessage/id/#/PointingToDeclaration/): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)   <br>
| [key](index.md#tech.whence.echo.support.kafka.stream/SubscribedMessage/key/#/PointingToDeclaration/)|  [jvm] <br><br>String 键<br><br>open override val [key](index.md#tech.whence.echo.support.kafka.stream/SubscribedMessage/key/#/PointingToDeclaration/): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)   <br>
| [source](index.md#tech.whence.echo.support.kafka.stream/SubscribedMessage/source/#/PointingToDeclaration/)|  [jvm] <br><br>String? 来源<br><br>open override val [source](index.md#tech.whence.echo.support.kafka.stream/SubscribedMessage/source/#/PointingToDeclaration/): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?   <br>
| [value](index.md#tech.whence.echo.support.kafka.stream/SubscribedMessage/value/#/PointingToDeclaration/)|  [jvm] <br><br>Accessor 值<br><br>open override val [value](index.md#tech.whence.echo.support.kafka.stream/SubscribedMessage/value/#/PointingToDeclaration/): [Accessor](../../tech.whence.echo.container.accessor/-accessor/index.md)   <br>

