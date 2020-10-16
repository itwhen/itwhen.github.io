---
title: Stream -
---
//[echo](../../index.md)/[tech.whence.echo.support.kafka.stream](../index.md)/[Stream](index.md)



# Stream  
 [jvm] 

消息流

class [Stream](index.md)(**vertx**: Vertx, **source**: [DataSource](../-data-source/index.md), **subscription**: [Subscription](../../tech.whence.echo.job.stream.subscription/-subscription/index.md)) : [AbstractManager](../../tech.whence.echo.job.manager/-abstract-manager/index.md), [MessagingProvider.Messager](../../tech.whence.echo.job.stream.provider/-messaging-provider/-messager/index.md)   


## Constructors  
  
|  Name|  Summary| 
|---|---|
| [Stream](-stream.md)|  [jvm] <br><br><br><br>fun [Stream](-stream.md)(vertx: Vertx, source: [DataSource](../-data-source/index.md), subscription: [Subscription](../../tech.whence.echo.job.stream.subscription/-subscription/index.md))   <br>


## Functions  
  
|  Name|  Summary| 
|---|---|
| [authorize](../../tech.whence.echo.job.manager/-abstract-manager/authorize.md)| [jvm]  <br>Brief description  <br><br><br>授权<br><br>  <br>Content  <br>open override fun [authorize](../../tech.whence.echo.job.manager/-abstract-manager/authorize.md)(): [Management](../../tech.whence.echo.job.manager.management/-management/index.md)  <br><br><br>
| [bulk](bulk.md)| [jvm]  <br>Brief description  <br><br><br>设置处理线程数<br><br>  <br>Content  <br>fun [bulk](bulk.md)(count: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [Stream](index.md)  <br><br><br>
| [close](../../tech.whence.echo.job.stream.provider/-messaging-provider/-messager/close.md)| [jvm]  <br>Brief description  <br><br><br>关闭<br><br>  <br>Content  <br>open override fun [close](../../tech.whence.echo.job.stream.provider/-messaging-provider/-messager/close.md)()  <br><br><br>
| [configure](configure.md)| [jvm]  <br>Brief description  <br><br><br>配置<br><br>  <br>Content  <br>fun [configure](configure.md)(config: [Accessor](../../tech.whence.echo.container.accessor/-accessor/index.md)?): [Stream](index.md)  <br>fun [configure](configure.md)(key: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), value: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)): [Stream](index.md)  <br><br><br>
| [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)| [jvm]  <br>Content  <br>open operator override fun [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [exceptionally](exceptionally.md)| [jvm]  <br>Brief description  <br><br><br>设置异常处理器<br><br>  <br>Content  <br>fun [exceptionally](exceptionally.md)(handler: [Thread.UncaughtExceptionHandler](https://docs.oracle.com/javase/8/docs/api/java/lang/Thread.UncaughtExceptionHandler.html)): [Stream](index.md)  <br><br><br>
| [follow](../../tech.whence.echo.job.manager/-abstract-manager/follow.md)| [jvm]  <br>Brief description  <br><br><br>跟随<br><br>  <br>Content  <br>open override fun [follow](../../tech.whence.echo.job.manager/-abstract-manager/follow.md)(leader: [Leader](../../tech.whence.echo.job.manager.management/-leader/index.md))  <br><br><br>
| [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [identify](identify.md)| [jvm]  <br>Brief description  <br><br><br>标记<br><br>  <br>Content  <br>fun [identify](identify.md)(name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): [Stream](index.md)  <br><br><br>
| [initialize](../../tech.whence.echo.job.manager/-abstract-manager/initialize.md)| [jvm]  <br>Brief description  <br><br><br>初始化<br><br>  <br>Content  <br>open override fun [initialize](../../tech.whence.echo.job.manager/-abstract-manager/initialize.md)()  <br><br><br>
| [inspect](../../tech.whence.echo.job.manager/-abstract-manager/inspect.md)| [jvm]  <br>Brief description  <br><br><br>查看状态<br><br>  <br>Content  <br>open override fun [inspect](../../tech.whence.echo.job.manager/-abstract-manager/inspect.md)(): [State](../../tech.whence.echo.job.manager.state/-state/index.md)  <br><br><br>
| [lead](../../tech.whence.echo.job.manager/-abstract-manager/lead.md)| [jvm]  <br>Brief description  <br><br><br>引导<br><br>  <br>Content  <br>open override fun [lead](../../tech.whence.echo.job.manager/-abstract-manager/lead.md)(follower: [Follower](../../tech.whence.echo.job.manager.management/-follower/index.md))  <br><br><br>
| [listen](listen.md)| [jvm]  <br>Brief description  <br><br><br>设置状态监听器<br><br>  <br>Content  <br>fun [listen](listen.md)(listener: KafkaStreams.StateListener): [Stream](index.md)  <br><br><br>
| [locate](locate.md)| [jvm]  <br>Brief description  <br><br><br>定位服务<br><br>  <br>Content  <br>fun [locate](locate.md)(host: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), port: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [Stream](index.md)  <br><br><br>
| [monitor](../../tech.whence.echo.job.manager/-abstract-manager/monitor.md)| [jvm]  <br>Brief description  <br><br><br>监听<br><br>  <br>Content  <br>override fun [monitor](../../tech.whence.echo.job.manager/-abstract-manager/monitor.md)(listener: [Listener](../../tech.whence.echo.job.manager/-listener/index.md))  <br><br><br>
| [name](name.md)| [jvm]  <br>Brief description  <br><br><br>名称<br><br>  <br>Content  <br>open override fun [name](name.md)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>
| [on](index.md#tech.whence.echo.job.manager/AbstractManager/on/#tech.whence.echo.job.manager.Event/PointingToDeclaration/)| [jvm]  <br>Brief description  <br><br><br>接收事件<br><br>  <br>Content  <br>override fun [on](index.md#tech.whence.echo.job.manager/AbstractManager/on/#tech.whence.echo.job.manager.Event/PointingToDeclaration/)(event: [Event](../../tech.whence.echo.job.manager/-event/index.md))  <br><br><br>
| [onAuthorised](index.md#tech.whence.echo.job.manager/AbstractManager/onAuthorised/#tech.whence.echo.job.manager.Event.Stopped/PointingToDeclaration/)| [jvm]  <br>Brief description  <br><br><br>停止服务时<br><br>  <br>Content  <br>override fun [onAuthorised](index.md#tech.whence.echo.job.manager/AbstractManager/onAuthorised/#tech.whence.echo.job.manager.Event.Stopped/PointingToDeclaration/)(event: [Event.Stopped](../../tech.whence.echo.job.manager/-event/-stopped/index.md))  <br><br><br>
| [onFollowed](index.md#tech.whence.echo.job.manager/AbstractManager/onFollowed/#tech.whence.echo.job.manager.Event/PointingToDeclaration/)| [jvm]  <br>Brief description  <br><br><br>跟随着接收事件<br><br>  <br>Content  <br>override fun [onFollowed](index.md#tech.whence.echo.job.manager/AbstractManager/onFollowed/#tech.whence.echo.job.manager.Event/PointingToDeclaration/)(event: [Event](../../tech.whence.echo.job.manager/-event/index.md))  <br><br><br>
| [prepare](prepare.md)| [jvm]  <br>Brief description  <br><br><br>预备<br><br>  <br>Content  <br>open override fun [prepare](prepare.md)(provider: [MessagingProvider](../../tech.whence.echo.job.stream.provider/-messaging-provider/index.md), logger: KLogger?, exceptionHandler: [Thread.UncaughtExceptionHandler](https://docs.oracle.com/javase/8/docs/api/java/lang/Thread.UncaughtExceptionHandler.html), listener: [Listener](../../tech.whence.echo.job.manager/-listener/index.md))  <br><br><br>
| [process](process.md)| [jvm]  <br>Brief description  <br><br><br>设置初始化器<br><br>  <br>Content  <br>fun [process](process.md)(initializer: [Initializer](../../tech.whence.echo.support.kafka.stream.initializer/-initializer/index.md)): [Stream](index.md)  <br><br><br>
| [resume](../../tech.whence.echo.job.manager/-abstract-manager/resume.md)| [jvm]  <br>Brief description  <br><br><br>恢复<br><br>  <br>Content  <br>open suspend override fun [resume](../../tech.whence.echo.job.manager/-abstract-manager/resume.md)()  <br><br><br>
| [start](../../tech.whence.echo.job.manager/-abstract-manager/start.md)| [jvm]  <br>Brief description  <br><br><br>启动<br><br>  <br>Content  <br>open suspend override fun [start](../../tech.whence.echo.job.manager/-abstract-manager/start.md)()  <br><br><br>
| [stop](../../tech.whence.echo.job.manager/-abstract-manager/stop.md)| [jvm]  <br>Brief description  <br><br><br>停止<br><br>  <br>Content  <br>open suspend override fun [stop](../../tech.whence.echo.job.manager/-abstract-manager/stop.md)()  <br><br><br>
| [suspend](../../tech.whence.echo.job.manager/-abstract-manager/suspend.md)| [jvm]  <br>Brief description  <br><br><br>挂起<br><br>  <br>Content  <br>open suspend override fun [suspend](../../tech.whence.echo.job.manager/-abstract-manager/suspend.md)()  <br><br><br>
| [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>


## Properties  
  
|  Name|  Summary| 
|---|---|
| [management](index.md#tech.whence.echo.support.kafka.stream/Stream/management/#/PointingToDeclaration/)|  [jvm] <br><br>Management 管理<br><br>override val [management](index.md#tech.whence.echo.support.kafka.stream/Stream/management/#/PointingToDeclaration/): [Management](../../tech.whence.echo.job.manager.management/-management/index.md)   <br>

