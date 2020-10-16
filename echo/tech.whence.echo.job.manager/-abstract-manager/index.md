---
title: AbstractManager -
---
//[echo](../../index.md)/[tech.whence.echo.job.manager](../index.md)/[AbstractManager](index.md)



# AbstractManager  
 [jvm] 

管理器抽象

abstract class [AbstractManager](index.md)(**vertx**: Vertx) : [Manager](../-manager/index.md), [Leader](../../tech.whence.echo.job.manager.management/-leader/index.md), [Follower](../../tech.whence.echo.job.manager.management/-follower/index.md)   


## Constructors  
  
|  Name|  Summary| 
|---|---|
| [AbstractManager](-abstract-manager.md)|  [jvm] <br><br><br><br>fun [AbstractManager](-abstract-manager.md)(vertx: Vertx)   <br>


## Functions  
  
|  Name|  Summary| 
|---|---|
| [authorize](authorize.md)| [jvm]  <br>Brief description  <br><br><br>授权<br><br>  <br>Content  <br>open override fun [authorize](authorize.md)(): [Management](../../tech.whence.echo.job.manager.management/-management/index.md)  <br><br><br>
| [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)| [jvm]  <br>Content  <br>open operator override fun [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [follow](follow.md)| [jvm]  <br>Brief description  <br><br><br>跟随<br><br>  <br>Content  <br>open override fun [follow](follow.md)(leader: [Leader](../../tech.whence.echo.job.manager.management/-leader/index.md))  <br><br><br>
| [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [initialize](initialize.md)| [jvm]  <br>Brief description  <br><br><br>初始化<br><br>  <br>Content  <br>open override fun [initialize](initialize.md)()  <br><br><br>
| [inspect](inspect.md)| [jvm]  <br>Brief description  <br><br><br>查看状态<br><br>  <br>Content  <br>open override fun [inspect](inspect.md)(): [State](../../tech.whence.echo.job.manager.state/-state/index.md)  <br><br><br>
| [lead](lead.md)| [jvm]  <br>Brief description  <br><br><br>引导<br><br>  <br>Content  <br>open override fun [lead](lead.md)(follower: [Follower](../../tech.whence.echo.job.manager.management/-follower/index.md))  <br><br><br>
| [monitor](monitor.md)| [jvm]  <br>Brief description  <br><br><br>监听<br><br>  <br>Content  <br>fun [monitor](monitor.md)(listener: [Listener](../-listener/index.md))  <br><br><br>
| [name](../../tech.whence.echo.definition/-namer/name.md)| [jvm]  <br>Brief description  <br><br><br>名称<br><br>  <br>Content  <br>abstract override fun [name](../../tech.whence.echo.definition/-namer/name.md)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>
| [resume](resume.md)| [jvm]  <br>Brief description  <br><br><br>恢复<br><br>  <br>Content  <br>open suspend override fun [resume](resume.md)()  <br><br><br>
| [start](start.md)| [jvm]  <br>Brief description  <br><br><br>启动<br><br>  <br>Content  <br>open suspend override fun [start](start.md)()  <br><br><br>
| [stop](stop.md)| [jvm]  <br>Brief description  <br><br><br>停止<br><br>  <br>Content  <br>open suspend override fun [stop](stop.md)()  <br><br><br>
| [suspend](suspend.md)| [jvm]  <br>Brief description  <br><br><br>挂起<br><br>  <br>Content  <br>open suspend override fun [suspend](suspend.md)()  <br><br><br>
| [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>


## Properties  
  
|  Name|  Summary| 
|---|---|
| [management](index.md#tech.whence.echo.job.manager/AbstractManager/management/#/PointingToDeclaration/)|  [jvm] <br><br>Management 管理<br><br>val [management](index.md#tech.whence.echo.job.manager/AbstractManager/management/#/PointingToDeclaration/): [Management](../../tech.whence.echo.job.manager.management/-management/index.md)   <br>


## Inheritors  
  
|  Name| 
|---|
| [DefaultManager](../-default-manager/index.md)
| [AbstractProvider](../../tech.whence.echo.job.stream.provider/-abstract-provider/index.md)
| [AbstractWork](../../tech.whence.echo.job.stream.work/-abstract-work/index.md)
| [Receiver](../../tech.whence.echo.support.kafka.receiver/-receiver/index.md)
| [Stream](../../tech.whence.echo.support.kafka.stream/-stream/index.md)

