---
title: Stopwatch -
---
//[echo](../../index.md)/[tech.whence.echo.support](../index.md)/[Stopwatch](index.md)



# Stopwatch  
 [jvm] 

计时器

class [Stopwatch](index.md)(**ticker**: [Stopwatch.Ticker](-ticker/index.md))   


## Constructors  
  
|  Name|  Summary| 
|---|---|
| [Stopwatch](-stopwatch.md)|  [jvm] <br><br><br><br>fun [Stopwatch](-stopwatch.md)(ticker: [Stopwatch.Ticker](-ticker/index.md))   <br>


## Types  
  
|  Name|  Summary| 
|---|---|
| [Companion](-companion/index.md)| [jvm]  <br>Content  <br>object [Companion](-companion/index.md)  <br><br><br>
| [Period](-period/index.md)| [jvm]  <br>Brief description  <br><br><br>阶段<br><br>  <br>Content  <br>data class [Period](-period/index.md)(**startAt**: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html), **endAt**: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html), **elapsed**: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html))  <br><br><br>
| [Ticker](-ticker/index.md)| [jvm]  <br>Brief description  <br><br><br>秒表<br><br>  <br>Content  <br>fun fun interface [Ticker](-ticker/index.md)  <br><br><br>


## Functions  
  
|  Name|  Summary| 
|---|---|
| [detail](detail.md)| [jvm]  <br>Brief description  <br><br><br>获取执行统计结果<br><br>  <br>Content  <br>fun [detail](detail.md)(unit: [TimeUnit](https://docs.oracle.com/javase/8/docs/api/java/util/concurrent/TimeUnit.html)?): [Map](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)<[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)>  <br><br><br>
| [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)| [jvm]  <br>Content  <br>open operator override fun [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [get](get.md)| [jvm]  <br>Brief description  <br><br><br>取总时间<br><br>  <br>Content  <br>fun [get](get.md)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>[jvm]  <br>Brief description  <br><br><br>获取子模块运行时间<br><br>  <br>Content  <br>fun [get](get.md)(name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?  <br><br><br>
| [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [run](run.md)| [jvm]  <br>Brief description  <br><br><br>执行子回调模块并返回其结果<br><br>  <br>Content  <br>fun <[T](run.md)> [run](run.md)(name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), producer: [Producer](../../tech.whence.echo.function/-producer/index.md)<[T](run.md)>): [T](run.md)  <br><br><br>[jvm]  <br>Brief description  <br><br><br>执行子回调模块<br><br>  <br>Content  <br>fun [run](run.md)(name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), runner: [Runner](../../tech.whence.echo.function/-runner/index.md))  <br><br><br>
| [start](start.md)| [jvm]  <br>Brief description  <br><br><br>启动<br><br>  <br>Content  <br>fun [start](start.md)()  <br><br><br>[jvm]  <br>Brief description  <br><br><br>启动子模块<br><br>  <br>Content  <br>fun [start](start.md)(name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html))  <br><br><br>
| [stop](stop.md)| [jvm]  <br>Brief description  <br><br><br>停止<br><br>  <br>Content  <br>fun [stop](stop.md)()  <br><br><br>[jvm]  <br>Brief description  <br><br><br>停止子模块<br><br>  <br>Content  <br>fun [stop](stop.md)(name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html))  <br><br><br>
| [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>


## Properties  
  
|  Name|  Summary| 
|---|---|
| [startAt](index.md#tech.whence.echo.support/Stopwatch/startAt/#/PointingToDeclaration/)|  [jvm] <br><br>Long 开始时间<br><br>var [startAt](index.md#tech.whence.echo.support/Stopwatch/startAt/#/PointingToDeclaration/): [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)   <br>

