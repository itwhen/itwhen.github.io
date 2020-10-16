---
title: Stages -
---
//[echo](../../index.md)/[tech.whence.echo.job.monitor](../index.md)/[Stages](index.md)



# Stages  
 [jvm] 

阶段数据 用以存储某作业某时间单位内各个状态下具体任务数量

class [Stages](index.md)(**name**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), **unit**: [TemporalUnit](https://docs.oracle.com/javase/8/docs/api/java/time/temporal/TemporalUnit.html), **capacity**: [Duration](https://docs.oracle.com/javase/8/docs/api/java/time/Duration.html))   


## Constructors  
  
|  Name|  Summary| 
|---|---|
| [Stages](-stages.md)|  [jvm] <br><br><br><br>fun [Stages](-stages.md)(name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), unit: [TemporalUnit](https://docs.oracle.com/javase/8/docs/api/java/time/temporal/TemporalUnit.html), capacity: [Duration](https://docs.oracle.com/javase/8/docs/api/java/time/Duration.html))   <br>


## Functions  
  
|  Name|  Summary| 
|---|---|
| [enter](enter.md)| [jvm]  <br>Brief description  <br><br><br>进入默认状态<br><br>  <br>Content  <br>fun [enter](enter.md)()  <br><br><br>[jvm]  <br>Brief description  <br><br><br>进入特定状态<br><br>  <br>Content  <br>fun [enter](enter.md)(id: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), stage: [Stage](../-stage/index.md))  <br><br><br>
| [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)| [jvm]  <br>Content  <br>open operator override fun [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [get](get.md)| [jvm]  <br>Brief description  <br><br><br>取数据<br><br>  <br>Content  <br>fun [get](get.md)(): [Map](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)<[Instant](https://docs.oracle.com/javase/8/docs/api/java/time/Instant.html), [Map](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)<[Stage](../-stage/index.md), [AtomicInteger](https://docs.oracle.com/javase/8/docs/api/java/util/concurrent/atomic/AtomicInteger.html)>>  <br><br><br>
| [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [reset](reset.md)| [jvm]  <br>Brief description  <br><br><br>重置状态<br><br>  <br>Content  <br>fun [reset](reset.md)(): [Stages](index.md)  <br><br><br>
| [statistics](statistics.md)| [jvm]  <br>Brief description  <br><br><br>统计指定时间内后数据<br><br>  <br>Content  <br>fun [statistics](statistics.md)(duration: [Duration](https://docs.oracle.com/javase/8/docs/api/java/time/Duration.html)): [Map](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)<[Stage](../-stage/index.md), [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)>  <br><br><br>
| [tabulate](tabulate.md)| [jvm]  <br>Brief description  <br><br><br>统计数据制表<br><br>  <br>Content  <br>fun [tabulate](tabulate.md)(duration: [Duration](https://docs.oracle.com/javase/8/docs/api/java/time/Duration.html)): Table<[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>  <br><br><br>
| [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>


## Properties  
  
|  Name|  Summary| 
|---|---|
| [lastAffectedAt](index.md#tech.whence.echo.job.monitor/Stages/lastAffectedAt/#/PointingToDeclaration/)|  [jvm] <br><br>Instant? 最后触发时间<br><br>var [lastAffectedAt](index.md#tech.whence.echo.job.monitor/Stages/lastAffectedAt/#/PointingToDeclaration/): [Instant](https://docs.oracle.com/javase/8/docs/api/java/time/Instant.html)?   <br>
| [lastAffectedId](index.md#tech.whence.echo.job.monitor/Stages/lastAffectedId/#/PointingToDeclaration/)|  [jvm] <br><br>String? 最后触发任务编号<br><br>var [lastAffectedId](index.md#tech.whence.echo.job.monitor/Stages/lastAffectedId/#/PointingToDeclaration/): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?   <br>
| [lastRanAt](index.md#tech.whence.echo.job.monitor/Stages/lastRanAt/#/PointingToDeclaration/)|  [jvm] <br><br>Instant? 最后运行时间<br><br>var [lastRanAt](index.md#tech.whence.echo.job.monitor/Stages/lastRanAt/#/PointingToDeclaration/): [Instant](https://docs.oracle.com/javase/8/docs/api/java/time/Instant.html)?   <br>

