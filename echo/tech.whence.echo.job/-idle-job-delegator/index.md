---
title: IdleJobDelegator -
---
//[echo](../../index.md)/[tech.whence.echo.job](../index.md)/[IdleJobDelegator](index.md)



# IdleJobDelegator  
 [jvm] 

不中断作业委托

class [IdleJobDelegator](index.md)(**delegator**: [IdleJob](../-idle-job/index.md)) : AbstractIdleService, [Monitorable](../../tech.whence.echo.job.monitor/-monitorable/index.md)   


## Constructors  
  
|  Name|  Summary| 
|---|---|
| [IdleJobDelegator](-idle-job-delegator.md)|  [jvm] <br><br><br><br>fun [IdleJobDelegator](-idle-job-delegator.md)(delegator: [IdleJob](../-idle-job/index.md))   <br>


## Functions  
  
|  Name|  Summary| 
|---|---|
| [addListener](index.md#com.google.common.util.concurrent/AbstractIdleService/addListener/#com.google.common.util.concurrent.Service.Listener#java.util.concurrent.Executor/PointingToDeclaration/)| [jvm]  <br>Content  <br>override fun [addListener](index.md#com.google.common.util.concurrent/AbstractIdleService/addListener/#com.google.common.util.concurrent.Service.Listener#java.util.concurrent.Executor/PointingToDeclaration/)(p0: Service.Listener, p1: [Executor](https://docs.oracle.com/javase/8/docs/api/java/util/concurrent/Executor.html))  <br><br><br>
| [awaitRunning](index.md#com.google.common.util.concurrent/AbstractIdleService/awaitRunning/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>override fun [awaitRunning](index.md#com.google.common.util.concurrent/AbstractIdleService/awaitRunning/#/PointingToDeclaration/)()  <br>override fun [awaitRunning](index.md#com.google.common.util.concurrent/AbstractIdleService/awaitRunning/#kotlin.Long#java.util.concurrent.TimeUnit/PointingToDeclaration/)(p0: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html), p1: [TimeUnit](https://docs.oracle.com/javase/8/docs/api/java/util/concurrent/TimeUnit.html))  <br><br><br>
| [awaitTerminated](index.md#com.google.common.util.concurrent/AbstractIdleService/awaitTerminated/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>override fun [awaitTerminated](index.md#com.google.common.util.concurrent/AbstractIdleService/awaitTerminated/#/PointingToDeclaration/)()  <br>override fun [awaitTerminated](index.md#com.google.common.util.concurrent/AbstractIdleService/awaitTerminated/#kotlin.Long#java.util.concurrent.TimeUnit/PointingToDeclaration/)(p0: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html), p1: [TimeUnit](https://docs.oracle.com/javase/8/docs/api/java/util/concurrent/TimeUnit.html))  <br><br><br>
| [configure](configure.md)| [jvm]  <br>Brief description  <br><br><br>配置<br><br>  <br>Content  <br>open override fun [configure](configure.md)(config: [Accessor](../../tech.whence.echo.container.accessor/-accessor/index.md))  <br><br><br>
| [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)| [jvm]  <br>Content  <br>open operator override fun [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [executor](index.md#com.google.common.util.concurrent/AbstractIdleService/executor/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [executor](index.md#com.google.common.util.concurrent/AbstractIdleService/executor/#/PointingToDeclaration/)(): [Executor](https://docs.oracle.com/javase/8/docs/api/java/util/concurrent/Executor.html)  <br><br><br>
| [failureCause](index.md#com.google.common.util.concurrent/AbstractIdleService/failureCause/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>override fun [failureCause](index.md#com.google.common.util.concurrent/AbstractIdleService/failureCause/#/PointingToDeclaration/)(): [Throwable](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-throwable/index.html)  <br><br><br>
| [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [isRunning](index.md#com.google.common.util.concurrent/AbstractIdleService/isRunning/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>override fun [isRunning](index.md#com.google.common.util.concurrent/AbstractIdleService/isRunning/#/PointingToDeclaration/)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [name](name.md)| [jvm]  <br>Brief description  <br><br><br>名称<br><br>  <br>Content  <br>open override fun [name](name.md)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>
| [startAsync](index.md#com.google.common.util.concurrent/AbstractIdleService/startAsync/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>@CanIgnoreReturnValue()  <br>  <br>override fun [startAsync](index.md#com.google.common.util.concurrent/AbstractIdleService/startAsync/#/PointingToDeclaration/)(): Service  <br><br><br>
| [state](index.md#com.google.common.util.concurrent/AbstractIdleService/state/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>override fun [state](index.md#com.google.common.util.concurrent/AbstractIdleService/state/#/PointingToDeclaration/)(): Service.State  <br><br><br>
| [stopAsync](index.md#com.google.common.util.concurrent/AbstractIdleService/stopAsync/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>@CanIgnoreReturnValue()  <br>  <br>override fun [stopAsync](index.md#com.google.common.util.concurrent/AbstractIdleService/stopAsync/#/PointingToDeclaration/)(): Service  <br><br><br>
| [toString](index.md#com.google.common.util.concurrent/AbstractIdleService/toString/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [toString](index.md#com.google.common.util.concurrent/AbstractIdleService/toString/#/PointingToDeclaration/)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>


## Properties  
  
|  Name|  Summary| 
|---|---|
| [delegate](index.md#tech.whence.echo.job/IdleJobDelegator/delegate/#/PointingToDeclaration/)|  [jvm] override val [delegate](index.md#tech.whence.echo.job/IdleJobDelegator/delegate/#/PointingToDeclaration/): Service   <br>
| [monitor](index.md#tech.whence.echo.job/IdleJobDelegator/monitor/#/PointingToDeclaration/)|  [jvm] <br><br>Monitor<br><br>open override val [monitor](index.md#tech.whence.echo.job/IdleJobDelegator/monitor/#/PointingToDeclaration/): [Monitor](../../tech.whence.echo.job.monitor/-monitor/index.md)   <br>
| [threadNameSupplier](index.md#tech.whence.echo.job/IdleJobDelegator/threadNameSupplier/#/PointingToDeclaration/)|  [jvm] override val [threadNameSupplier](index.md#tech.whence.echo.job/IdleJobDelegator/threadNameSupplier/#/PointingToDeclaration/): Supplier<[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)>   <br>

