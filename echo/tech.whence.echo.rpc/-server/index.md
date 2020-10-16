---
title: Server -
---
//[echo](../../index.md)/[tech.whence.echo.rpc](../index.md)/[Server](index.md)



# Server  
 [jvm] 

服务提供者

class [Server](index.md)(**vertx**: Vertx)   


## Constructors  
  
|  Name|  Summary| 
|---|---|
| [Server](-server.md)|  [jvm] fun [Server](-server.md)(vertx: Vertx)   <br>


## Types  
  
|  Name|  Summary| 
|---|---|
| [Companion](-companion/index.md)| [jvm]  <br>Content  <br>object [Companion](-companion/index.md)  <br><br><br>


## Functions  
  
|  Name|  Summary| 
|---|---|
| [adapt](adapt.md)| [jvm]  <br>Brief description  <br><br><br>注册服务及其自动适配接口<br><br>  <br>Content  <br>fun <[F](adapt.md) : [Facade](../-facade/index.md), [A](adapt.md) : [Api](../-api/index.md)<[F](adapt.md)>, [Contractor](../-contractor/index.md)> [adapt](adapt.md)(facade: [KClass](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-class/index.html)<out [F](adapt.md)>, adapter: [KClass](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-class/index.html)<[A](adapt.md)>): [Server](index.md)  <br>fun <[F](adapt.md) : [Facade](../-facade/index.md), [A](adapt.md) : [Api](../-api/index.md)<[F](adapt.md)>, [Contractor](../-contractor/index.md)> [adapt](adapt.md)(producer: [Producer](../../tech.whence.echo.function/-producer/index.md)<[F](adapt.md)>, adapter: [KClass](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-class/index.html)<[A](adapt.md)>): [Server](index.md)  <br><br><br>
| [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)| [jvm]  <br>Content  <br>open operator override fun [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [locate](locate.md)| [jvm]  <br>Brief description  <br><br><br>设置监听<br><br>  <br>Content  <br>@[JvmOverloads](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-overloads/index.html)()  <br>  <br>fun [locate](locate.md)(router: Router, host: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), port: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), options: HttpServerOptions?): [Server](index.md)  <br><br><br>
| [provide](provide.md)| [jvm]  <br>Brief description  <br><br><br>注册服务<br><br>  <br>Content  <br>fun [provide](provide.md)(contractor: [Contractor](../-contractor/index.md), address: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?): [Server](index.md)  <br><br><br>
| [start](start.md)| [jvm]  <br>Brief description  <br><br><br>启动<br><br>  <br>Content  <br>suspend fun [start](start.md)()  <br><br><br>
| [stop](stop.md)| [jvm]  <br>Brief description  <br><br><br>停止<br><br>  <br>Content  <br>suspend fun [stop](stop.md)()  <br><br><br>
| [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>

