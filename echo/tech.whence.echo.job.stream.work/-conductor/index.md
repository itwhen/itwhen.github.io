---
title: Conductor -
---
//[echo](../../index.md)/[tech.whence.echo.job.stream.work](../index.md)/[Conductor](index.md)



# Conductor  
 [jvm] 

编排器

class [Conductor](index.md)(**providable**: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), **originatedAt**: [Instant](https://docs.oracle.com/javase/8/docs/api/java/time/Instant.html)?, **cycle**: [Duration](https://docs.oracle.com/javase/8/docs/api/java/time/Duration.html))   


## Constructors  
  
|  Name|  Summary| 
|---|---|
| [Conductor](-conductor.md)|  [jvm] <br><br><br><br>fun [Conductor](-conductor.md)(providable: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), originatedAt: [Instant](https://docs.oracle.com/javase/8/docs/api/java/time/Instant.html)?, cycle: [Duration](https://docs.oracle.com/javase/8/docs/api/java/time/Duration.html))   <br>


## Types  
  
|  Name|  Summary| 
|---|---|
| [Companion](-companion/index.md)| [jvm]  <br>Content  <br>object [Companion](-companion/index.md)  <br><br><br>


## Functions  
  
|  Name|  Summary| 
|---|---|
| [await](await.md)| [jvm]  <br>Brief description  <br><br><br>等待任务提供者预备完成<br><br>  <br>Content  <br>fun [await](await.md)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [clean](clean.md)| [jvm]  <br>Brief description  <br><br><br>清理 停止收集器 取出剩余所有任务<br><br>  <br>Content  <br>fun [clean](clean.md)(): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[Task](../../tech.whence.echo.job.stream.task/-task/index.md)>  <br><br><br>
| [collect](collect.md)| [jvm]  <br>Brief description  <br><br><br>收集任务<br><br>  <br>Content  <br>fun [collect](collect.md)(task: [Task](../../tech.whence.echo.job.stream.task/-task/index.md)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [degradeBy](degrade-by.md)| [jvm]  <br>Brief description  <br><br><br>设置降级器<br><br>  <br>Content  <br>fun [degradeBy](degrade-by.md)(degrader: [Degrader](../../tech.whence.echo.job.stream.degrader/-degrader/index.md)): [Conductor](index.md)  <br><br><br>
| [dump](dump.md)| [jvm]  <br>Brief description  <br><br><br>丢弃任务<br><br>  <br>Content  <br>fun [dump](dump.md)(task: [Task](../../tech.whence.echo.job.stream.task/-task/index.md))  <br><br><br>
| [dumping](dumping.md)| [jvm]  <br>Brief description  <br><br><br>取出被抛弃任务<br><br>  <br>Content  <br>fun [dumping](dumping.md)(count: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[Task](../../tech.whence.echo.job.stream.task/-task/index.md)>  <br><br><br>
| [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)| [jvm]  <br>Content  <br>open operator override fun [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [expired](expired.md)| [jvm]  <br>Brief description  <br><br><br>判断消息是否过期<br><br>  <br>Content  <br>fun [expired](expired.md)(message: [Message](../../tech.whence.echo.job.stream.message/-message/index.md)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [idle](idle.md)| [jvm]  <br>Brief description  <br><br><br>取空闲时间 若重试未设置则为空 若正常状态下重置重试返回空 否则取重试设置的下一个等待周期<br><br>  <br>Content  <br>fun [idle](idle.md)(provided: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), idled: [Retrying](../../tech.whence.echo.retry/-retrying/index.md)?): [Duration](https://docs.oracle.com/javase/8/docs/api/java/time/Duration.html)?  <br><br><br>
| [idleBy](idle-by.md)| [jvm]  <br>Brief description  <br><br><br>设置等待设置<br><br>  <br>Content  <br>fun [idleBy](idle-by.md)(idler: [Retry](../../tech.whence.echo.retry/-retry/index.md)?): [Conductor](index.md)  <br><br><br>
| [inspect](inspect.md)| [jvm]  <br>Brief description  <br><br><br>检查当前状态<br><br>  <br>Content  <br>fun [inspect](inspect.md)(scheduler: [Scheduler](../-scheduler/index.md))  <br><br><br>
| [measureBy](measure-by.md)| [jvm]  <br>Brief description  <br><br><br>设置测量器<br><br>  <br>Content  <br>fun [measureBy](measure-by.md)(measurer: [Measurer](../-measurer/index.md)): [Conductor](index.md)  <br><br><br>
| [providable](providable.md)| [jvm]  <br>Brief description  <br><br><br>是否可供给<br><br>  <br>Content  <br>fun [providable](providable.md)(provided: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [provideBy](provide-by.md)| [jvm]  <br>Brief description  <br><br><br>设置任务提供者<br><br>  <br>Content  <br>fun [provideBy](provide-by.md)(provider: [Provider](../../tech.whence.echo.job.stream.provider/-provider/index.md)): [Conductor](index.md)  <br><br><br>
| [ready](ready.md)| [jvm]  <br>Brief description  <br><br><br>预备<br><br>  <br>Content  <br>fun [ready](ready.md)()  <br><br><br>[jvm]  <br>Brief description  <br><br><br>预备任务提供者<br><br>  <br>Content  <br>fun [ready](ready.md)(provider: [Provider](../../tech.whence.echo.job.stream.provider/-provider/index.md))  <br><br><br>
| [recollect](recollect.md)| [jvm]  <br>Brief description  <br><br><br>重新收集任务<br><br>  <br>Content  <br>fun [recollect](recollect.md)(task: [Task](../../tech.whence.echo.job.stream.task/-task/index.md), retry: [Retry](../../tech.whence.echo.retry/-retry/index.md)?)  <br><br><br>
| [respond](respond.md)| [jvm]  <br>Brief description  <br><br><br>响应所有提供者<br><br>  <br>Content  <br>fun [respond](respond.md)()  <br><br><br>
| [retryBy](retry-by.md)| [jvm]  <br>Brief description  <br><br><br>设置重试任务提供者<br><br>  <br>Content  <br>fun [retryBy](retry-by.md)(provider: [RetryingProvider](../../tech.whence.echo.job.stream.provider/-retrying-provider/index.md)?): [Conductor](index.md)  <br><br><br>
| [storeBy](store-by.md)| [jvm]  <br>Brief description  <br><br><br>设置任务存储器<br><br>  <br>Content  <br>fun [storeBy](store-by.md)(collector: [Collector](../../tech.whence.echo.job.stream.collector/-collector/index.md)<[Task](../../tech.whence.echo.job.stream.task/-task/index.md)>, dumper: [Collector](../../tech.whence.echo.job.stream.collector/-collector/index.md)<[Task](../../tech.whence.echo.job.stream.task/-task/index.md)>, collectable: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [Conductor](index.md)  <br><br><br>
| [take](take.md)| [jvm]  <br>Brief description  <br><br><br>取出所有任务<br><br>  <br>Content  <br>fun [take](take.md)(): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[Task](../../tech.whence.echo.job.stream.task/-task/index.md)>  <br><br><br>[jvm]  <br>Brief description  <br><br><br>取出任务<br><br>  <br>Content  <br>fun [take](take.md)(count: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), cycle: [Duration](https://docs.oracle.com/javase/8/docs/api/java/time/Duration.html)?): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[Task](../../tech.whence.echo.job.stream.task/-task/index.md)>  <br><br><br>
| [timing](timing.md)| [jvm]  <br>Brief description  <br><br><br>取执行时机 当前时间+循环周期<br><br>  <br>Content  <br>fun [timing](timing.md)(): [Instant](https://docs.oracle.com/javase/8/docs/api/java/time/Instant.html)  <br><br><br>
| [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>


## Properties  
  
|  Name|  Summary| 
|---|---|
| [collectable](index.md#tech.whence.echo.job.stream.work/Conductor/collectable/#/PointingToDeclaration/)|  [jvm] <br><br>Int 可收集量<br><br>var [collectable](index.md#tech.whence.echo.job.stream.work/Conductor/collectable/#/PointingToDeclaration/): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)   <br>
| [cycle](index.md#tech.whence.echo.job.stream.work/Conductor/cycle/#/PointingToDeclaration/)|  [jvm] <br><br>Duration 循环周期<br><br>val [cycle](index.md#tech.whence.echo.job.stream.work/Conductor/cycle/#/PointingToDeclaration/): [Duration](https://docs.oracle.com/javase/8/docs/api/java/time/Duration.html)   <br>
| [degradation](index.md#tech.whence.echo.job.stream.work/Conductor/degradation/#/PointingToDeclaration/)|  [jvm] <br><br>Degrader? 降级器<br><br>var [degradation](index.md#tech.whence.echo.job.stream.work/Conductor/degradation/#/PointingToDeclaration/): [Degrader](../../tech.whence.echo.job.stream.degrader/-degrader/index.md)?   <br>
| [degrading](index.md#tech.whence.echo.job.stream.work/Conductor/degrading/#/PointingToDeclaration/)|  [jvm] <br><br>Boolean 是否在降级中<br><br>val [degrading](index.md#tech.whence.echo.job.stream.work/Conductor/degrading/#/PointingToDeclaration/): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)   <br>
| [originatedAt](index.md#tech.whence.echo.job.stream.work/Conductor/originatedAt/#/PointingToDeclaration/)|  [jvm] <br><br>Instant? 任务数据开始时间<br><br>val [originatedAt](index.md#tech.whence.echo.job.stream.work/Conductor/originatedAt/#/PointingToDeclaration/): [Instant](https://docs.oracle.com/javase/8/docs/api/java/time/Instant.html)?   <br>
| [providable](index.md#tech.whence.echo.job.stream.work/Conductor/providable/#/PointingToDeclaration/)|  [jvm] <br><br>Int 可提供量<br><br>val [providable](index.md#tech.whence.echo.job.stream.work/Conductor/providable/#/PointingToDeclaration/): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)   <br>
| [redoable](index.md#tech.whence.echo.job.stream.work/Conductor/redoable/#/PointingToDeclaration/)|  [jvm] <br><br>Boolean 是否可重做<br><br>val [redoable](index.md#tech.whence.echo.job.stream.work/Conductor/redoable/#/PointingToDeclaration/): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)   <br>
| [upgrading](index.md#tech.whence.echo.job.stream.work/Conductor/upgrading/#/PointingToDeclaration/)|  [jvm] <br><br>Boolean 是否在升级中<br><br>val [upgrading](index.md#tech.whence.echo.job.stream.work/Conductor/upgrading/#/PointingToDeclaration/): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)   <br>

