---
title: AbstractProvider -
---
//[echo](../../index.md)/[tech.whence.echo.job.stream.provider](../index.md)/[AbstractProvider](index.md)



# AbstractProvider  
 [jvm] 

抽象消息提供者

abstract class [AbstractProvider](index.md)<[M](index.md) : [Message](../../tech.whence.echo.job.stream.message/-message/index.md)>(**vertx**: Vertx, **name**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)) : [AbstractManager](../../tech.whence.echo.job.manager/-abstract-manager/index.md), [Provider](../-provider/index.md)   


## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| M| <br><br>: Message 消息类型<br><br>
  


## Constructors  
  
|  Name|  Summary| 
|---|---|
| [AbstractProvider](-abstract-provider.md)|  [jvm] <br><br><br><br>fun [AbstractProvider](-abstract-provider.md)(vertx: Vertx, name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html))   <br>


## Functions  
  
|  Name|  Summary| 
|---|---|
| [append](append.md)| [jvm]  <br>Brief description  <br><br><br>附加新消息<br><br>  <br>Content  <br>fun [append](append.md)(message: [M](index.md))  <br><br><br>
| [authorize](../../tech.whence.echo.job.manager/-abstract-manager/authorize.md)| [jvm]  <br>Brief description  <br><br><br>授权<br><br>  <br>Content  <br>open override fun [authorize](../../tech.whence.echo.job.manager/-abstract-manager/authorize.md)(): [Management](../../tech.whence.echo.job.manager.management/-management/index.md)  <br><br><br>
| [close](close.md)| [jvm]  <br>Brief description  <br><br><br>关闭<br><br>  <br>Content  <br>open override fun [close](close.md)(): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[Task](../../tech.whence.echo.job.stream.task/-task/index.md)>?  <br><br><br>
| [contextualize](contextualize.md)| [jvm]  <br>Brief description  <br><br><br>设置上下文<br><br>  <br>Content  <br>open fun [contextualize](contextualize.md)(context: [Context](../-context/index.md))  <br><br><br>
| [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)| [jvm]  <br>Content  <br>open operator override fun [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [follow](../../tech.whence.echo.job.manager/-abstract-manager/follow.md)| [jvm]  <br>Brief description  <br><br><br>跟随<br><br>  <br>Content  <br>open override fun [follow](../../tech.whence.echo.job.manager/-abstract-manager/follow.md)(leader: [Leader](../../tech.whence.echo.job.manager.management/-leader/index.md))  <br><br><br>
| [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [initialize](../../tech.whence.echo.job.manager/-abstract-manager/initialize.md)| [jvm]  <br>Content  <br>open override fun [initialize](../../tech.whence.echo.job.manager/-abstract-manager/initialize.md)()  <br><br><br>
| [inspect](../../tech.whence.echo.job.manager/-abstract-manager/inspect.md)| [jvm]  <br>Content  <br>open override fun [inspect](../../tech.whence.echo.job.manager/-abstract-manager/inspect.md)(): [State](../../tech.whence.echo.job.manager.state/-state/index.md)  <br><br><br>
| [lead](../../tech.whence.echo.job.manager/-abstract-manager/lead.md)| [jvm]  <br>Brief description  <br><br><br>引导<br><br>  <br>Content  <br>open override fun [lead](../../tech.whence.echo.job.manager/-abstract-manager/lead.md)(follower: [Follower](../../tech.whence.echo.job.manager.management/-follower/index.md))  <br><br><br>
| [monitor](../../tech.whence.echo.job.manager/-abstract-manager/monitor.md)| [jvm]  <br>Brief description  <br><br><br>监听<br><br>  <br>Content  <br>override fun [monitor](../../tech.whence.echo.job.manager/-abstract-manager/monitor.md)(listener: [Listener](../../tech.whence.echo.job.manager/-listener/index.md))  <br><br><br>
| [name](name.md)| [jvm]  <br>Brief description  <br><br><br>名称<br><br>  <br>Content  <br>open override fun [name](name.md)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>
| [on](../../tech.whence.echo.support.kafka.stream/-stream/index.md#tech.whence.echo.job.manager/AbstractManager/on/#tech.whence.echo.job.manager.Event/PointingToDeclaration/)| [jvm]  <br>Brief description  <br><br><br>接收事件<br><br>  <br>Content  <br>override fun [on](../../tech.whence.echo.support.kafka.stream/-stream/index.md#tech.whence.echo.job.manager/AbstractManager/on/#tech.whence.echo.job.manager.Event/PointingToDeclaration/)(event: [Event](../../tech.whence.echo.job.manager/-event/index.md))  <br><br><br>
| [onAuthorised](../../tech.whence.echo.support.kafka.stream/-stream/index.md#tech.whence.echo.job.manager/AbstractManager/onAuthorised/#tech.whence.echo.job.manager.Event.Stopped/PointingToDeclaration/)| [jvm]  <br>Brief description  <br><br><br>停止服务时<br><br>  <br>Content  <br>override fun [onAuthorised](../../tech.whence.echo.support.kafka.stream/-stream/index.md#tech.whence.echo.job.manager/AbstractManager/onAuthorised/#tech.whence.echo.job.manager.Event.Stopped/PointingToDeclaration/)(event: [Event.Stopped](../../tech.whence.echo.job.manager/-event/-stopped/index.md))  <br><br><br>
| [onFollowed](../../tech.whence.echo.support.kafka.stream/-stream/index.md#tech.whence.echo.job.manager/AbstractManager/onFollowed/#tech.whence.echo.job.manager.Event/PointingToDeclaration/)| [jvm]  <br>Brief description  <br><br><br>跟随着接收事件<br><br>  <br>Content  <br>override fun [onFollowed](../../tech.whence.echo.support.kafka.stream/-stream/index.md#tech.whence.echo.job.manager/AbstractManager/onFollowed/#tech.whence.echo.job.manager.Event/PointingToDeclaration/)(event: [Event](../../tech.whence.echo.job.manager/-event/index.md))  <br><br><br>
| [ready](ready.md)| [jvm]  <br>Brief description  <br><br><br>准备<br><br>  <br>Content  <br>open override fun [ready](ready.md)()  <br><br><br>
| [respond](respond.md)| [jvm]  <br>Brief description  <br><br><br>响应<br><br>  <br>Content  <br>open override fun [respond](respond.md)()  <br><br><br>
| [resume](../../tech.whence.echo.job.manager/-abstract-manager/resume.md)| [jvm]  <br>Content  <br>open suspend override fun [resume](../../tech.whence.echo.job.manager/-abstract-manager/resume.md)()  <br><br><br>
| [start](../../tech.whence.echo.job.manager/-abstract-manager/start.md)| [jvm]  <br>Content  <br>open suspend override fun [start](../../tech.whence.echo.job.manager/-abstract-manager/start.md)()  <br><br><br>
| [stop](../../tech.whence.echo.job.manager/-abstract-manager/stop.md)| [jvm]  <br>Content  <br>open suspend override fun [stop](../../tech.whence.echo.job.manager/-abstract-manager/stop.md)()  <br><br><br>
| [suspend](../../tech.whence.echo.job.manager/-abstract-manager/suspend.md)| [jvm]  <br>Content  <br>open suspend override fun [suspend](../../tech.whence.echo.job.manager/-abstract-manager/suspend.md)()  <br><br><br>
| [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>


## Properties  
  
|  Name|  Summary| 
|---|---|
| [collector](index.md#tech.whence.echo.job.stream.provider/AbstractProvider/collector/#/PointingToDeclaration/)|  [jvm] <br><br>Collector<M> 收集器<br><br>lateinit var [collector](index.md#tech.whence.echo.job.stream.provider/AbstractProvider/collector/#/PointingToDeclaration/): [Collector](../../tech.whence.echo.job.stream.collector/-collector/index.md)<[M](index.md)>   <br>
| [empty](index.md#tech.whence.echo.job.stream.provider/AbstractProvider/empty/#/PointingToDeclaration/)|  [jvm] <br><br>Boolean 当前容器是否为空<br><br>open override val [empty](index.md#tech.whence.echo.job.stream.provider/AbstractProvider/empty/#/PointingToDeclaration/): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)   <br>
| [management](index.md#tech.whence.echo.job.stream.provider/AbstractProvider/management/#/PointingToDeclaration/)|  [jvm] <br><br>Management 管理<br><br>override val [management](index.md#tech.whence.echo.job.stream.provider/AbstractProvider/management/#/PointingToDeclaration/): [Management](../../tech.whence.echo.job.manager.management/-management/index.md)   <br>
| [size](index.md#tech.whence.echo.job.stream.provider/AbstractProvider/size/#/PointingToDeclaration/)|  [jvm] <br><br>UInt 当前容器总数据量<br><br>@[ExperimentalUnsignedTypes](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-experimental-unsigned-types/index.html)()  <br>  <br>open override val [size](index.md#tech.whence.echo.job.stream.provider/AbstractProvider/size/#/PointingToDeclaration/): [UInt](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-u-int/index.html)   <br>


## Inheritors  
  
|  Name| 
|---|
| [MessagingProvider](../-messaging-provider/index.md)
| [RetryingProvider](../-retrying-provider/index.md)
| [SupplyingProvider](../-supplying-provider/index.md)

