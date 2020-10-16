---
title: Workstage -
---
//[echo](../../../index.md)/[tech.whence.echo.job.stream.work](../../index.md)/[SequentialWork](../index.md)/[Workstage](index.md)



# Workstage  
 [jvm] 

工作阶段

class [Workstage](index.md)(**name**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), **namer**: [Namer](../../-namer/index.md)) : [AbstractWorkstage](../../../tech.whence.echo.job.stream.workstage/-abstract-workstage/index.md)   


## Constructors  
  
|  Name|  Summary| 
|---|---|
| [Workstage](-workstage.md)|  [jvm] <br><br><br><br>fun [Workstage](-workstage.md)(name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), namer: [Namer](../../-namer/index.md))   <br>


## Types  
  
|  Name|  Summary| 
|---|---|
| [Companion](-companion/index.md)| [jvm]  <br>Content  <br>object [Companion](-companion/index.md)  <br><br><br>


## Functions  
  
|  Name|  Summary| 
|---|---|
| [assembleBy](assemble-by.md)| [jvm]  <br>Brief description  <br><br><br>设置装配器<br><br>  <br>Content  <br>fun [assembleBy](assemble-by.md)(executor: [Executor](https://docs.oracle.com/javase/8/docs/api/java/util/concurrent/Executor.html)): [SequentialWork.Workstage](index.md)  <br>fun [assembleBy](assemble-by.md)(assembler: [Assembler](../../-assembler/index.md)): [SequentialWork.Workstage](index.md)  <br><br><br>
| [equals](../../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)| [jvm]  <br>Content  <br>open operator override fun [equals](../../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [hashCode](../../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [hashCode](../../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [toString](../../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [toString](../../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>


## Properties  
  
|  Name|  Summary| 
|---|---|
| [assembler](index.md#tech.whence.echo.job.stream.work/SequentialWork.Workstage/assembler/#/PointingToDeclaration/)|  [jvm] <br><br>Assembler 装配器<br><br>var [assembler](index.md#tech.whence.echo.job.stream.work/SequentialWork.Workstage/assembler/#/PointingToDeclaration/): [Assembler](../../-assembler/index.md)   <br>
| [name](index.md#tech.whence.echo.job.stream.work/SequentialWork.Workstage/name/#/PointingToDeclaration/)|  [jvm] <br><br>String 名称<br><br>open override var [name](index.md#tech.whence.echo.job.stream.work/SequentialWork.Workstage/name/#/PointingToDeclaration/): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)   <br>
| [namer](index.md#tech.whence.echo.job.stream.work/SequentialWork.Workstage/namer/#/PointingToDeclaration/)|  [jvm] <br><br>Namer 命名者<br><br>open override var [namer](index.md#tech.whence.echo.job.stream.work/SequentialWork.Workstage/namer/#/PointingToDeclaration/): [Namer](../../-namer/index.md)   <br>
| [worker](index.md#tech.whence.echo.job.stream.work/SequentialWork.Workstage/worker/#/PointingToDeclaration/)|  [jvm] <br><br>Worker? 工人<br><br>open override var [worker](index.md#tech.whence.echo.job.stream.work/SequentialWork.Workstage/worker/#/PointingToDeclaration/): [Worker](../../-worker/index.md)?   <br>
| [workers](index.md#tech.whence.echo.job.stream.work/SequentialWork.Workstage/workers/#/PointingToDeclaration/)|  [jvm] <br><br>Int 人数<br><br>open override var [workers](index.md#tech.whence.echo.job.stream.work/SequentialWork.Workstage/workers/#/PointingToDeclaration/): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)   <br>
| [workload](index.md#tech.whence.echo.job.stream.work/SequentialWork.Workstage/workload/#/PointingToDeclaration/)|  [jvm] <br><br>Int 负载<br><br>open override var [workload](index.md#tech.whence.echo.job.stream.work/SequentialWork.Workstage/workload/#/PointingToDeclaration/): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)   <br>

