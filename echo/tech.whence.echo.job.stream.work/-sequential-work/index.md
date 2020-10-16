---
title: SequentialWork -
---
//[echo](../../index.md)/[tech.whence.echo.job.stream.work](../index.md)/[SequentialWork](index.md)



# SequentialWork  
 [jvm] 

顺序工作

class [SequentialWork](index.md)(**vertx**: Vertx, **name**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), **workers**: [Workers](../-workers/index.md)?) : [AbstractWork](../-abstract-work/index.md)<[SequentialWork.Workstage](-workstage/index.md), [SequentialWork.WorkstageBuilder](-workstage-builder/index.md), [CompletableFuture](https://docs.oracle.com/javase/8/docs/api/java/util/concurrent/CompletableFuture.html)<[List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[Task](../../tech.whence.echo.job.stream.task/-task/index.md)>>>    


## Constructors  
  
|  Name|  Summary| 
|---|---|
| [SequentialWork](-sequential-work.md)|  [jvm] <br><br><br><br>fun [SequentialWork](-sequential-work.md)(vertx: Vertx, name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), workers: [Workers](../-workers/index.md)?)   <br>


## Types  
  
|  Name|  Summary| 
|---|---|
| [Builder](-builder/index.md)| [jvm]  <br>Brief description  <br><br><br>构造器<br><br>  <br>Content  <br>class [Builder](-builder/index.md)(**vertx**: Vertx, **work**: [SequentialWork](index.md)) : [AbstractBuilder](../-abstract-builder/index.md)<[SequentialWork.Builder](-builder/index.md), [SequentialWork](index.md), [SequentialWork.Workstage](-workstage/index.md), [SequentialWork.WorkstageBuilder](-workstage-builder/index.md)>   <br><br><br>
| [Workstage](-workstage/index.md)| [jvm]  <br>Brief description  <br><br><br>工作阶段<br><br>  <br>Content  <br>class [Workstage](-workstage/index.md)(**name**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), **namer**: [Namer](../-namer/index.md)) : [AbstractWorkstage](../../tech.whence.echo.job.stream.workstage/-abstract-workstage/index.md)  <br><br><br>
| [WorkstageBuilder](-workstage-builder/index.md)| [jvm]  <br>Brief description  <br><br><br>工作阶段构造器<br><br>  <br>Content  <br>class [WorkstageBuilder](-workstage-builder/index.md)(**workstage**: [SequentialWork.Workstage](-workstage/index.md)) : [AbstractWorkstageBuilder](../../tech.whence.echo.job.stream.workstage/-abstract-workstage-builder/index.md)<[SequentialWork.WorkstageBuilder](-workstage-builder/index.md), [SequentialWork.Workstage](-workstage/index.md)>   <br><br><br>


## Functions  
  
|  Name|  Summary| 
|---|---|
| [authorize](../../tech.whence.echo.job.manager/-abstract-manager/authorize.md)| [jvm]  <br>Brief description  <br><br><br>授权<br><br>  <br>Content  <br>open override fun [authorize](../../tech.whence.echo.job.manager/-abstract-manager/authorize.md)(): [Management](../../tech.whence.echo.job.manager.management/-management/index.md)  <br><br><br>
| [configureBy](../-abstract-work/configure-by.md)| [jvm]  <br>Brief description  <br><br><br>配置<br><br>  <br>Content  <br>override fun [configureBy](../-abstract-work/configure-by.md)(config: [Config](../-config/index.md))  <br><br><br>
| [degradeBy](../-abstract-work/degrade-by.md)| [jvm]  <br>Brief description  <br><br><br>设置降级配置<br><br>  <br>Content  <br>@[JvmOverloads](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-overloads/index.html)()  <br>  <br>override fun [degradeBy](../-abstract-work/degrade-by.md)(window: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), min: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), max: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), idler: [Retry](../../tech.whence.echo.retry/-retry/index.md)?)  <br><br><br>
| [dispatch](../-abstract-work/dispatch.md)| [jvm]  <br>Brief description  <br><br><br>调度<br><br>  <br>Content  <br>open override fun [dispatch](../-abstract-work/dispatch.md)(): [Duration](https://docs.oracle.com/javase/8/docs/api/java/time/Duration.html)  <br><br><br>
| [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)| [jvm]  <br>Content  <br>open operator override fun [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [follow](../../tech.whence.echo.job.manager/-abstract-manager/follow.md)| [jvm]  <br>Brief description  <br><br><br>跟随<br><br>  <br>Content  <br>open override fun [follow](../../tech.whence.echo.job.manager/-abstract-manager/follow.md)(leader: [Leader](../../tech.whence.echo.job.manager.management/-leader/index.md))  <br><br><br>
| [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [initialize](../../tech.whence.echo.job.manager/-abstract-manager/initialize.md)| [jvm]  <br>Content  <br>open override fun [initialize](../../tech.whence.echo.job.manager/-abstract-manager/initialize.md)()  <br><br><br>
| [inspect](../../tech.whence.echo.job.manager/-abstract-manager/inspect.md)| [jvm]  <br>Content  <br>open override fun [inspect](../../tech.whence.echo.job.manager/-abstract-manager/inspect.md)(): [State](../../tech.whence.echo.job.manager.state/-state/index.md)  <br><br><br>
| [lead](../../tech.whence.echo.job.manager/-abstract-manager/lead.md)| [jvm]  <br>Brief description  <br><br><br>引导<br><br>  <br>Content  <br>open override fun [lead](../../tech.whence.echo.job.manager/-abstract-manager/lead.md)(follower: [Follower](../../tech.whence.echo.job.manager.management/-follower/index.md))  <br><br><br>
| [logBy](../-abstract-work/log-by.md)| [jvm]  <br>Brief description  <br><br><br>设置日志记录器<br><br>  <br>Content  <br>override fun [logBy](../-abstract-work/log-by.md)(logger: KLogger)  <br><br><br>
| [monitor](../../tech.whence.echo.job.manager/-abstract-manager/monitor.md)| [jvm]  <br>Brief description  <br><br><br>监听<br><br>  <br>Content  <br>override fun [monitor](../../tech.whence.echo.job.manager/-abstract-manager/monitor.md)(listener: [Listener](../../tech.whence.echo.job.manager/-listener/index.md))  <br><br><br>
| [monitorBy](../-abstract-work/monitor-by.md)| [jvm]  <br>Brief description  <br><br><br>设置监听器<br><br>  <br>Content  <br>override fun [monitorBy](../-abstract-work/monitor-by.md)(monitor: [Monitor](../../tech.whence.echo.job.stream.monitor/-monitor/index.md))  <br><br><br>
| [name](name.md)| [jvm]  <br>Content  <br>open override fun [name](name.md)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>
| [nameBy](../-abstract-work/name-by.md)| [jvm]  <br>Brief description  <br><br><br>设置工人命名者<br><br>  <br>Content  <br>override fun [nameBy](../-abstract-work/name-by.md)(namer: [Namer](../-namer/index.md))  <br><br><br>
| [on](../../tech.whence.echo.support.kafka.stream/-stream/index.md#tech.whence.echo.job.manager/AbstractManager/on/#tech.whence.echo.job.manager.Event/PointingToDeclaration/)| [jvm]  <br>Brief description  <br><br><br>接收事件<br><br>  <br>Content  <br>override fun [on](../../tech.whence.echo.support.kafka.stream/-stream/index.md#tech.whence.echo.job.manager/AbstractManager/on/#tech.whence.echo.job.manager.Event/PointingToDeclaration/)(event: [Event](../../tech.whence.echo.job.manager/-event/index.md))  <br><br><br>
| [onAuthorised](../../tech.whence.echo.support.kafka.stream/-stream/index.md#tech.whence.echo.job.manager/AbstractManager/onAuthorised/#tech.whence.echo.job.manager.Event.Stopped/PointingToDeclaration/)| [jvm]  <br>Brief description  <br><br><br>停止服务时<br><br>  <br>Content  <br>override fun [onAuthorised](../../tech.whence.echo.support.kafka.stream/-stream/index.md#tech.whence.echo.job.manager/AbstractManager/onAuthorised/#tech.whence.echo.job.manager.Event.Stopped/PointingToDeclaration/)(event: [Event.Stopped](../../tech.whence.echo.job.manager/-event/-stopped/index.md))  <br><br><br>
| [onFollowed](../../tech.whence.echo.support.kafka.stream/-stream/index.md#tech.whence.echo.job.manager/AbstractManager/onFollowed/#tech.whence.echo.job.manager.Event/PointingToDeclaration/)| [jvm]  <br>Brief description  <br><br><br>跟随着接收事件<br><br>  <br>Content  <br>override fun [onFollowed](../../tech.whence.echo.support.kafka.stream/-stream/index.md#tech.whence.echo.job.manager/AbstractManager/onFollowed/#tech.whence.echo.job.manager.Event/PointingToDeclaration/)(event: [Event](../../tech.whence.echo.job.manager/-event/index.md))  <br><br><br>
| [provideBy](../-abstract-work/provide-by.md)| [jvm]  <br>Brief description  <br><br><br>设置消息提供者<br><br>  <br>Content  <br>override fun [provideBy](../-abstract-work/provide-by.md)(provider: [Provider](../../tech.whence.echo.job.stream.provider/-provider/index.md))  <br><br><br>
| [resume](../../tech.whence.echo.job.manager/-abstract-manager/resume.md)| [jvm]  <br>Content  <br>open suspend override fun [resume](../../tech.whence.echo.job.manager/-abstract-manager/resume.md)()  <br><br><br>
| [stage](index.md#tech.whence.echo.job.stream.work/AbstractWork/stage/#tech.whence.echo.job.stream.work.SequentialWork.Workstage/PointingToDeclaration/)| [jvm]  <br>Brief description  <br><br><br>设置阶段<br><br>  <br>Content  <br>open override fun [stage](index.md#tech.whence.echo.job.stream.work/AbstractWork/stage/#tech.whence.echo.job.stream.work.SequentialWork.Workstage/PointingToDeclaration/)(workstage: [SequentialWork.Workstage](-workstage/index.md))  <br>open override fun [stage](stage.md)(name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), builder: [Consumer](../../tech.whence.echo.function/-consumer/index.md)<[SequentialWork.WorkstageBuilder](-workstage-builder/index.md)>)  <br>override fun [stage](index.md#tech.whence.echo.job.stream.work/AbstractWork/stage/#kotlin.String#kotlin.Int#kotlin.Int#tech.whence.echo.job.stream.work.Worker?#tech.whence.echo.function.Consumer[tech.whence.echo.job.stream.work.SequentialWork.WorkstageBuilder]?/PointingToDeclaration/)(name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), workers: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), workload: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), worker: [Worker](../-worker/index.md)?, extender: [Consumer](../../tech.whence.echo.function/-consumer/index.md)<[SequentialWork.WorkstageBuilder](-workstage-builder/index.md)>?)  <br><br><br>
| [start](../../tech.whence.echo.job.manager/-abstract-manager/start.md)| [jvm]  <br>Content  <br>open suspend override fun [start](../../tech.whence.echo.job.manager/-abstract-manager/start.md)()  <br><br><br>
| [stop](../../tech.whence.echo.job.manager/-abstract-manager/stop.md)| [jvm]  <br>Content  <br>open suspend override fun [stop](../../tech.whence.echo.job.manager/-abstract-manager/stop.md)()  <br><br><br>
| [suspend](../../tech.whence.echo.job.manager/-abstract-manager/suspend.md)| [jvm]  <br>Content  <br>open suspend override fun [suspend](../../tech.whence.echo.job.manager/-abstract-manager/suspend.md)()  <br><br><br>
| [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>


## Properties  
  
|  Name|  Summary| 
|---|---|
| [management](index.md#tech.whence.echo.job.stream.work/SequentialWork/management/#/PointingToDeclaration/)|  [jvm] <br><br>Management 管理<br><br>override val [management](index.md#tech.whence.echo.job.stream.work/SequentialWork/management/#/PointingToDeclaration/): [Management](../../tech.whence.echo.job.manager.management/-management/index.md)   <br>

