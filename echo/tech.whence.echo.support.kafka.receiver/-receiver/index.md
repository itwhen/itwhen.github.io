---
title: Receiver -
---
//[echo](../../index.md)/[tech.whence.echo.support.kafka.receiver](../index.md)/[Receiver](index.md)



# Receiver  
 [jvm] 

接收器

class [Receiver](index.md)(**vertx**: Vertx, **source**: [DataSource](../-data-source/index.md), **subscription**: [Subscription](../../tech.whence.echo.job.stream.subscription/-subscription/index.md)) : [AbstractManager](../../tech.whence.echo.job.manager/-abstract-manager/index.md)   


## Constructors  
  
|  Name|  Summary| 
|---|---|
| [Receiver](-receiver.md)|  [jvm] <br><br><br><br>fun [Receiver](-receiver.md)(vertx: Vertx, source: [DataSource](../-data-source/index.md), subscription: [Subscription](../../tech.whence.echo.job.stream.subscription/-subscription/index.md))   <br>


## Functions  
  
|  Name|  Summary| 
|---|---|
| [authorize](../../tech.whence.echo.job.manager/-abstract-manager/authorize.md)| [jvm]  <br>Brief description  <br><br><br>授权<br><br>  <br>Content  <br>open override fun [authorize](../../tech.whence.echo.job.manager/-abstract-manager/authorize.md)(): [Management](../../tech.whence.echo.job.manager.management/-management/index.md)  <br><br><br>
| [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)| [jvm]  <br>Content  <br>open operator override fun [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [follow](../../tech.whence.echo.job.manager/-abstract-manager/follow.md)| [jvm]  <br>Brief description  <br><br><br>跟随<br><br>  <br>Content  <br>open override fun [follow](../../tech.whence.echo.job.manager/-abstract-manager/follow.md)(leader: [Leader](../../tech.whence.echo.job.manager.management/-leader/index.md))  <br><br><br>
| [group](group.md)| [jvm]  <br>Brief description  <br><br><br>设置分组<br><br>  <br>Content  <br>fun [group](group.md)(group: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): [Receiver](index.md)  <br><br><br>
| [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [initialize](../../tech.whence.echo.job.manager/-abstract-manager/initialize.md)| [jvm]  <br>Brief description  <br><br><br>初始化<br><br>  <br>Content  <br>open override fun [initialize](../../tech.whence.echo.job.manager/-abstract-manager/initialize.md)()  <br><br><br>
| [inspect](../../tech.whence.echo.job.manager/-abstract-manager/inspect.md)| [jvm]  <br>Brief description  <br><br><br>查看状态<br><br>  <br>Content  <br>open override fun [inspect](../../tech.whence.echo.job.manager/-abstract-manager/inspect.md)(): [State](../../tech.whence.echo.job.manager.state/-state/index.md)  <br><br><br>
| [laten](laten.md)| [jvm]  <br>Brief description  <br><br><br>设置延迟<br><br>  <br>Content  <br>fun [laten](laten.md)(latency: [Duration](https://docs.oracle.com/javase/8/docs/api/java/time/Duration.html)): [Receiver](index.md)  <br><br><br>
| [lead](../../tech.whence.echo.job.manager/-abstract-manager/lead.md)| [jvm]  <br>Brief description  <br><br><br>引导<br><br>  <br>Content  <br>open override fun [lead](../../tech.whence.echo.job.manager/-abstract-manager/lead.md)(follower: [Follower](../../tech.whence.echo.job.manager.management/-follower/index.md))  <br><br><br>
| [limit](limit.md)| [jvm]  <br>Brief description  <br><br><br>设置消费限制<br><br>  <br>Content  <br>fun [limit](limit.md)(limit: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)): [Receiver](index.md)  <br><br><br>
| [listen](listen.md)| [jvm]  <br>Brief description  <br><br><br>设置回调<br><br>  <br>Content  <br>fun [listen](listen.md)(callback: [Consumer](../../tech.whence.echo.function/-consumer/index.md)<[List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[Result](../-result/index.md)>>): [Receiver](index.md)  <br><br><br>
| [monitor](../../tech.whence.echo.job.manager/-abstract-manager/monitor.md)| [jvm]  <br>Brief description  <br><br><br>监听<br><br>  <br>Content  <br>override fun [monitor](../../tech.whence.echo.job.manager/-abstract-manager/monitor.md)(listener: [Listener](../../tech.whence.echo.job.manager/-listener/index.md))  <br><br><br>
| [name](name.md)| [jvm]  <br>Brief description  <br><br><br>名称<br><br>  <br>Content  <br>open override fun [name](name.md)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>
| [on](../../tech.whence.echo.support.kafka.stream/-stream/index.md#tech.whence.echo.job.manager/AbstractManager/on/#tech.whence.echo.job.manager.Event/PointingToDeclaration/)| [jvm]  <br>Brief description  <br><br><br>接收事件<br><br>  <br>Content  <br>override fun [on](../../tech.whence.echo.support.kafka.stream/-stream/index.md#tech.whence.echo.job.manager/AbstractManager/on/#tech.whence.echo.job.manager.Event/PointingToDeclaration/)(event: [Event](../../tech.whence.echo.job.manager/-event/index.md))  <br><br><br>
| [onAuthorised](../../tech.whence.echo.support.kafka.stream/-stream/index.md#tech.whence.echo.job.manager/AbstractManager/onAuthorised/#tech.whence.echo.job.manager.Event.Stopped/PointingToDeclaration/)| [jvm]  <br>Brief description  <br><br><br>停止服务时<br><br>  <br>Content  <br>override fun [onAuthorised](../../tech.whence.echo.support.kafka.stream/-stream/index.md#tech.whence.echo.job.manager/AbstractManager/onAuthorised/#tech.whence.echo.job.manager.Event.Stopped/PointingToDeclaration/)(event: [Event.Stopped](../../tech.whence.echo.job.manager/-event/-stopped/index.md))  <br><br><br>
| [onFollowed](../../tech.whence.echo.support.kafka.stream/-stream/index.md#tech.whence.echo.job.manager/AbstractManager/onFollowed/#tech.whence.echo.job.manager.Event/PointingToDeclaration/)| [jvm]  <br>Brief description  <br><br><br>跟随着接收事件<br><br>  <br>Content  <br>override fun [onFollowed](../../tech.whence.echo.support.kafka.stream/-stream/index.md#tech.whence.echo.job.manager/AbstractManager/onFollowed/#tech.whence.echo.job.manager.Event/PointingToDeclaration/)(event: [Event](../../tech.whence.echo.job.manager/-event/index.md))  <br><br><br>
| [resume](../../tech.whence.echo.job.manager/-abstract-manager/resume.md)| [jvm]  <br>Brief description  <br><br><br>恢复<br><br>  <br>Content  <br>open suspend override fun [resume](../../tech.whence.echo.job.manager/-abstract-manager/resume.md)()  <br><br><br>
| [start](../../tech.whence.echo.job.manager/-abstract-manager/start.md)| [jvm]  <br>Brief description  <br><br><br>启动<br><br>  <br>Content  <br>open suspend override fun [start](../../tech.whence.echo.job.manager/-abstract-manager/start.md)()  <br><br><br>
| [stop](../../tech.whence.echo.job.manager/-abstract-manager/stop.md)| [jvm]  <br>Brief description  <br><br><br>停止<br><br>  <br>Content  <br>open suspend override fun [stop](../../tech.whence.echo.job.manager/-abstract-manager/stop.md)()  <br><br><br>
| [suspend](../../tech.whence.echo.job.manager/-abstract-manager/suspend.md)| [jvm]  <br>Brief description  <br><br><br>挂起<br><br>  <br>Content  <br>open suspend override fun [suspend](../../tech.whence.echo.job.manager/-abstract-manager/suspend.md)()  <br><br><br>
| [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>


## Properties  
  
|  Name|  Summary| 
|---|---|
| [management](index.md#tech.whence.echo.support.kafka.receiver/Receiver/management/#/PointingToDeclaration/)|  [jvm] <br><br>Management 管理<br><br>override val [management](index.md#tech.whence.echo.support.kafka.receiver/Receiver/management/#/PointingToDeclaration/): [Management](../../tech.whence.echo.job.manager.management/-management/index.md)   <br>

