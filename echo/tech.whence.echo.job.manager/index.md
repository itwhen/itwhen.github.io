---
title: tech.whence.echo.job.manager -
---
//[echo](../index.md)/[tech.whence.echo.job.manager](index.md)



# Package tech.whence.echo.job.manager  


## Types  
  
|  Name|  Summary| 
|---|---|
| [AbstractManager](-abstract-manager/index.md)| [jvm]  <br>Brief description  <br><br><br>管理器抽象<br><br>  <br>Content  <br>abstract class [AbstractManager](-abstract-manager/index.md)(**vertx**: Vertx) : [Manager](-manager/index.md), [Leader](../tech.whence.echo.job.manager.management/-leader/index.md), [Follower](../tech.whence.echo.job.manager.management/-follower/index.md)  <br><br><br>
| [DefaultManager](-default-manager/index.md)| [jvm]  <br>Brief description  <br><br><br>默认管理器<br><br>  <br>Content  <br>class [DefaultManager](-default-manager/index.md)(**vertx**: Vertx) : [AbstractManager](-abstract-manager/index.md)  <br><br><br>
| [Event](-event/index.md)| [jvm]  <br>Brief description  <br><br><br>事件<br><br>  <br>Content  <br>sealed class [Event](-event/index.md) : [AbstractEvent](../tech.whence.echo.event/-abstract-event/index.md)<[State](../tech.whence.echo.job.manager.state/-state/index.md)>   <br><br><br>
| [Listener](-listener/index.md)| [jvm]  <br>Brief description  <br><br><br>监听器<br><br>  <br>Content  <br>fun fun interface [Listener](-listener/index.md)  <br><br><br>
| [Manager](-manager/index.md)| [jvm]  <br>Brief description  <br><br><br>管理器<br><br>  <br>Content  <br>interface [Manager](-manager/index.md) : [Namer](../tech.whence.echo.definition/-namer/index.md)  <br><br><br>
| [Operation](-operation/index.md)| [jvm]  <br>Brief description  <br><br><br>操作<br><br>  <br>Content  <br>enum [Operation](-operation/index.md) : [Enum](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-enum/index.html)<[Operation](-operation/index.md)>   <br><br><br>

