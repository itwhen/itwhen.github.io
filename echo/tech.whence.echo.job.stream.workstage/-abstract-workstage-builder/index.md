---
title: AbstractWorkstageBuilder -
---
//[echo](../../index.md)/[tech.whence.echo.job.stream.workstage](../index.md)/[AbstractWorkstageBuilder](index.md)



# AbstractWorkstageBuilder  
 [jvm] 

抽象工作阶段构造器

abstract class [AbstractWorkstageBuilder](index.md)<[A](index.md) : [AbstractWorkstageBuilder](index.md)<[A](index.md), [S](index.md)>, [S](index.md) : [AbstractWorkstage](../-abstract-workstage/index.md)>(**workstage**: [S](index.md))   


## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| A| <br><br>: AbstractWorkstageBuilder<A, S> 子类<br><br>
| S| <br><br>: AbstractWorkstage 工作阶段子类<br><br>
  


## Constructors  
  
|  Name|  Summary| 
|---|---|
| [AbstractWorkstageBuilder](-abstract-workstage-builder.md)|  [jvm] <br><br><br><br>fun <[S](index.md) : [AbstractWorkstage](../-abstract-workstage/index.md)> [AbstractWorkstageBuilder](-abstract-workstage-builder.md)(workstage: [S](index.md))   <br>


## Functions  
  
|  Name|  Summary| 
|---|---|
| [build](build.md)| [jvm]  <br>Brief description  <br><br><br>构造<br><br>  <br>Content  <br>fun [build](build.md)(): [S](index.md)  <br><br><br>
| [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)| [jvm]  <br>Content  <br>open operator override fun [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [extendBy](extend-by.md)| [jvm]  <br>Brief description  <br><br><br>扩展<br><br>  <br>Content  <br>fun [extendBy](extend-by.md)(extender: [Consumer](../../tech.whence.echo.function/-consumer/index.md)<[A](index.md)>): [A](index.md)  <br><br><br>
| [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>
| [workBy](work-by.md)| [jvm]  <br>Brief description  <br><br><br>指定工作设置<br><br>  <br>Content  <br>fun [workBy](work-by.md)(workers: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), workload: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), worker: [Worker](../../tech.whence.echo.job.stream.work/-worker/index.md)): [A](index.md)  <br><br><br>


## Inheritors  
  
|  Name| 
|---|
| [SequentialWork](../../tech.whence.echo.job.stream.work/-sequential-work/-workstage-builder/index.md)

