---
title: AbstractCollector -
---
//[echo](../../index.md)/[tech.whence.echo.job.stream.collector](../index.md)/[AbstractCollector](index.md)



# AbstractCollector  
 [jvm] 

抽象收集者

abstract class [AbstractCollector](index.md)<[Q](index.md) : [Queue](https://docs.oracle.com/javase/8/docs/api/java/util/Queue.html)<[T](index.md)>, [T](index.md) : [Message](../../tech.whence.echo.job.stream.message/-message/index.md)>@[JvmOverloads](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-overloads/index.html)()constructor(**queue**: [Q](index.md), **strictly**: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)) : [Collector](../-collector/index.md)<[T](index.md)>    


## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| Q| <br><br>: Queue<T> 数据队列类<br><br>
| T| <br><br>: Message 消息类<br><br>
  


## Constructors  
  
|  Name|  Summary| 
|---|---|
| [AbstractCollector](-abstract-collector.md)|  [jvm] <br><br><br><br>@[JvmOverloads](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-overloads/index.html)()  <br>  <br>fun <[Q](index.md) : [Queue](https://docs.oracle.com/javase/8/docs/api/java/util/Queue.html)<[T](index.md)>> [AbstractCollector](-abstract-collector.md)(queue: [Q](index.md), strictly: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html))   <br>


## Functions  
  
|  Name|  Summary| 
|---|---|
| [await](await.md)| [jvm]  <br>Brief description  <br><br><br>等待指定操作可执行<br><br>  <br>Content  <br>open override fun [await](await.md)(access: [Access](../-access/index.md), waiting: [Duration](https://docs.oracle.com/javase/8/docs/api/java/time/Duration.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [drain](drain.md)| [jvm]  <br>Brief description  <br><br><br>取出剩余所有任务<br><br>  <br>Content  <br>open override fun [drain](drain.md)(): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[T](index.md)>  <br><br><br>[jvm]  <br>Brief description  <br><br><br>取出任务 若限制小于等于0时返回空 若超过等待时间则停止且返回已收集任务 结果将按创建时间排序<br><br>  <br>Content  <br>open override fun [drain](../-collector/drain.md)(limit: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), waiting: [Duration](https://docs.oracle.com/javase/8/docs/api/java/time/Duration.html)?): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[T](index.md)>  <br><br><br>
| [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)| [jvm]  <br>Content  <br>open operator override fun [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [offer](offer.md)| [jvm]  <br>Brief description  <br><br><br>写入消息<br><br>  <br>Content  <br>open override fun [offer](offer.md)(message: [T](index.md)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [put](put.md)| [jvm]  <br>Brief description  <br><br><br>写入消息<br><br>  <br>Content  <br>open override fun [put](put.md)(message: [T](index.md))  <br><br><br>
| [responsively](responsively.md)| [jvm]  <br>Brief description  <br><br><br>提供响应能力<br><br>  <br>Content  <br>open override fun [responsively](responsively.md)(responder: [Responder](../../tech.whence.echo.job.stream.provider/-responder/index.md))  <br><br><br>
| [signal](signal.md)| [jvm]  <br>Brief description  <br><br><br>等待指定操作执行完毕<br><br>  <br>Content  <br>open override fun [signal](signal.md)(access: [Access](../-access/index.md))  <br><br><br>
| [take](take.md)| [jvm]  <br>Brief description  <br><br><br>取消息<br><br>  <br>Content  <br>open override fun [take](take.md)(waiting: [Duration](https://docs.oracle.com/javase/8/docs/api/java/time/Duration.html)?): [T](index.md)?  <br><br><br>
| [to](to.md)| [jvm]  <br>Brief description  <br><br><br>切换到指定阶段<br><br>  <br>Content  <br>open override fun [to](to.md)(stage: [Stage](../../tech.whence.echo.job.stream.provider/-stage/index.md))  <br><br><br>
| [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>


## Properties  
  
|  Name|  Summary| 
|---|---|
| [empty](index.md#tech.whence.echo.job.stream.collector/AbstractCollector/empty/#/PointingToDeclaration/)|  [jvm] <br><br>Boolean 当前容器是否为空<br><br>open override val [empty](index.md#tech.whence.echo.job.stream.collector/AbstractCollector/empty/#/PointingToDeclaration/): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)   <br>
| [size](index.md#tech.whence.echo.job.stream.collector/AbstractCollector/size/#/PointingToDeclaration/)|  [jvm] <br><br>UInt 当前容器总数据量<br><br>open override val [size](index.md#tech.whence.echo.job.stream.collector/AbstractCollector/size/#/PointingToDeclaration/): [UInt](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-u-int/index.html)   <br>


## Inheritors  
  
|  Name| 
|---|
| [AbstractBlockingCollector](../-abstract-blocking-collector/index.md)
| [PlainCollector](../-plain-collector/index.md)

