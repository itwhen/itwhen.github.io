---
title: Monitor -
---
//[echo](../../index.md)/[tech.whence.echo.job.monitor](../index.md)/[Monitor](index.md)



# Monitor  
 [jvm] 

监控

class [Monitor](index.md)   


## Constructors  
  
|  Name|  Summary| 
|---|---|
| [Monitor](-monitor.md)|  [jvm] fun [Monitor](-monitor.md)()   <br>
| [Monitor](-monitor.md)|  [jvm] fun [Monitor](-monitor.md)(living: [Duration](https://docs.oracle.com/javase/8/docs/api/java/time/Duration.html), listener: [Listener](../-listener/index.md))   <br>


## Types  
  
|  Name|  Summary| 
|---|---|
| [Companion](-companion/index.md)| [jvm]  <br>Content  <br>object [Companion](-companion/index.md)  <br><br><br>


## Functions  
  
|  Name|  Summary| 
|---|---|
| [broadcast](broadcast.md)| [jvm]  <br>Brief description  <br><br><br>将当前状态通知到监听器<br><br>  <br>Content  <br>fun [broadcast](broadcast.md)()  <br><br><br>
| [enter](enter.md)| [jvm]  <br>Brief description  <br><br><br>进入某阶段<br><br>  <br>Content  <br>@[JvmOverloads](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-overloads/index.html)()  <br>  <br>fun [enter](enter.md)(name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html))  <br><br><br>[jvm]  <br>Brief description  <br><br><br>进入特定状态<br><br>  <br>Content  <br>@[JvmOverloads](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-overloads/index.html)()  <br>  <br>fun [enter](enter.md)(name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), id: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), state: [Stage](../-stage/index.md))  <br><br><br>
| [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)| [jvm]  <br>Content  <br>open operator override fun [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [reset](reset.md)| [jvm]  <br>Brief description  <br><br><br>重置状态记录<br><br>  <br>Content  <br>fun [reset](reset.md)()  <br><br><br>
| [stage](stage.md)| [jvm]  <br>Brief description  <br><br><br>取指定阶段数据<br><br>  <br>Content  <br>fun [stage](stage.md)(name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): [Stages](../-stages/index.md)?  <br><br><br>
| [statistics](statistics.md)| [jvm]  <br>Brief description  <br><br><br>统计指定时间段内数据<br><br>  <br>Content  <br>fun [statistics](statistics.md)(duration: [Duration](https://docs.oracle.com/javase/8/docs/api/java/time/Duration.html)): [Map](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)<[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), [Map](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)<[Stage](../-stage/index.md), [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)>>  <br><br><br>
| [tabulate](tabulate.md)| [jvm]  <br>Brief description  <br><br><br>将指定时间段内阶段数据制表<br><br>  <br>Content  <br>fun [tabulate](tabulate.md)(duration: [Duration](https://docs.oracle.com/javase/8/docs/api/java/time/Duration.html)): Table<[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>  <br><br><br>
| [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>


## Properties  
  
|  Name|  Summary| 
|---|---|
| [lately](index.md#tech.whence.echo.job.monitor/Monitor/lately/#/PointingToDeclaration/)|  [jvm] <br><br>Map<String, Duration> 最近状况<br><br>val [lately](index.md#tech.whence.echo.job.monitor/Monitor/lately/#/PointingToDeclaration/): [Map](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)<[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), [Duration](https://docs.oracle.com/javase/8/docs/api/java/time/Duration.html)>   <br>

