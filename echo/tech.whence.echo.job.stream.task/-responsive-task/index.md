---
title: ResponsiveTask -
---
//[echo](../../index.md)/[tech.whence.echo.job.stream.task](../index.md)/[ResponsiveTask](index.md)



# ResponsiveTask  
 [jvm] 

响应式任务

class [ResponsiveTask](index.md)<[T](index.md) : [Task](../-task/index.md)>(**proxy**: [T](index.md), **marker**: ([T](index.md), [Measurer.Action](../../tech.whence.echo.job.stream.work/-measurer/-action/index.md)) -> [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)) : [AbstractTask](../-abstract-task/index.md)<[T](index.md)>    


## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| T| <br><br>: Task 任务类型<br><br>
  


## Constructors  
  
|  Name|  Summary| 
|---|---|
| [ResponsiveTask](-responsive-task.md)|  [jvm] <br><br><br><br>fun <[T](index.md) : [Task](../-task/index.md)> [ResponsiveTask](-responsive-task.md)(proxy: [T](index.md), marker: ([T](index.md), [Measurer.Action](../../tech.whence.echo.job.stream.work/-measurer/-action/index.md)) -> [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html))   <br>


## Functions  
  
|  Name|  Summary| 
|---|---|
| [die](../-abstract-task/die.md)| [jvm]  <br>Brief description  <br><br><br>失效<br><br>  <br>Content  <br>open override fun [die](../-abstract-task/die.md)(death: [Death](../../tech.whence.echo.job.stream.message/-death/index.md))  <br><br><br>
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
| [createdAt](index.md#tech.whence.echo.job.stream.task/ResponsiveTask/createdAt/#/PointingToDeclaration/)|  [jvm] open override val [createdAt](index.md#tech.whence.echo.job.stream.task/ResponsiveTask/createdAt/#/PointingToDeclaration/): [Instant](https://docs.oracle.com/javase/8/docs/api/java/time/Instant.html)   <br>
| [data](index.md#tech.whence.echo.job.stream.task/ResponsiveTask/data/#/PointingToDeclaration/)|  [jvm] open override val [data](index.md#tech.whence.echo.job.stream.task/ResponsiveTask/data/#/PointingToDeclaration/): [Map](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)<[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?>   <br>
| [dead](index.md#tech.whence.echo.job.stream.task/ResponsiveTask/dead/#/PointingToDeclaration/)|  [jvm] open override val [dead](index.md#tech.whence.echo.job.stream.task/ResponsiveTask/dead/#/PointingToDeclaration/): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)   <br>
| [death](index.md#tech.whence.echo.job.stream.task/ResponsiveTask/death/#/PointingToDeclaration/)|  [jvm] open override var [death](index.md#tech.whence.echo.job.stream.task/ResponsiveTask/death/#/PointingToDeclaration/): [Death](../../tech.whence.echo.job.stream.message/-death/index.md)?   <br>
| [diedAt](index.md#tech.whence.echo.job.stream.task/ResponsiveTask/diedAt/#/PointingToDeclaration/)|  [jvm] open override var [diedAt](index.md#tech.whence.echo.job.stream.task/ResponsiveTask/diedAt/#/PointingToDeclaration/): [Instant](https://docs.oracle.com/javase/8/docs/api/java/time/Instant.html)?   <br>
| [id](index.md#tech.whence.echo.job.stream.task/ResponsiveTask/id/#/PointingToDeclaration/)|  [jvm] open override val [id](index.md#tech.whence.echo.job.stream.task/ResponsiveTask/id/#/PointingToDeclaration/): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)   <br>
| [key](index.md#tech.whence.echo.job.stream.task/ResponsiveTask/key/#/PointingToDeclaration/)|  [jvm] open override val [key](index.md#tech.whence.echo.job.stream.task/ResponsiveTask/key/#/PointingToDeclaration/): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)   <br>
| [provider](index.md#tech.whence.echo.job.stream.task/ResponsiveTask/provider/#/PointingToDeclaration/)|  [jvm] <br><br>Provider? 消息提供者<br><br>open override val [provider](index.md#tech.whence.echo.job.stream.task/ResponsiveTask/provider/#/PointingToDeclaration/): [Provider](../../tech.whence.echo.job.stream.provider/-provider/index.md)?   <br>
| [proxy](index.md#tech.whence.echo.job.stream.task/ResponsiveTask/proxy/#/PointingToDeclaration/)|  [jvm] <br><br>T 任务代理<br><br>val [proxy](index.md#tech.whence.echo.job.stream.task/ResponsiveTask/proxy/#/PointingToDeclaration/): [T](index.md)   <br>
| [source](index.md#tech.whence.echo.job.stream.task/ResponsiveTask/source/#/PointingToDeclaration/)|  [jvm] open override val [source](index.md#tech.whence.echo.job.stream.task/ResponsiveTask/source/#/PointingToDeclaration/): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?   <br>
| [value](index.md#tech.whence.echo.job.stream.task/ResponsiveTask/value/#/PointingToDeclaration/)|  [jvm] open override val [value](index.md#tech.whence.echo.job.stream.task/ResponsiveTask/value/#/PointingToDeclaration/): [Accessor](../../tech.whence.echo.container.accessor/-accessor/index.md)   <br>
| [workload](index.md#tech.whence.echo.job.stream.task/ResponsiveTask/workload/#/PointingToDeclaration/)|  [jvm] <br><br>Traceable? 可跟踪数据<br><br>open override val [workload](index.md#tech.whence.echo.job.stream.task/ResponsiveTask/workload/#/PointingToDeclaration/): [Traceable](../../tech.whence.echo.job/-traceable/index.md)?   <br>
| [workloads](index.md#tech.whence.echo.job.stream.task/ResponsiveTask/workloads/#/PointingToDeclaration/)|  [jvm] <br><br>LinkedList<Traceable> 工作负载<br><br>override var [workloads](index.md#tech.whence.echo.job.stream.task/ResponsiveTask/workloads/#/PointingToDeclaration/): [LinkedList](https://docs.oracle.com/javase/8/docs/api/java/util/LinkedList.html)<[Traceable](../../tech.whence.echo.job/-traceable/index.md)>   <br>

