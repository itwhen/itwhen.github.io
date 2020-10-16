---
title: ScheduledJob -
---
//[echo](../../index.md)/[tech.whence.echo.job](../index.md)/[ScheduledJob](index.md)



# ScheduledJob  
 [jvm] 

可调度作业

interface [ScheduledJob](index.md) : [IdleJob](../-idle-job/index.md)   


## Functions  
  
|  Name|  Summary| 
|---|---|
| [configure](../../tech.whence.echo.job.monitor/-monitorable/configure.md)| [jvm]  <br>Brief description  <br><br><br>配置<br><br>  <br>Content  <br>abstract override fun [configure](../../tech.whence.echo.job.monitor/-monitorable/configure.md)(config: [Accessor](../../tech.whence.echo.container.accessor/-accessor/index.md))  <br><br><br>
| [delegate](../-job/delegate.md)| [jvm]  <br>Brief description  <br><br><br>托管<br><br>  <br>Content  <br>abstract override fun [delegate](../-job/delegate.md)(): Service  <br><br><br>
| [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)| [jvm]  <br>Content  <br>open operator override fun [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [initialize](initialize.md)| [jvm]  <br>Brief description  <br><br><br>初始化<br><br>  <br>Content  <br>abstract fun [initialize](initialize.md)()  <br><br><br>
| [name](../../tech.whence.echo.definition/-namer/name.md)| [jvm]  <br>Content  <br>abstract override fun [name](../../tech.whence.echo.definition/-namer/name.md)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>
| [resume](resume.md)| [jvm]  <br>Brief description  <br><br><br>恢复<br><br>  <br>Content  <br>abstract fun [resume](resume.md)()  <br><br><br>
| [run](run.md)| [jvm]  <br>Brief description  <br><br><br>执行<br><br>  <br>Content  <br>abstract fun [run](run.md)()  <br><br><br>
| [schedule](schedule.md)| [jvm]  <br>Brief description  <br><br><br>时间安排<br><br>  <br>Content  <br>abstract fun [schedule](schedule.md)(): [Duration](https://docs.oracle.com/javase/8/docs/api/java/time/Duration.html)  <br><br><br>
| [shutdown](../-job/shutdown.md)| [jvm]  <br>Brief description  <br><br><br>关闭<br><br>  <br>Content  <br>abstract override fun [shutdown](../-job/shutdown.md)()  <br><br><br>
| [startup](../-job/startup.md)| [jvm]  <br>Brief description  <br><br><br>开启<br><br>  <br>Content  <br>abstract override fun [startup](../-job/startup.md)()  <br><br><br>
| [suspend](suspend.md)| [jvm]  <br>Brief description  <br><br><br>挂起<br><br>  <br>Content  <br>abstract fun [suspend](suspend.md)()  <br><br><br>
| [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>


## Properties  
  
|  Name|  Summary| 
|---|---|
| [monitor](index.md#tech.whence.echo.job/ScheduledJob/monitor/#/PointingToDeclaration/)|  [jvm] <br><br>Monitor 监控器<br><br>abstract override val [monitor](index.md#tech.whence.echo.job/ScheduledJob/monitor/#/PointingToDeclaration/): [Monitor](../../tech.whence.echo.job.monitor/-monitor/index.md)   <br>


## Inheritors  
  
|  Name| 
|---|
| [AbstractScheduledJob](../-abstract-scheduled-job/index.md)

