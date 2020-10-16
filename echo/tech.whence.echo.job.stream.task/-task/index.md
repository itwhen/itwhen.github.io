---
title: Task -
---
//[echo](../../index.md)/[tech.whence.echo.job.stream.task](../index.md)/[Task](index.md)



# Task  
 [jvm] 

任务

interface [Task](index.md) : [Message](../../tech.whence.echo.job.stream.message/-message/index.md)   


## Functions  
  
|  Name|  Summary| 
|---|---|
| [die](../../tech.whence.echo.job.stream.message/-message/die.md)| [jvm]  <br>Brief description  <br><br><br>失效<br><br>  <br>Content  <br>abstract override fun [die](../../tech.whence.echo.job.stream.message/-message/die.md)(death: [Death](../../tech.whence.echo.job.stream.message/-death/index.md))  <br><br><br>
| [dump](dump.md)| [jvm]  <br>Brief description  <br><br><br>丢弃<br><br>  <br>Content  <br>abstract fun [dump](dump.md)()  <br><br><br>
| [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)| [jvm]  <br>Content  <br>open operator override fun [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [fail](fail.md)| [jvm]  <br>Brief description  <br><br><br>置为失败<br><br>  <br>Content  <br>abstract fun [fail](fail.md)()  <br><br><br>
| [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [ignore](ignore.md)| [jvm]  <br>Brief description  <br><br><br>忽略<br><br>  <br>Content  <br>abstract fun [ignore](ignore.md)()  <br><br><br>
| [reload](reload.md)| [jvm]  <br>Brief description  <br><br><br>重载数据<br><br>  <br>Content  <br>abstract fun [reload](reload.md)(workload: [Traceable](../../tech.whence.echo.job/-traceable/index.md))  <br><br><br>
| [retry](retry.md)| [jvm]  <br>Brief description  <br><br><br>重试<br><br>  <br>Content  <br>abstract fun [retry](retry.md)(retry: [Retry](../../tech.whence.echo.retry/-retry/index.md)?)  <br><br><br>
| [succeed](succeed.md)| [jvm]  <br>Brief description  <br><br><br>置为成功<br><br>  <br>Content  <br>abstract fun [succeed](succeed.md)()  <br><br><br>
| [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>


## Properties  
  
|  Name|  Summary| 
|---|---|
| [createdAt](index.md#tech.whence.echo.job.stream.task/Task/createdAt/#/PointingToDeclaration/)|  [jvm] <br><br>Instant 创建时间<br><br>abstract override val [createdAt](index.md#tech.whence.echo.job.stream.task/Task/createdAt/#/PointingToDeclaration/): [Instant](https://docs.oracle.com/javase/8/docs/api/java/time/Instant.html)   <br>
| [data](index.md#tech.whence.echo.job.stream.task/Task/data/#/PointingToDeclaration/)|  [jvm] <br><br>Map<String, Any?> 数据<br><br>abstract override val [data](index.md#tech.whence.echo.job.stream.task/Task/data/#/PointingToDeclaration/): [Map](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)<[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?>   <br>
| [dead](index.md#tech.whence.echo.job.stream.task/Task/dead/#/PointingToDeclaration/)|  [jvm] <br><br>Boolean 是否失效<br><br>open override val [dead](index.md#tech.whence.echo.job.stream.task/Task/dead/#/PointingToDeclaration/): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)   <br>
| [death](index.md#tech.whence.echo.job.stream.task/Task/death/#/PointingToDeclaration/)|  [jvm] <br><br>Death? 失效方式<br><br>abstract override val [death](index.md#tech.whence.echo.job.stream.task/Task/death/#/PointingToDeclaration/): [Death](../../tech.whence.echo.job.stream.message/-death/index.md)?   <br>
| [diedAt](index.md#tech.whence.echo.job.stream.task/Task/diedAt/#/PointingToDeclaration/)|  [jvm] <br><br>Instant? 失效时间<br><br>abstract override val [diedAt](index.md#tech.whence.echo.job.stream.task/Task/diedAt/#/PointingToDeclaration/): [Instant](https://docs.oracle.com/javase/8/docs/api/java/time/Instant.html)?   <br>
| [id](index.md#tech.whence.echo.job.stream.task/Task/id/#/PointingToDeclaration/)|  [jvm] <br><br>String 编号<br><br>abstract override val [id](index.md#tech.whence.echo.job.stream.task/Task/id/#/PointingToDeclaration/): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)   <br>
| [key](index.md#tech.whence.echo.job.stream.task/Task/key/#/PointingToDeclaration/)|  [jvm] <br><br>String 键<br><br>abstract override val [key](index.md#tech.whence.echo.job.stream.task/Task/key/#/PointingToDeclaration/): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)   <br>
| [provider](index.md#tech.whence.echo.job.stream.task/Task/provider/#/PointingToDeclaration/)|  [jvm] <br><br>Provider? 数据提供者<br><br>abstract val [provider](index.md#tech.whence.echo.job.stream.task/Task/provider/#/PointingToDeclaration/): [Provider](../../tech.whence.echo.job.stream.provider/-provider/index.md)?   <br>
| [source](index.md#tech.whence.echo.job.stream.task/Task/source/#/PointingToDeclaration/)|  [jvm] <br><br>String? 来源<br><br>abstract override val [source](index.md#tech.whence.echo.job.stream.task/Task/source/#/PointingToDeclaration/): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?   <br>
| [value](index.md#tech.whence.echo.job.stream.task/Task/value/#/PointingToDeclaration/)|  [jvm] <br><br>Accessor 值<br><br>abstract override val [value](index.md#tech.whence.echo.job.stream.task/Task/value/#/PointingToDeclaration/): [Accessor](../../tech.whence.echo.container.accessor/-accessor/index.md)   <br>
| [workload](index.md#tech.whence.echo.job.stream.task/Task/workload/#/PointingToDeclaration/)|  [jvm] <br><br>Traceable? 可跟踪数据<br><br>abstract val [workload](index.md#tech.whence.echo.job.stream.task/Task/workload/#/PointingToDeclaration/): [Traceable](../../tech.whence.echo.job/-traceable/index.md)?   <br>


## Inheritors  
  
|  Name| 
|---|
| [AbstractTask](../-abstract-task/index.md)

