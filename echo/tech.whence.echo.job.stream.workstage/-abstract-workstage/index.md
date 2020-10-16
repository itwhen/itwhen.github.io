---
title: AbstractWorkstage -
---
//[echo](../../index.md)/[tech.whence.echo.job.stream.workstage](../index.md)/[AbstractWorkstage](index.md)



# AbstractWorkstage  
 [jvm] 

抽象工作阶段

abstract class [AbstractWorkstage](index.md)(**name**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), **namer**: [Namer](../../tech.whence.echo.job.stream.work/-namer/index.md)) : [Workstage](../-workstage/index.md)   


## Constructors  
  
|  Name|  Summary| 
|---|---|
| [AbstractWorkstage](-abstract-workstage.md)|  [jvm] <br><br><br><br>fun [AbstractWorkstage](-abstract-workstage.md)(name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), namer: [Namer](../../tech.whence.echo.job.stream.work/-namer/index.md))   <br>


## Functions  
  
|  Name|  Summary| 
|---|---|
| [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)| [jvm]  <br>Content  <br>open operator override fun [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>


## Properties  
  
|  Name|  Summary| 
|---|---|
| [name](index.md#tech.whence.echo.job.stream.workstage/AbstractWorkstage/name/#/PointingToDeclaration/)|  [jvm] <br><br>String 名称<br><br>open override var [name](index.md#tech.whence.echo.job.stream.workstage/AbstractWorkstage/name/#/PointingToDeclaration/): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)   <br>
| [namer](index.md#tech.whence.echo.job.stream.workstage/AbstractWorkstage/namer/#/PointingToDeclaration/)|  [jvm] <br><br>Namer 命名者<br><br>open override var [namer](index.md#tech.whence.echo.job.stream.workstage/AbstractWorkstage/namer/#/PointingToDeclaration/): [Namer](../../tech.whence.echo.job.stream.work/-namer/index.md)   <br>
| [worker](index.md#tech.whence.echo.job.stream.workstage/AbstractWorkstage/worker/#/PointingToDeclaration/)|  [jvm] <br><br>Worker? 工人<br><br>open override var [worker](index.md#tech.whence.echo.job.stream.workstage/AbstractWorkstage/worker/#/PointingToDeclaration/): [Worker](../../tech.whence.echo.job.stream.work/-worker/index.md)?   <br>
| [workers](index.md#tech.whence.echo.job.stream.workstage/AbstractWorkstage/workers/#/PointingToDeclaration/)|  [jvm] <br><br>Int 人数<br><br>open override var [workers](index.md#tech.whence.echo.job.stream.workstage/AbstractWorkstage/workers/#/PointingToDeclaration/): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)   <br>
| [workload](index.md#tech.whence.echo.job.stream.workstage/AbstractWorkstage/workload/#/PointingToDeclaration/)|  [jvm] <br><br>Int 负载<br><br>open override var [workload](index.md#tech.whence.echo.job.stream.workstage/AbstractWorkstage/workload/#/PointingToDeclaration/): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)   <br>


## Inheritors  
  
|  Name| 
|---|
| [SequentialWork](../../tech.whence.echo.job.stream.work/-sequential-work/-workstage/index.md)

