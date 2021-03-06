---
title: SupplyingProvider -
---
//[echo](../../index.md)/[tech.whence.echo.job.stream.provider](../index.md)/[SupplyingProvider](index.md)



# SupplyingProvider  
 [jvm] 

指定任务提供者

class [SupplyingProvider](index.md)(**vertx**: Vertx, **name**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), **producer**: [Producer](../../tech.whence.echo.function/-producer/index.md)<[List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[Message](../../tech.whence.echo.job.stream.message/-message/index.md)>>) : [AbstractProvider](../-abstract-provider/index.md)<[Message](../../tech.whence.echo.job.stream.message/-message/index.md)> , [Provider](../-provider/index.md)   


## Constructors  
  
|  Name|  Summary| 
|---|---|
| [SupplyingProvider](-supplying-provider.md)|  [jvm] <br><br><br><br>fun [SupplyingProvider](-supplying-provider.md)(vertx: Vertx, name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), producer: [Producer](../../tech.whence.echo.function/-producer/index.md)<[List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[Message](../../tech.whence.echo.job.stream.message/-message/index.md)>>)   <br>


## Types  
  
|  Name|  Summary| 
|---|---|
| [InnerTask](-inner-task/index.md)| [jvm]  <br>Brief description  <br><br><br>内置任务<br><br>  <br>Content  <br>inner class [InnerTask](-inner-task/index.md)(**message**: [Message](../../tech.whence.echo.job.stream.message/-message/index.md)) : [AbstractTask](../../tech.whence.echo.job.stream.task/-abstract-task/index.md)<[Message](../../tech.whence.echo.job.stream.message/-message/index.md)>   <br><br><br>


## Functions  
  
|  Name|  Summary| 
|---|---|
| [append](index.md#tech.whence.echo.job.stream.provider/AbstractProvider/append/#tech.whence.echo.job.stream.message.Message/PointingToDeclaration/)| [jvm]  <br>Brief description  <br><br><br>附加新消息<br><br>  <br>Content  <br>override fun [append](index.md#tech.whence.echo.job.stream.provider/AbstractProvider/append/#tech.whence.echo.job.stream.message.Message/PointingToDeclaration/)(message: [Message](../../tech.whence.echo.job.stream.message/-message/index.md))  <br><br><br>
| [authorize](../../tech.whence.echo.job.manager/-abstract-manager/authorize.md)| [jvm]  <br>Brief description  <br><br><br>授权<br><br>  <br>Content  <br>open override fun [authorize](../../tech.whence.echo.job.manager/-abstract-manager/authorize.md)(): [Management](../../tech.whence.echo.job.manager.management/-management/index.md)  <br><br><br>
| [close](../-abstract-provider/close.md)| [jvm]  <br>Content  <br>open override fun [close](../-abstract-provider/close.md)(): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[Task](../../tech.whence.echo.job.stream.task/-task/index.md)>?  <br><br><br>
| [contextualize](contextualize.md)| [jvm]  <br>Brief description  <br><br><br>设置上下文<br><br>  <br>Content  <br>open override fun [contextualize](contextualize.md)(context: [Context](../-context/index.md))  <br><br><br>
| [dead](index.md#tech.whence.echo.job.stream.provider/AbstractProvider/dead/#tech.whence.echo.job.stream.message.Message/PointingToDeclaration/)| [jvm]  <br>Brief description  <br><br><br>判断消息是否已失效 若消息已失效或编排器认为其已过期<br><br>  <br>Content  <br>override fun [dead](index.md#tech.whence.echo.job.stream.provider/AbstractProvider/dead/#tech.whence.echo.job.stream.message.Message/PointingToDeclaration/)(message: [Message](../../tech.whence.echo.job.stream.message/-message/index.md)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)| [jvm]  <br>Content  <br>open operator override fun [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [follow](../../tech.whence.echo.job.manager/-abstract-manager/follow.md)| [jvm]  <br>Brief description  <br><br><br>跟随<br><br>  <br>Content  <br>open override fun [follow](../../tech.whence.echo.job.manager/-abstract-manager/follow.md)(leader: [Leader](../../tech.whence.echo.job.manager.management/-leader/index.md))  <br><br><br>
| [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [initialize](../../tech.whence.echo.job.manager/-abstract-manager/initialize.md)| [jvm]  <br>Content  <br>open override fun [initialize](../../tech.whence.echo.job.manager/-abstract-manager/initialize.md)()  <br><br><br>
| [inspect](../../tech.whence.echo.job.manager/-abstract-manager/inspect.md)| [jvm]  <br>Content  <br>open override fun [inspect](../../tech.whence.echo.job.manager/-abstract-manager/inspect.md)(): [State](../../tech.whence.echo.job.manager.state/-state/index.md)  <br><br><br>
| [lead](../../tech.whence.echo.job.manager/-abstract-manager/lead.md)| [jvm]  <br>Brief description  <br><br><br>引导<br><br>  <br>Content  <br>open override fun [lead](../../tech.whence.echo.job.manager/-abstract-manager/lead.md)(follower: [Follower](../../tech.whence.echo.job.manager.management/-follower/index.md))  <br><br><br>
| [monitor](../../tech.whence.echo.job.manager/-abstract-manager/monitor.md)| [jvm]  <br>Brief description  <br><br><br>监听<br><br>  <br>Content  <br>override fun [monitor](../../tech.whence.echo.job.manager/-abstract-manager/monitor.md)(listener: [Listener](../../tech.whence.echo.job.manager/-listener/index.md))  <br><br><br>
| [name](../-abstract-provider/name.md)| [jvm]  <br>Content  <br>open override fun [name](../-abstract-provider/name.md)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>
| [on](../../tech.whence.echo.support.kafka.stream/-stream/index.md#tech.whence.echo.job.manager/AbstractManager/on/#tech.whence.echo.job.manager.Event/PointingToDeclaration/)| [jvm]  <br>Brief description  <br><br><br>接收事件<br><br>  <br>Content  <br>override fun [on](../../tech.whence.echo.support.kafka.stream/-stream/index.md#tech.whence.echo.job.manager/AbstractManager/on/#tech.whence.echo.job.manager.Event/PointingToDeclaration/)(event: [Event](../../tech.whence.echo.job.manager/-event/index.md))  <br><br><br>
| [onAuthorised](../../tech.whence.echo.support.kafka.stream/-stream/index.md#tech.whence.echo.job.manager/AbstractManager/onAuthorised/#tech.whence.echo.job.manager.Event.Stopped/PointingToDeclaration/)| [jvm]  <br>Brief description  <br><br><br>停止服务时<br><br>  <br>Content  <br>override fun [onAuthorised](../../tech.whence.echo.support.kafka.stream/-stream/index.md#tech.whence.echo.job.manager/AbstractManager/onAuthorised/#tech.whence.echo.job.manager.Event.Stopped/PointingToDeclaration/)(event: [Event.Stopped](../../tech.whence.echo.job.manager/-event/-stopped/index.md))  <br><br><br>
| [onFollowed](../../tech.whence.echo.support.kafka.stream/-stream/index.md#tech.whence.echo.job.manager/AbstractManager/onFollowed/#tech.whence.echo.job.manager.Event/PointingToDeclaration/)| [jvm]  <br>Brief description  <br><br><br>跟随着接收事件<br><br>  <br>Content  <br>override fun [onFollowed](../../tech.whence.echo.support.kafka.stream/-stream/index.md#tech.whence.echo.job.manager/AbstractManager/onFollowed/#tech.whence.echo.job.manager.Event/PointingToDeclaration/)(event: [Event](../../tech.whence.echo.job.manager/-event/index.md))  <br><br><br>
| [provide](index.md#tech.whence.echo.job.stream.provider/AbstractProvider/provide/#tech.whence.echo.job.stream.monitor.Monitor#kotlin.Long/PointingToDeclaration/)| [jvm]  <br>Brief description  <br><br><br>生成消息 根据已生成量及可执行时间判断是否可循环 取出消息并处理 若不可继续循环则跳出 若消息不可保存则跳出 否则继续循环 最后返回下次执行间隔<br><br>  <br>Content  <br>override fun [provide](index.md#tech.whence.echo.job.stream.provider/AbstractProvider/provide/#tech.whence.echo.job.stream.monitor.Monitor#kotlin.Long/PointingToDeclaration/)(monitor: [Monitor](../../tech.whence.echo.job.stream.monitor/-monitor/index.md), blockingAt: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)): [Duration](https://docs.oracle.com/javase/8/docs/api/java/time/Duration.html)?  <br><br><br>
| [ready](ready.md)| [jvm]  <br>Brief description  <br><br><br>准备<br><br>  <br>Content  <br>open override fun [ready](ready.md)()  <br><br><br>
| [respond](../-abstract-provider/respond.md)| [jvm]  <br>Content  <br>open override fun [respond](../-abstract-provider/respond.md)()  <br><br><br>
| [resume](../../tech.whence.echo.job.manager/-abstract-manager/resume.md)| [jvm]  <br>Content  <br>open suspend override fun [resume](../../tech.whence.echo.job.manager/-abstract-manager/resume.md)()  <br><br><br>
| [run](index.md#tech.whence.echo.job.stream.provider/AbstractProvider/run/#/PointingToDeclaration/)| [jvm]  <br>Brief description  <br><br><br>在适当条件下生成消息 当前处于存活状态 编排器可用 收集者可读 并返回下次执行间隔<br><br>  <br>Content  <br>override fun [run](index.md#tech.whence.echo.job.stream.provider/AbstractProvider/run/#/PointingToDeclaration/)(): [Duration](https://docs.oracle.com/javase/8/docs/api/java/time/Duration.html)?  <br><br><br>
| [runnable](index.md#tech.whence.echo.job.stream.provider/AbstractProvider/runnable/#kotlin.Int#kotlin.Long/PointingToDeclaration/)| [jvm]  <br>Brief description  <br><br><br>判断是否能继续执行 若当前非存活状态则否 若阻塞时间在过去则否 最后判断消息供给是否足够<br><br>  <br>Content  <br>override fun [runnable](index.md#tech.whence.echo.job.stream.provider/AbstractProvider/runnable/#kotlin.Int#kotlin.Long/PointingToDeclaration/)(provided: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), blockingAt: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [start](../../tech.whence.echo.job.manager/-abstract-manager/start.md)| [jvm]  <br>Content  <br>open suspend override fun [start](../../tech.whence.echo.job.manager/-abstract-manager/start.md)()  <br><br><br>
| [stop](../../tech.whence.echo.job.manager/-abstract-manager/stop.md)| [jvm]  <br>Content  <br>open suspend override fun [stop](../../tech.whence.echo.job.manager/-abstract-manager/stop.md)()  <br><br><br>
| [suspend](../../tech.whence.echo.job.manager/-abstract-manager/suspend.md)| [jvm]  <br>Content  <br>open suspend override fun [suspend](../../tech.whence.echo.job.manager/-abstract-manager/suspend.md)()  <br><br><br>
| [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>


## Properties  
  
|  Name|  Summary| 
|---|---|
| [blockingAt](index.md#tech.whence.echo.job.stream.provider/SupplyingProvider/blockingAt/#/PointingToDeclaration/)|  [jvm] <br><br>Long 阻塞时间<br><br>override var [blockingAt](index.md#tech.whence.echo.job.stream.provider/SupplyingProvider/blockingAt/#/PointingToDeclaration/): [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)   <br>
| [collector](index.md#tech.whence.echo.job.stream.provider/SupplyingProvider/collector/#/PointingToDeclaration/)|  [jvm] <br><br>Collector<M> 收集器<br><br>lateinit override var [collector](index.md#tech.whence.echo.job.stream.provider/SupplyingProvider/collector/#/PointingToDeclaration/): [Collector](../../tech.whence.echo.job.stream.collector/-collector/index.md)<[Message](../../tech.whence.echo.job.stream.message/-message/index.md)>   <br>
| [empty](index.md#tech.whence.echo.job.stream.provider/SupplyingProvider/empty/#/PointingToDeclaration/)|  [jvm] open override val [empty](index.md#tech.whence.echo.job.stream.provider/SupplyingProvider/empty/#/PointingToDeclaration/): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)   <br>
| [idled](index.md#tech.whence.echo.job.stream.provider/SupplyingProvider/idled/#/PointingToDeclaration/)|  [jvm] <br><br>Retrying 等待<br><br>override var [idled](index.md#tech.whence.echo.job.stream.provider/SupplyingProvider/idled/#/PointingToDeclaration/): [Retrying](../../tech.whence.echo.retry/-retrying/index.md)   <br>
| [management](index.md#tech.whence.echo.job.stream.provider/SupplyingProvider/management/#/PointingToDeclaration/)|  [jvm] <br><br>Management 管理<br><br>override val [management](index.md#tech.whence.echo.job.stream.provider/SupplyingProvider/management/#/PointingToDeclaration/): [Management](../../tech.whence.echo.job.manager.management/-management/index.md)   <br>
| [name](index.md#tech.whence.echo.job.stream.provider/SupplyingProvider/name/#/PointingToDeclaration/)|  [jvm] <br><br>String 名称<br><br>override val [name](index.md#tech.whence.echo.job.stream.provider/SupplyingProvider/name/#/PointingToDeclaration/): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)   <br>
| [runAt](index.md#tech.whence.echo.job.stream.provider/SupplyingProvider/runAt/#/PointingToDeclaration/)|  [jvm] <br><br>Long 执行时间<br><br>override var [runAt](index.md#tech.whence.echo.job.stream.provider/SupplyingProvider/runAt/#/PointingToDeclaration/): [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)   <br>
| [size](index.md#tech.whence.echo.job.stream.provider/SupplyingProvider/size/#/PointingToDeclaration/)|  [jvm] @[ExperimentalUnsignedTypes](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-experimental-unsigned-types/index.html)()  <br>  <br>open override val [size](index.md#tech.whence.echo.job.stream.provider/SupplyingProvider/size/#/PointingToDeclaration/): [UInt](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-u-int/index.html)   <br>

