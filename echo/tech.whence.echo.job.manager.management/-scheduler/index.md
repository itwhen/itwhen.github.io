---
title: Scheduler -
---
//[echo](../../index.md)/[tech.whence.echo.job.manager.management](../index.md)/[Scheduler](index.md)



# Scheduler  
 [jvm] 

调度器

class [Scheduler](index.md)   


## Constructors  
  
|  Name|  Summary| 
|---|---|
| [Scheduler](-scheduler.md)|  [jvm] fun [Scheduler](-scheduler.md)()   <br>


## Types  
  
|  Name|  Summary| 
|---|---|
| [Advice](-advice/index.md)| [jvm]  <br>Brief description  <br><br><br>增强<br><br>  <br>Content  <br>enum [Advice](-advice/index.md) : [Enum](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-enum/index.html)<[Scheduler.Advice](-advice/index.md)>   <br><br><br>


## Functions  
  
|  Name|  Summary| 
|---|---|
| [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)| [jvm]  <br>Content  <br>open operator override fun [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [introduce](introduce.md)| [jvm]  <br>Brief description  <br><br><br>引入行为 引入后将在指定增强处被触发时执行指定行为<br><br>  <br>Content  <br>fun [introduce](introduce.md)(action: [Actor](../-actor/index.md), vararg advices: [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<out [Scheduler.Advice](-advice/index.md)>): [Scheduler](index.md)  <br><br><br>
| [reschedule](reschedule.md)| [jvm]  <br>Brief description  <br><br><br>重新调度<br><br>  <br>Content  <br>fun [reschedule](reschedule.md)(fixer: [Fixer](../../tech.whence.echo.function/-fixer/index.md)<[Scheduling](../-scheduling/index.md)?>): [Scheduler](index.md)  <br><br><br>
| [run](run.md)| [jvm]  <br>Brief description  <br><br><br>执行调度计划并返回下次执行间隔<br><br>  <br>Content  <br>suspend fun [run](run.md)(): [Duration](https://docs.oracle.com/javase/8/docs/api/java/time/Duration.html)  <br><br><br>
| [schedule](schedule.md)| [jvm]  <br>Brief description  <br><br><br>调度<br><br>  <br>Content  <br>fun [schedule](schedule.md)(scheduling: [Scheduling](../-scheduling/index.md)?): [Scheduler](index.md)  <br><br><br>
| [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>

