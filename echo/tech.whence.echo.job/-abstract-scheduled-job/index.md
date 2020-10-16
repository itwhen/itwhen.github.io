---
title: AbstractScheduledJob -
---
//[echo](../../index.md)/[tech.whence.echo.job](../index.md)/[AbstractScheduledJob](index.md)



# AbstractScheduledJob  
 [jvm] 

可调度作业抽象

abstract class [AbstractScheduledJob](index.md)<[V](index.md)>(**vertx**: Vertx) : [AbstractJob](../-abstract-job/index.md)<[V](index.md)> , [ScheduledJob](../-scheduled-job/index.md), [Leader](../../tech.whence.echo.job.manager.management/-leader/index.md), [Authorizer](../../tech.whence.echo.job.manager.management/-authorizer/index.md)   


## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| V| <br><br>配置<br><br>
  


## Constructors  
  
|  Name|  Summary| 
|---|---|
| [AbstractScheduledJob](-abstract-scheduled-job.md)|  [jvm] <br><br>配置<br><br>fun [AbstractScheduledJob](-abstract-scheduled-job.md)(vertx: Vertx)   <br>


## Functions  
  
|  Name|  Summary| 
|---|---|
| [authorize](authorize.md)| [jvm]  <br>Brief description  <br><br><br>授权<br><br>  <br>Content  <br>open override fun [authorize](authorize.md)(): [Management](../../tech.whence.echo.job.manager.management/-management/index.md)  <br><br><br>
| [configure](../../tech.whence.echo.job.monitor/-monitorable/configure.md)| [jvm]  <br>Content  <br>abstract override fun [configure](../../tech.whence.echo.job.monitor/-monitorable/configure.md)(config: [Accessor](../../tech.whence.echo.container.accessor/-accessor/index.md))  <br><br><br>
| [delegate](delegate.md)| [jvm]  <br>Brief description  <br><br><br>托管<br><br>  <br>Content  <br>open override fun [delegate](delegate.md)(): Service  <br><br><br>
| [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)| [jvm]  <br>Content  <br>open operator override fun [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [initialize](initialize.md)| [jvm]  <br>Brief description  <br><br><br>初始化<br><br>  <br>Content  <br>open override fun [initialize](initialize.md)()  <br><br><br>
| [lead](lead.md)| [jvm]  <br>Brief description  <br><br><br>引导<br><br>  <br>Content  <br>open override fun [lead](lead.md)(follower: [Follower](../../tech.whence.echo.job.manager.management/-follower/index.md))  <br><br><br>
| [name](../../tech.whence.echo.definition/-namer/name.md)| [jvm]  <br>Content  <br>abstract override fun [name](../../tech.whence.echo.definition/-namer/name.md)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>
| [resume](resume.md)| [jvm]  <br>Brief description  <br><br><br>恢复<br><br>  <br>Content  <br>open override fun [resume](resume.md)()  <br><br><br>
| [run](../-scheduled-job/run.md)| [jvm]  <br>Brief description  <br><br><br>执行<br><br>  <br>Content  <br>abstract override fun [run](../-scheduled-job/run.md)()  <br><br><br>
| [schedule](../-scheduled-job/schedule.md)| [jvm]  <br>Brief description  <br><br><br>时间安排<br><br>  <br>Content  <br>abstract override fun [schedule](../-scheduled-job/schedule.md)(): [Duration](https://docs.oracle.com/javase/8/docs/api/java/time/Duration.html)  <br><br><br>
| [shutdown](shutdown.md)| [jvm]  <br>Brief description  <br><br><br>关闭<br><br>  <br>Content  <br>open override fun [shutdown](shutdown.md)()  <br><br><br>
| [startup](startup.md)| [jvm]  <br>Brief description  <br><br><br>开启<br><br>  <br>Content  <br>open override fun [startup](startup.md)()  <br><br><br>
| [suspend](suspend.md)| [jvm]  <br>Brief description  <br><br><br>挂起<br><br>  <br>Content  <br>open override fun [suspend](suspend.md)()  <br><br><br>
| [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>


## Properties  
  
|  Name|  Summary| 
|---|---|
| [monitor](index.md#tech.whence.echo.job/AbstractScheduledJob/monitor/#/PointingToDeclaration/)|  [jvm] open override val [monitor](index.md#tech.whence.echo.job/AbstractScheduledJob/monitor/#/PointingToDeclaration/): [Monitor](../../tech.whence.echo.job.monitor/-monitor/index.md)   <br>

