---
title: Measurer -
---
//[echo](../../index.md)/[tech.whence.echo.job.stream.work](../index.md)/[Measurer](index.md)



# Measurer  
 [jvm] 

测量器

class [Measurer](index.md)   


## Constructors  
  
|  Name|  Summary| 
|---|---|
| [Measurer](-measurer.md)|  [jvm] fun [Measurer](-measurer.md)()   <br>


## Types  
  
|  Name|  Summary| 
|---|---|
| [Action](-action/index.md)| [jvm]  <br>Brief description  <br><br><br>行为<br><br>  <br>Content  <br>enum [Action](-action/index.md) : [Enum](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-enum/index.html)<[Measurer.Action](-action/index.md)>   <br><br><br>


## Functions  
  
|  Name|  Summary| 
|---|---|
| [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)| [jvm]  <br>Content  <br>open operator override fun [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [getCapacities](get-capacities.md)| [jvm]  <br>Brief description  <br><br><br>取容量记录<br><br>  <br>Content  <br>fun [getCapacities](get-capacities.md)(): [Map](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)<[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)>  <br><br><br>
| [getMetrics](get-metrics.md)| [jvm]  <br>Brief description  <br><br><br>取行为统计<br><br>  <br>Content  <br>fun [getMetrics](get-metrics.md)(): [Map](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)<[Measurer.Action](-action/index.md), Meter>  <br><br><br>
| [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [mark](mark.md)| [jvm]  <br>Brief description  <br><br><br>标记容量<br><br>  <br>Content  <br>fun [mark](mark.md)(name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), capacity: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html))  <br><br><br>[jvm]  <br>Brief description  <br><br><br>标记行为<br><br>  <br>Content  <br>@[JvmOverloads](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-overloads/index.html)()  <br>  <br>fun [mark](mark.md)(action: [Measurer.Action](-action/index.md), count: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html))  <br><br><br>
| [ready](ready.md)| [jvm]  <br>Brief description  <br><br><br>预备<br><br>  <br>Content  <br>fun [ready](ready.md)()  <br><br><br>
| [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>


## Properties  
  
|  Name|  Summary| 
|---|---|
| [startAt](index.md#tech.whence.echo.job.stream.work/Measurer/startAt/#/PointingToDeclaration/)|  [jvm] <br><br>Instant? 开始时间<br><br>var [startAt](index.md#tech.whence.echo.job.stream.work/Measurer/startAt/#/PointingToDeclaration/): [Instant](https://docs.oracle.com/javase/8/docs/api/java/time/Instant.html)?   <br>

