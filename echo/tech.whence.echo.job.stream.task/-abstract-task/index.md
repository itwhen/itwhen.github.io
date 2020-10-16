---
title: AbstractTask -
---
//[echo](../../index.md)/[tech.whence.echo.job.stream.task](../index.md)/[AbstractTask](index.md)



# AbstractTask  
 [jvm] 

抽象任务

abstract class [AbstractTask](index.md)<[T](index.md) : [Message](../../tech.whence.echo.job.stream.message/-message/index.md)>(**id**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), **key**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), **value**: [Accessor](../../tech.whence.echo.container.accessor/-accessor/index.md), **source**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, **createdAt**: [Instant](https://docs.oracle.com/javase/8/docs/api/java/time/Instant.html)) : [AbstractMessage](../../tech.whence.echo.job.stream.message/-abstract-message/index.md), [Task](../-task/index.md)   


## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| T| <br><br>: Message 消息类型<br><br>
  


## Constructors  
  
|  Name|  Summary| 
|---|---|
| [AbstractTask](-abstract-task.md)|  [jvm] fun <[T](index.md) : [Message](../../tech.whence.echo.job.stream.message/-message/index.md)> [AbstractTask](-abstract-task.md)(message: [T](index.md))   <br>
| [AbstractTask](-abstract-task.md)|  [jvm] <br><br><br><br>fun [AbstractTask](-abstract-task.md)(id: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), key: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), value: [Accessor](../../tech.whence.echo.container.accessor/-accessor/index.md), source: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, createdAt: [Instant](https://docs.oracle.com/javase/8/docs/api/java/time/Instant.html))   <br>


## Functions  
  
|  Name|  Summary| 
|---|---|
| [die](die.md)| [jvm]  <br>Brief description  <br><br><br>失效<br><br>  <br>Content  <br>open override fun [die](die.md)(death: [Death](../../tech.whence.echo.job.stream.message/-death/index.md))  <br><br><br>
| [dump](dump.md)| [jvm]  <br>Brief description  <br><br><br>丢弃<br><br>  <br>Content  <br>open override fun [dump](dump.md)()  <br><br><br>
| [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)| [jvm]  <br>Content  <br>open operator override fun [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [fail](fail.md)| [jvm]  <br>Brief description  <br><br><br>置为失败<br><br>  <br>Content  <br>open override fun [fail](fail.md)()  <br><br><br>
| [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [ignore](ignore.md)| [jvm]  <br>Brief description  <br><br><br>忽略<br><br>  <br>Content  <br>open override fun [ignore](ignore.md)()  <br><br><br>
| [reload](reload.md)| [jvm]  <br>Brief description  <br><br><br>重载数据<br><br>  <br>Content  <br>open override fun [reload](reload.md)(workload: [Traceable](../../tech.whence.echo.job/-traceable/index.md))  <br><br><br>
| [retry](retry.md)| [jvm]  <br>Brief description  <br><br><br>重试<br><br>  <br>Content  <br>open override fun [retry](retry.md)(retry: [Retry](../../tech.whence.echo.retry/-retry/index.md)?)  <br><br><br>
| [succeed](succeed.md)| [jvm]  <br>Brief description  <br><br><br>置为成功<br><br>  <br>Content  <br>open override fun [succeed](succeed.md)()  <br><br><br>
| [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>


## Properties  
  
|  Name|  Summary| 
|---|---|
| [createdAt](index.md#tech.whence.echo.job.stream.task/AbstractTask/createdAt/#/PointingToDeclaration/)|  [jvm] open override val [createdAt](index.md#tech.whence.echo.job.stream.task/AbstractTask/createdAt/#/PointingToDeclaration/): [Instant](https://docs.oracle.com/javase/8/docs/api/java/time/Instant.html)   <br>
| [data](index.md#tech.whence.echo.job.stream.task/AbstractTask/data/#/PointingToDeclaration/)|  [jvm] open override val [data](index.md#tech.whence.echo.job.stream.task/AbstractTask/data/#/PointingToDeclaration/): [Map](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)<[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?>   <br>
| [dead](index.md#tech.whence.echo.job.stream.task/AbstractTask/dead/#/PointingToDeclaration/)|  [jvm] open override val [dead](index.md#tech.whence.echo.job.stream.task/AbstractTask/dead/#/PointingToDeclaration/): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)   <br>
| [death](index.md#tech.whence.echo.job.stream.task/AbstractTask/death/#/PointingToDeclaration/)|  [jvm] open override var [death](index.md#tech.whence.echo.job.stream.task/AbstractTask/death/#/PointingToDeclaration/): [Death](../../tech.whence.echo.job.stream.message/-death/index.md)?   <br>
| [diedAt](index.md#tech.whence.echo.job.stream.task/AbstractTask/diedAt/#/PointingToDeclaration/)|  [jvm] open override var [diedAt](index.md#tech.whence.echo.job.stream.task/AbstractTask/diedAt/#/PointingToDeclaration/): [Instant](https://docs.oracle.com/javase/8/docs/api/java/time/Instant.html)?   <br>
| [id](index.md#tech.whence.echo.job.stream.task/AbstractTask/id/#/PointingToDeclaration/)|  [jvm] open override val [id](index.md#tech.whence.echo.job.stream.task/AbstractTask/id/#/PointingToDeclaration/): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)   <br>
| [key](index.md#tech.whence.echo.job.stream.task/AbstractTask/key/#/PointingToDeclaration/)|  [jvm] open override val [key](index.md#tech.whence.echo.job.stream.task/AbstractTask/key/#/PointingToDeclaration/): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)   <br>
| [provider](index.md#tech.whence.echo.job.stream.task/AbstractTask/provider/#/PointingToDeclaration/)|  [jvm] <br><br>Provider? 数据提供者<br><br>abstract override val [provider](index.md#tech.whence.echo.job.stream.task/AbstractTask/provider/#/PointingToDeclaration/): [Provider](../../tech.whence.echo.job.stream.provider/-provider/index.md)?   <br>
| [source](index.md#tech.whence.echo.job.stream.task/AbstractTask/source/#/PointingToDeclaration/)|  [jvm] open override val [source](index.md#tech.whence.echo.job.stream.task/AbstractTask/source/#/PointingToDeclaration/): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?   <br>
| [value](index.md#tech.whence.echo.job.stream.task/AbstractTask/value/#/PointingToDeclaration/)|  [jvm] open override val [value](index.md#tech.whence.echo.job.stream.task/AbstractTask/value/#/PointingToDeclaration/): [Accessor](../../tech.whence.echo.container.accessor/-accessor/index.md)   <br>
| [workload](index.md#tech.whence.echo.job.stream.task/AbstractTask/workload/#/PointingToDeclaration/)|  [jvm] <br><br>Traceable? 当前负载<br><br>open override val [workload](index.md#tech.whence.echo.job.stream.task/AbstractTask/workload/#/PointingToDeclaration/): [Traceable](../../tech.whence.echo.job/-traceable/index.md)?   <br>


## Inheritors  
  
|  Name| 
|---|
| [MessagingProvider](../../tech.whence.echo.job.stream.provider/-messaging-provider/-inner-task/index.md)
| [RetryingProvider](../../tech.whence.echo.job.stream.provider/-retrying-provider/-inner-task/index.md)
| [SupplyingProvider](../../tech.whence.echo.job.stream.provider/-supplying-provider/-inner-task/index.md)
| [ResponsiveTask](../-responsive-task/index.md)

