---
title: tech.whence.echo.rpc -
---
//[echo](../index.md)/[tech.whence.echo.rpc](index.md)



# Package tech.whence.echo.rpc  


## Types  
  
|  Name|  Summary| 
|---|---|
| [AbstractAdapter](-abstract-adapter/index.md)| [jvm]  <br>Brief description  <br><br><br>适配抽象<br><br>  <br>Content  <br>abstract class [AbstractAdapter](-abstract-adapter/index.md)<[F](-abstract-adapter/index.md) : [Facade](-facade/index.md)>(**facade**: [F](-abstract-adapter/index.md)) : [Api](-api/index.md)<[F](-abstract-adapter/index.md)>   <br><br><br>
| [AbstractService](-abstract-service/index.md)| [jvm]  <br>Brief description  <br><br><br>抽象服务<br><br>  <br>Content  <br>abstract class [AbstractService](-abstract-service/index.md)<[T](-abstract-service/index.md) : [AbstractService](-abstract-service/index.md)<[T](-abstract-service/index.md)>> : [Reference](../tech.whence.echo.type/-reference/index.md)<[T](-abstract-service/index.md)>   <br><br><br>
| [Api](-api/index.md)| [jvm]  <br>Brief description  <br><br><br>对外API<br><br>  <br>Content  <br>interface [Api](-api/index.md)<[F](-api/index.md) : [Facade](-facade/index.md)>  <br><br><br>
| [Contractor](-contractor/index.md)| [jvm]  <br>Brief description  <br><br><br>对外契约<br><br>  <br>Content  <br>interface [Contractor](-contractor/index.md)  <br><br><br>
| [Deployer](-deployer/index.md)| [jvm]  <br>Brief description  <br><br><br>部署器<br><br>  <br>Content  <br>class [Deployer](-deployer/index.md)  <br><br><br>
| [Facade](-facade/index.md)| [jvm]  <br>Brief description  <br><br><br>门面<br><br>  <br>Content  <br>interface [Facade](-facade/index.md)  <br><br><br>
| [Launcher](-launcher/index.md)| [jvm]  <br>Brief description  <br><br><br>引导器<br><br>  <br>Content  <br>abstract class [Launcher](-launcher/index.md) : CoroutineVerticle  <br><br><br>
| [Maintainer](-maintainer/index.md)| [jvm]  <br>Brief description  <br><br><br>维护者<br><br>  <br>Content  <br>class [Maintainer](-maintainer/index.md)(**vertx**: Vertx)  <br><br><br>
| [OperationResponder](index.md#tech.whence.echo.rpc/OperationResponder///PointingToDeclaration/)| [jvm]  <br>Brief description  <br><br><br>WEB响应<br><br>  <br>Content  <br>typealias [OperationResponder](index.md#tech.whence.echo.rpc/OperationResponder///PointingToDeclaration/) = Handler<AsyncResult<OperationResponse>>  <br><br><br>
| [Responder](index.md#tech.whence.echo.rpc/Responder///PointingToDeclaration/)| [jvm]  <br>Brief description  <br><br><br>响应<br><br>  <br>Content  <br>typealias [Responder](index.md#tech.whence.echo.rpc/Responder///PointingToDeclaration/)<[T](index.md#tech.whence.echo.rpc/Responder///PointingToDeclaration/)> = Handler<AsyncResult<[Response](../tech.whence.echo.rpc.response/-response/index.md)<[T](index.md#tech.whence.echo.rpc/Responder///PointingToDeclaration/)>>>  <br><br><br>
| [Server](-server/index.md)| [jvm]  <br>Brief description  <br><br><br>服务提供者<br><br>  <br>Content  <br>class [Server](-server/index.md)(**vertx**: Vertx)  <br><br><br>


## Functions  
  
|  Name|  Summary| 
|---|---|
| [extract](extract.md)| [jvm]  <br>Brief description  <br><br><br>参数化前端请求<br><br>  <br>Content  <br>inline fun <[T](extract.md) : [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)> OperationRequest.[extract](extract.md)(key: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?): [T](extract.md)  <br><br><br>
| [respond](respond.md)| [jvm]  <br>Brief description  <br><br><br>响应<br><br>  <br>Content  <br>fun [OperationResponder](index.md#tech.whence.echo.rpc/OperationResponder///PointingToDeclaration/).[respond](respond.md)(consumer: [Consumer](../tech.whence.echo.function/-consumer/index.md)<[OperationResponder](index.md#tech.whence.echo.rpc/OperationResponder///PointingToDeclaration/)>)  <br>fun <[T](respond.md) : [Payload](../tech.whence.echo.rpc.payload/-payload/index.md)> [Responder](index.md#tech.whence.echo.rpc/Responder///PointingToDeclaration/)<[T](respond.md)>.[respond](respond.md)(response: [Response](../tech.whence.echo.rpc.response/-response/index.md)<[T](respond.md)>)  <br><br><br>
| [up](up.md)| [jvm]  <br>Brief description  <br><br><br>标准化前端响应<br><br>  <br>Content  <br>inline fun <[T](up.md) : [Payload](../tech.whence.echo.rpc.payload/-payload/index.md)> [OperationResponder](index.md#tech.whence.echo.rpc/OperationResponder///PointingToDeclaration/).[up](up.md)(): [Responder](index.md#tech.whence.echo.rpc/Responder///PointingToDeclaration/)<[T](up.md)>  <br><br><br>[jvm]  <br>Brief description  <br><br><br>转换为访问器<br><br>  <br>Content  <br>fun JsonObject.[up](up.md)(): [Accessor](../tech.whence.echo.container.accessor/-accessor/index.md)  <br><br><br>[jvm]  <br>Brief description  <br><br><br>标准化前端请求<br><br>  <br>Content  <br>inline fun <[T](up.md) : [Payload](../tech.whence.echo.rpc.payload/-payload/index.md)> OperationRequest.[up](up.md)(): [Request](../tech.whence.echo.rpc.request/-request/index.md)<[T](up.md)>  <br><br><br>
| [via](via.md)| [jvm]  <br>Brief description  <br><br><br>响应<br><br>  <br>Content  <br>fun <[T](via.md) : [Payload](../tech.whence.echo.rpc.payload/-payload/index.md)> [OperationResponder](index.md#tech.whence.echo.rpc/OperationResponder///PointingToDeclaration/).[via](via.md)(producer: [Producer](../tech.whence.echo.function/-producer/index.md)<[Response](../tech.whence.echo.rpc.response/-response/index.md)<[T](via.md)>>)  <br><br><br>
| [warn](warn.md)| [jvm]  <br>Brief description  <br><br><br>告警<br><br>  <br>Content  <br>fun HttpServerResponse.[warn](warn.md)(failure: [Failure](../tech.whence.echo.rpc.response/-failure/index.md))  <br>fun HttpServerResponse.[warn](warn.md)(code: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), message: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html))  <br><br><br>

