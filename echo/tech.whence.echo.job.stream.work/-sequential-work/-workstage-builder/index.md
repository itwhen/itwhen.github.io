---
title: WorkstageBuilder -
---
//[echo](../../../index.md)/[tech.whence.echo.job.stream.work](../../index.md)/[SequentialWork](../index.md)/[WorkstageBuilder](index.md)



# WorkstageBuilder  
 [jvm] 

工作阶段构造器

class [WorkstageBuilder](index.md)(**workstage**: [SequentialWork.Workstage](../-workstage/index.md)) : [AbstractWorkstageBuilder](../../../tech.whence.echo.job.stream.workstage/-abstract-workstage-builder/index.md)<[SequentialWork.WorkstageBuilder](index.md), [SequentialWork.Workstage](../-workstage/index.md)>    


## Constructors  
  
|  Name|  Summary| 
|---|---|
| [WorkstageBuilder](-workstage-builder.md)|  [jvm] <br><br><br><br>fun [WorkstageBuilder](-workstage-builder.md)(workstage: [SequentialWork.Workstage](../-workstage/index.md))   <br>


## Functions  
  
|  Name|  Summary| 
|---|---|
| [assembleBy](assemble-by.md)| [jvm]  <br>Brief description  <br><br><br>设置装配器<br><br>  <br>Content  <br>fun [assembleBy](assemble-by.md)(executor: [Executor](https://docs.oracle.com/javase/8/docs/api/java/util/concurrent/Executor.html)): [SequentialWork.WorkstageBuilder](index.md)  <br>fun [assembleBy](assemble-by.md)(assembler: [Assembler](../../-assembler/index.md)): [SequentialWork.WorkstageBuilder](index.md)  <br><br><br>
| [build](../../../tech.whence.echo.job.stream.workstage/-abstract-workstage-builder/build.md)| [jvm]  <br>Brief description  <br><br><br>构造<br><br>  <br>Content  <br>override fun [build](../../../tech.whence.echo.job.stream.workstage/-abstract-workstage-builder/build.md)(): [SequentialWork.Workstage](../-workstage/index.md)  <br><br><br>
| [equals](../../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)| [jvm]  <br>Content  <br>open operator override fun [equals](../../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [extendBy](index.md#tech.whence.echo.job.stream.workstage/AbstractWorkstageBuilder/extendBy/#tech.whence.echo.function.Consumer[tech.whence.echo.job.stream.work.SequentialWork.WorkstageBuilder]/PointingToDeclaration/)| [jvm]  <br>Brief description  <br><br><br>扩展<br><br>  <br>Content  <br>override fun [extendBy](index.md#tech.whence.echo.job.stream.workstage/AbstractWorkstageBuilder/extendBy/#tech.whence.echo.function.Consumer[tech.whence.echo.job.stream.work.SequentialWork.WorkstageBuilder]/PointingToDeclaration/)(extender: [Consumer](../../../tech.whence.echo.function/-consumer/index.md)<[SequentialWork.WorkstageBuilder](index.md)>): [SequentialWork.WorkstageBuilder](index.md)  <br><br><br>
| [hashCode](../../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [hashCode](../../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [toString](../../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [toString](../../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>
| [workBy](../../../tech.whence.echo.job.stream.workstage/-abstract-workstage-builder/work-by.md)| [jvm]  <br>Brief description  <br><br><br>指定工作设置<br><br>  <br>Content  <br>override fun [workBy](../../../tech.whence.echo.job.stream.workstage/-abstract-workstage-builder/work-by.md)(workers: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), workload: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), worker: [Worker](../../-worker/index.md)): [SequentialWork.WorkstageBuilder](index.md)  <br><br><br>

