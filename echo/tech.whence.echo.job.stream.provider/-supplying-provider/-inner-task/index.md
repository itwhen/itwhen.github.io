---
title: InnerTask -
---
//[echo](../../../index.md)/[tech.whence.echo.job.stream.provider](../../index.md)/[SupplyingProvider](../index.md)/[InnerTask](index.md)



# InnerTask  
 [jvm] 

内置任务

inner class [InnerTask](index.md)(**message**: [Message](../../../tech.whence.echo.job.stream.message/-message/index.md)) : [AbstractTask](../../../tech.whence.echo.job.stream.task/-abstract-task/index.md)<[Message](../../../tech.whence.echo.job.stream.message/-message/index.md)>    


## Constructors  
  
|  Name|  Summary| 
|---|---|
| [InnerTask](-inner-task.md)|  [jvm] <br><br><br><br>fun [InnerTask](-inner-task.md)(message: [Message](../../../tech.whence.echo.job.stream.message/-message/index.md))   <br>


## Functions  
  
|  Name|  Summary| 
|---|---|
| [die](../../../tech.whence.echo.job.stream.task/-abstract-task/die.md)| [jvm]  <br>Brief description  <br><br><br>失效<br><br>  <br>Content  <br>open override fun [die](../../../tech.whence.echo.job.stream.task/-abstract-task/die.md)(death: [Death](../../../tech.whence.echo.job.stream.message/-death/index.md))  <br><br><br>
| [dump](dump.md)| [jvm]  <br>Brief description  <br><br><br>丢弃<br><br>  <br>Content  <br>open override fun [dump](dump.md)()  <br><br><br>
| [equals](../../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)| [jvm]  <br>Content  <br>open operator override fun [equals](../../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [fail](../../../tech.whence.echo.job.stream.task/-abstract-task/fail.md)| [jvm]  <br>Brief description  <br><br><br>置为失败<br><br>  <br>Content  <br>open override fun [fail](../../../tech.whence.echo.job.stream.task/-abstract-task/fail.md)()  <br><br><br>
| [hashCode](../../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [hashCode](../../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [ignore](../../../tech.whence.echo.job.stream.task/-abstract-task/ignore.md)| [jvm]  <br>Brief description  <br><br><br>忽略<br><br>  <br>Content  <br>open override fun [ignore](../../../tech.whence.echo.job.stream.task/-abstract-task/ignore.md)()  <br><br><br>
| [reload](../../../tech.whence.echo.job.stream.task/-abstract-task/reload.md)| [jvm]  <br>Brief description  <br><br><br>重载数据<br><br>  <br>Content  <br>open override fun [reload](../../../tech.whence.echo.job.stream.task/-abstract-task/reload.md)(workload: [Traceable](../../../tech.whence.echo.job/-traceable/index.md))  <br><br><br>
| [retry](../../../tech.whence.echo.job.stream.task/-abstract-task/retry.md)| [jvm]  <br>Brief description  <br><br><br>重试<br><br>  <br>Content  <br>open override fun [retry](../../../tech.whence.echo.job.stream.task/-abstract-task/retry.md)(retry: [Retry](../../../tech.whence.echo.retry/-retry/index.md)?)  <br><br><br>
| [succeed](../../../tech.whence.echo.job.stream.task/-abstract-task/succeed.md)| [jvm]  <br>Brief description  <br><br><br>置为成功<br><br>  <br>Content  <br>open override fun [succeed](../../../tech.whence.echo.job.stream.task/-abstract-task/succeed.md)()  <br><br><br>
| [toString](../../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [toString](../../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>


## Properties  
  
|  Name|  Summary| 
|---|---|
| [createdAt](index.md#tech.whence.echo.job.stream.provider/SupplyingProvider.InnerTask/createdAt/#/PointingToDeclaration/)|  [jvm] open override val [createdAt](index.md#tech.whence.echo.job.stream.provider/SupplyingProvider.InnerTask/createdAt/#/PointingToDeclaration/): [Instant](https://docs.oracle.com/javase/8/docs/api/java/time/Instant.html)   <br>
| [data](index.md#tech.whence.echo.job.stream.provider/SupplyingProvider.InnerTask/data/#/PointingToDeclaration/)|  [jvm] open override val [data](index.md#tech.whence.echo.job.stream.provider/SupplyingProvider.InnerTask/data/#/PointingToDeclaration/): [Map](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)<[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?>   <br>
| [dead](index.md#tech.whence.echo.job.stream.provider/SupplyingProvider.InnerTask/dead/#/PointingToDeclaration/)|  [jvm] open override val [dead](index.md#tech.whence.echo.job.stream.provider/SupplyingProvider.InnerTask/dead/#/PointingToDeclaration/): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)   <br>
| [death](index.md#tech.whence.echo.job.stream.provider/SupplyingProvider.InnerTask/death/#/PointingToDeclaration/)|  [jvm] open override var [death](index.md#tech.whence.echo.job.stream.provider/SupplyingProvider.InnerTask/death/#/PointingToDeclaration/): [Death](../../../tech.whence.echo.job.stream.message/-death/index.md)?   <br>
| [diedAt](index.md#tech.whence.echo.job.stream.provider/SupplyingProvider.InnerTask/diedAt/#/PointingToDeclaration/)|  [jvm] open override var [diedAt](index.md#tech.whence.echo.job.stream.provider/SupplyingProvider.InnerTask/diedAt/#/PointingToDeclaration/): [Instant](https://docs.oracle.com/javase/8/docs/api/java/time/Instant.html)?   <br>
| [id](index.md#tech.whence.echo.job.stream.provider/SupplyingProvider.InnerTask/id/#/PointingToDeclaration/)|  [jvm] open override val [id](index.md#tech.whence.echo.job.stream.provider/SupplyingProvider.InnerTask/id/#/PointingToDeclaration/): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)   <br>
| [key](index.md#tech.whence.echo.job.stream.provider/SupplyingProvider.InnerTask/key/#/PointingToDeclaration/)|  [jvm] open override val [key](index.md#tech.whence.echo.job.stream.provider/SupplyingProvider.InnerTask/key/#/PointingToDeclaration/): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)   <br>
| [provider](index.md#tech.whence.echo.job.stream.provider/SupplyingProvider.InnerTask/provider/#/PointingToDeclaration/)|  [jvm] <br><br>Provider 提供者<br><br>open override val [provider](index.md#tech.whence.echo.job.stream.provider/SupplyingProvider.InnerTask/provider/#/PointingToDeclaration/): [Provider](../../-provider/index.md)   <br>
| [source](index.md#tech.whence.echo.job.stream.provider/SupplyingProvider.InnerTask/source/#/PointingToDeclaration/)|  [jvm] open override val [source](index.md#tech.whence.echo.job.stream.provider/SupplyingProvider.InnerTask/source/#/PointingToDeclaration/): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?   <br>
| [value](index.md#tech.whence.echo.job.stream.provider/SupplyingProvider.InnerTask/value/#/PointingToDeclaration/)|  [jvm] open override val [value](index.md#tech.whence.echo.job.stream.provider/SupplyingProvider.InnerTask/value/#/PointingToDeclaration/): [Accessor](../../../tech.whence.echo.container.accessor/-accessor/index.md)   <br>
| [workload](index.md#tech.whence.echo.job.stream.provider/SupplyingProvider.InnerTask/workload/#/PointingToDeclaration/)|  [jvm] <br><br>Traceable? 当前负载<br><br>open override val [workload](index.md#tech.whence.echo.job.stream.provider/SupplyingProvider.InnerTask/workload/#/PointingToDeclaration/): [Traceable](../../../tech.whence.echo.job/-traceable/index.md)?   <br>
| [workloads](index.md#tech.whence.echo.job.stream.provider/SupplyingProvider.InnerTask/workloads/#/PointingToDeclaration/)|  [jvm] <br><br>LinkedList<Traceable> 工作负载<br><br>override var [workloads](index.md#tech.whence.echo.job.stream.provider/SupplyingProvider.InnerTask/workloads/#/PointingToDeclaration/): [LinkedList](https://docs.oracle.com/javase/8/docs/api/java/util/LinkedList.html)<[Traceable](../../../tech.whence.echo.job/-traceable/index.md)>   <br>

