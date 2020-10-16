---
title: Collector -
---
//[echo](../../index.md)/[tech.whence.echo.job.stream.collector](../index.md)/[Collector](index.md)



# Collector  
 [jvm] 

收集者

interface [Collector](index.md)<[T](index.md) : [Message](../../tech.whence.echo.job.stream.message/-message/index.md)> : [Container](../../tech.whence.echo.container/-container/index.md)   


## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| T| <br><br>: Message 消息类型<br><br>
  


## Types  
  
|  Name|  Summary| 
|---|---|
| [State](-state/index.md)| [jvm]  <br>Brief description  <br><br><br>收集者状态<br><br>  <br>Content  <br>enum [State](-state/index.md) : [Enum](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-enum/index.html)<[Collector.State](-state/index.md)>   <br><br><br>


## Functions  
  
|  Name|  Summary| 
|---|---|
| [await](await.md)| [jvm]  <br>Brief description  <br><br><br>等待指定操作可执行<br><br>  <br>Content  <br>abstract fun [await](await.md)(access: [Access](../-access/index.md), waiting: [Duration](https://docs.oracle.com/javase/8/docs/api/java/time/Duration.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [drain](drain.md)| [jvm]  <br>Brief description  <br><br><br>取出剩余所有任务<br><br>  <br>Content  <br>abstract fun [drain](drain.md)(): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[T](index.md)>  <br><br><br>[jvm]  <br>Brief description  <br><br><br>取出任务 若限制小于等于0时返回空 若超过等待时间则停止且返回已收集任务 结果将按创建时间排序<br><br>  <br>Content  <br>open fun [drain](drain.md)(limit: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), waiting: [Duration](https://docs.oracle.com/javase/8/docs/api/java/time/Duration.html)?): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[T](index.md)>  <br><br><br>
| [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)| [jvm]  <br>Content  <br>open operator override fun [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [offer](offer.md)| [jvm]  <br>Brief description  <br><br><br>写入消息<br><br>  <br>Content  <br>abstract fun [offer](offer.md)(message: [T](index.md)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [put](put.md)| [jvm]  <br>Brief description  <br><br><br>写入消息<br><br>  <br>Content  <br>abstract fun [put](put.md)(message: [T](index.md))  <br><br><br>
| [responsively](responsively.md)| [jvm]  <br>Brief description  <br><br><br>提供响应能力<br><br>  <br>Content  <br>abstract fun [responsively](responsively.md)(responder: [Responder](../../tech.whence.echo.job.stream.provider/-responder/index.md))  <br><br><br>
| [signal](signal.md)| [jvm]  <br>Brief description  <br><br><br>等待指定操作执行完毕<br><br>  <br>Content  <br>abstract fun [signal](signal.md)(access: [Access](../-access/index.md))  <br><br><br>
| [take](take.md)| [jvm]  <br>Brief description  <br><br><br>取消息<br><br>  <br>Content  <br>abstract fun [take](take.md)(waiting: [Duration](https://docs.oracle.com/javase/8/docs/api/java/time/Duration.html)?): [T](index.md)?  <br><br><br>
| [to](to.md)| [jvm]  <br>Brief description  <br><br><br>切换到指定阶段<br><br>  <br>Content  <br>abstract fun [to](to.md)(stage: [Stage](../../tech.whence.echo.job.stream.provider/-stage/index.md))  <br><br><br>
| [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>


## Properties  
  
|  Name|  Summary| 
|---|---|
| [empty](index.md#tech.whence.echo.job.stream.collector/Collector/empty/#/PointingToDeclaration/)|  [jvm] <br><br>Boolean 当前容器是否为空<br><br>abstract override val [empty](index.md#tech.whence.echo.job.stream.collector/Collector/empty/#/PointingToDeclaration/): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)   <br>
| [size](index.md#tech.whence.echo.job.stream.collector/Collector/size/#/PointingToDeclaration/)|  [jvm] <br><br>UInt 当前容器总数据量<br><br>abstract override val [size](index.md#tech.whence.echo.job.stream.collector/Collector/size/#/PointingToDeclaration/): [UInt](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-u-int/index.html)   <br>


## Inheritors  
  
|  Name| 
|---|
| [AbstractCollector](../-abstract-collector/index.md)
| [SupplyingCollector](../-supplying-collector/index.md)

