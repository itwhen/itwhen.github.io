---
title: tech.whence.echo.job.stream.provider -
---
//[echo](../index.md)/[tech.whence.echo.job.stream.provider](index.md)



# Package tech.whence.echo.job.stream.provider  


## Types  
  
|  Name|  Summary| 
|---|---|
| [AbstractProvider](-abstract-provider/index.md)| [jvm]  <br>Brief description  <br><br><br>抽象消息提供者<br><br>  <br>Content  <br>abstract class [AbstractProvider](-abstract-provider/index.md)<[M](-abstract-provider/index.md) : [Message](../tech.whence.echo.job.stream.message/-message/index.md)>(**vertx**: Vertx, **name**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)) : [AbstractManager](../tech.whence.echo.job.manager/-abstract-manager/index.md), [Provider](-provider/index.md)  <br><br><br>
| [Context](-context/index.md)| [jvm]  <br>Brief description  <br><br><br>运行上下文<br><br>  <br>Content  <br>class [Context](-context/index.md)  <br><br><br>
| [MessagingProvider](-messaging-provider/index.md)| [jvm]  <br>Brief description  <br><br><br>普通任务提供者<br><br>  <br>Content  <br>class [MessagingProvider](-messaging-provider/index.md)(**vertx**: Vertx, **messager**: [MessagingProvider.Messager](-messaging-provider/-messager/index.md), **stamp**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?) : [AbstractProvider](-abstract-provider/index.md)<[Message](../tech.whence.echo.job.stream.message/-message/index.md)> , [Provider](-provider/index.md)  <br><br><br>
| [Provider](-provider/index.md)| [jvm]  <br>Brief description  <br><br><br>数据提供者<br><br>  <br>Content  <br>interface [Provider](-provider/index.md) : [Manager](../tech.whence.echo.job.manager/-manager/index.md), [Container](../tech.whence.echo.container/-container/index.md)  <br><br><br>
| [Responder](-responder/index.md)| [jvm]  <br>Brief description  <br><br><br>响应器<br><br>  <br>Content  <br>fun fun interface [Responder](-responder/index.md)  <br><br><br>
| [RetryingProvider](-retrying-provider/index.md)| [jvm]  <br>Brief description  <br><br><br>重试任务提供者 默认重试=退火间隔30秒重试3次<br><br>  <br>Content  <br>class [RetryingProvider](-retrying-provider/index.md)(**vertx**: Vertx, **retry**: [Retry](../tech.whence.echo.retry/-retry/index.md)?) : [AbstractProvider](-abstract-provider/index.md)<[RetryingProvider.InnerTask](-retrying-provider/-inner-task/index.md)> , [Provider](-provider/index.md)  <br><br><br>
| [Stage](-stage/index.md)| [jvm]  <br>Brief description  <br><br><br>提供者阶段<br><br>  <br>Content  <br>enum [Stage](-stage/index.md) : [Enum](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-enum/index.html)<[Stage](-stage/index.md)>   <br><br><br>
| [Store](-store/index.md)| [jvm]  <br>Brief description  <br><br><br>消息存储器<br><br>  <br>Content  <br>class [Store](-store/index.md) : [Container](../tech.whence.echo.container/-container/index.md)  <br><br><br>
| [SupplyingProvider](-supplying-provider/index.md)| [jvm]  <br>Brief description  <br><br><br>指定任务提供者<br><br>  <br>Content  <br>class [SupplyingProvider](-supplying-provider/index.md)(**vertx**: Vertx, **name**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), **producer**: [Producer](../tech.whence.echo.function/-producer/index.md)<[List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[Message](../tech.whence.echo.job.stream.message/-message/index.md)>>) : [AbstractProvider](-abstract-provider/index.md)<[Message](../tech.whence.echo.job.stream.message/-message/index.md)> , [Provider](-provider/index.md)  <br><br><br>

