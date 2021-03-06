---
title: AbstractResponsiveMessage -
---
//[echo](../../index.md)/[tech.whence.echo.job.stream.message](../index.md)/[AbstractResponsiveMessage](index.md)



# AbstractResponsiveMessage  
 [jvm] 

抽象响应式消息

abstract class [AbstractResponsiveMessage](index.md)(**id**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), **key**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), **value**: [Accessor](../../tech.whence.echo.container.accessor/-accessor/index.md), **source**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, **createdAt**: [Instant](https://docs.oracle.com/javase/8/docs/api/java/time/Instant.html), **responder**: [Responder](../-responder/index.md)) : [AbstractMessage](../-abstract-message/index.md), [Responsive](../-responsive/index.md)   


## Constructors  
  
|  Name|  Summary| 
|---|---|
| [AbstractResponsiveMessage](-abstract-responsive-message.md)|  [jvm] <br><br><br><br>fun [AbstractResponsiveMessage](-abstract-responsive-message.md)(id: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), key: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), value: [Accessor](../../tech.whence.echo.container.accessor/-accessor/index.md), source: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, createdAt: [Instant](https://docs.oracle.com/javase/8/docs/api/java/time/Instant.html), responder: [Responder](../-responder/index.md))   <br>


## Functions  
  
|  Name|  Summary| 
|---|---|
| [die](die.md)| [jvm]  <br>Brief description  <br><br><br>失效<br><br>  <br>Content  <br>open override fun [die](die.md)(death: [Death](../-death/index.md))  <br><br><br>
| [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)| [jvm]  <br>Content  <br>open operator override fun [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [respond](respond.md)| [jvm]  <br>Brief description  <br><br><br>响应 默认响应失败状态<br><br>  <br>Content  <br>open override fun [respond](respond.md)(state: [Responder.State](../-responder/-state/index.md))  <br><br><br>
| [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>


## Properties  
  
|  Name|  Summary| 
|---|---|
| [createdAt](index.md#tech.whence.echo.job.stream.message/AbstractResponsiveMessage/createdAt/#/PointingToDeclaration/)|  [jvm] <br><br>Instant 创建时间<br><br>open override val [createdAt](index.md#tech.whence.echo.job.stream.message/AbstractResponsiveMessage/createdAt/#/PointingToDeclaration/): [Instant](https://docs.oracle.com/javase/8/docs/api/java/time/Instant.html)   <br>
| [data](index.md#tech.whence.echo.job.stream.message/AbstractResponsiveMessage/data/#/PointingToDeclaration/)|  [jvm] <br><br>Map<String, Any?> 数据<br><br>open override val [data](index.md#tech.whence.echo.job.stream.message/AbstractResponsiveMessage/data/#/PointingToDeclaration/): [Map](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)<[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?>   <br>
| [dead](index.md#tech.whence.echo.job.stream.message/AbstractResponsiveMessage/dead/#/PointingToDeclaration/)|  [jvm] <br><br>Boolean 是否失效<br><br>open override val [dead](index.md#tech.whence.echo.job.stream.message/AbstractResponsiveMessage/dead/#/PointingToDeclaration/): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)   <br>
| [death](index.md#tech.whence.echo.job.stream.message/AbstractResponsiveMessage/death/#/PointingToDeclaration/)|  [jvm] <br><br>Death? 失效方式<br><br>open override var [death](index.md#tech.whence.echo.job.stream.message/AbstractResponsiveMessage/death/#/PointingToDeclaration/): [Death](../-death/index.md)?   <br>
| [diedAt](index.md#tech.whence.echo.job.stream.message/AbstractResponsiveMessage/diedAt/#/PointingToDeclaration/)|  [jvm] <br><br>Instant? 失效时间<br><br>open override var [diedAt](index.md#tech.whence.echo.job.stream.message/AbstractResponsiveMessage/diedAt/#/PointingToDeclaration/): [Instant](https://docs.oracle.com/javase/8/docs/api/java/time/Instant.html)?   <br>
| [id](index.md#tech.whence.echo.job.stream.message/AbstractResponsiveMessage/id/#/PointingToDeclaration/)|  [jvm] <br><br>String 编号<br><br>open override val [id](index.md#tech.whence.echo.job.stream.message/AbstractResponsiveMessage/id/#/PointingToDeclaration/): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)   <br>
| [key](index.md#tech.whence.echo.job.stream.message/AbstractResponsiveMessage/key/#/PointingToDeclaration/)|  [jvm] <br><br>String 键<br><br>open override val [key](index.md#tech.whence.echo.job.stream.message/AbstractResponsiveMessage/key/#/PointingToDeclaration/): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)   <br>
| [source](index.md#tech.whence.echo.job.stream.message/AbstractResponsiveMessage/source/#/PointingToDeclaration/)|  [jvm] <br><br>String? 来源<br><br>open override val [source](index.md#tech.whence.echo.job.stream.message/AbstractResponsiveMessage/source/#/PointingToDeclaration/): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?   <br>
| [value](index.md#tech.whence.echo.job.stream.message/AbstractResponsiveMessage/value/#/PointingToDeclaration/)|  [jvm] <br><br>Accessor 值<br><br>open override val [value](index.md#tech.whence.echo.job.stream.message/AbstractResponsiveMessage/value/#/PointingToDeclaration/): [Accessor](../../tech.whence.echo.container.accessor/-accessor/index.md)   <br>


## Inheritors  
  
|  Name| 
|---|
| [SubscribedMessage](../../tech.whence.echo.support.kafka.stream/-subscribed-message/index.md)

