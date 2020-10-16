---
title: DefaultManager -
---
//[echo](../../index.md)/[tech.whence.echo.job.manager](../index.md)/[DefaultManager](index.md)



# DefaultManager  
 [jvm] 

默认管理器

class [DefaultManager](index.md)(**vertx**: Vertx) : [AbstractManager](../-abstract-manager/index.md)   


## Constructors  
  
|  Name|  Summary| 
|---|---|
| [DefaultManager](-default-manager.md)|  [jvm] <br><br><br><br>fun [DefaultManager](-default-manager.md)(vertx: Vertx)   <br>


## Functions  
  
|  Name|  Summary| 
|---|---|
| [authorize](../-abstract-manager/authorize.md)| [jvm]  <br>Brief description  <br><br><br>授权<br><br>  <br>Content  <br>open override fun [authorize](../-abstract-manager/authorize.md)(): [Management](../../tech.whence.echo.job.manager.management/-management/index.md)  <br><br><br>
| [dispatch](dispatch.md)| [jvm]  <br>Brief description  <br><br><br>调度<br><br>  <br>Content  <br>fun [dispatch](dispatch.md)()  <br>fun [dispatch](dispatch.md)(delay: [Duration](https://docs.oracle.com/javase/8/docs/api/java/time/Duration.html))  <br>fun [dispatch](dispatch.md)(times: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html))  <br><br><br>
| [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)| [jvm]  <br>Content  <br>open operator override fun [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [follow](../-abstract-manager/follow.md)| [jvm]  <br>Brief description  <br><br><br>跟随<br><br>  <br>Content  <br>open override fun [follow](../-abstract-manager/follow.md)(leader: [Leader](../../tech.whence.echo.job.manager.management/-leader/index.md))  <br><br><br>
| [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [initialize](../-abstract-manager/initialize.md)| [jvm]  <br>Brief description  <br><br><br>初始化<br><br>  <br>Content  <br>open override fun [initialize](../-abstract-manager/initialize.md)()  <br><br><br>
| [inspect](../-abstract-manager/inspect.md)| [jvm]  <br>Brief description  <br><br><br>查看状态<br><br>  <br>Content  <br>open override fun [inspect](../-abstract-manager/inspect.md)(): [State](../../tech.whence.echo.job.manager.state/-state/index.md)  <br><br><br>
| [lead](../-abstract-manager/lead.md)| [jvm]  <br>Brief description  <br><br><br>引导<br><br>  <br>Content  <br>open override fun [lead](../-abstract-manager/lead.md)(follower: [Follower](../../tech.whence.echo.job.manager.management/-follower/index.md))  <br><br><br>
| [monitor](../-abstract-manager/monitor.md)| [jvm]  <br>Brief description  <br><br><br>监听<br><br>  <br>Content  <br>override fun [monitor](../-abstract-manager/monitor.md)(listener: [Listener](../-listener/index.md))  <br><br><br>
| [name](name.md)| [jvm]  <br>Brief description  <br><br><br>名称<br><br>  <br>Content  <br>open override fun [name](name.md)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>
| [onAuthorised](../../tech.whence.echo.support.kafka.stream/-stream/index.md#tech.whence.echo.job.manager/AbstractManager/onAuthorised/#tech.whence.echo.job.manager.Event.Stopped/PointingToDeclaration/)| [jvm]  <br>Brief description  <br><br><br>停止服务时<br><br>  <br>Content  <br>override fun [onAuthorised](../../tech.whence.echo.support.kafka.stream/-stream/index.md#tech.whence.echo.job.manager/AbstractManager/onAuthorised/#tech.whence.echo.job.manager.Event.Stopped/PointingToDeclaration/)(event: [Event.Stopped](../-event/-stopped/index.md))  <br><br><br>
| [onFollowed](../../tech.whence.echo.support.kafka.stream/-stream/index.md#tech.whence.echo.job.manager/AbstractManager/onFollowed/#tech.whence.echo.job.manager.Event/PointingToDeclaration/)| [jvm]  <br>Brief description  <br><br><br>跟随着接收事件<br><br>  <br>Content  <br>override fun [onFollowed](../../tech.whence.echo.support.kafka.stream/-stream/index.md#tech.whence.echo.job.manager/AbstractManager/onFollowed/#tech.whence.echo.job.manager.Event/PointingToDeclaration/)(event: [Event](../-event/index.md))  <br><br><br>
| [resume](../-abstract-manager/resume.md)| [jvm]  <br>Brief description  <br><br><br>恢复<br><br>  <br>Content  <br>open suspend override fun [resume](../-abstract-manager/resume.md)()  <br><br><br>
| [start](../-abstract-manager/start.md)| [jvm]  <br>Brief description  <br><br><br>启动<br><br>  <br>Content  <br>open suspend override fun [start](../-abstract-manager/start.md)()  <br><br><br>
| [stop](../-abstract-manager/stop.md)| [jvm]  <br>Brief description  <br><br><br>停止<br><br>  <br>Content  <br>open suspend override fun [stop](../-abstract-manager/stop.md)()  <br><br><br>
| [suspend](../-abstract-manager/suspend.md)| [jvm]  <br>Brief description  <br><br><br>挂起<br><br>  <br>Content  <br>open suspend override fun [suspend](../-abstract-manager/suspend.md)()  <br><br><br>
| [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>


## Properties  
  
|  Name|  Summary| 
|---|---|
| [management](index.md#tech.whence.echo.job.manager/DefaultManager/management/#/PointingToDeclaration/)|  [jvm] <br><br>Management 管理<br><br>override val [management](index.md#tech.whence.echo.job.manager/DefaultManager/management/#/PointingToDeclaration/): [Management](../../tech.whence.echo.job.manager.management/-management/index.md)   <br>

