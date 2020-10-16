---
title: Factory -
---
//[echo](../../index.md)/[tech.whence.echo.ioc](../index.md)/[Factory](index.md)



# Factory  
 [jvm] 

Verticle工厂

class [Factory](index.md) : VerticleFactory   


## Constructors  
  
|  Name|  Summary| 
|---|---|
| [Factory](-factory.md)|  [jvm] fun [Factory](-factory.md)()   <br>


## Types  
  
|  Name|  Summary| 
|---|---|
| [Companion](-companion/index.md)| [jvm]  <br>Content  <br>object [Companion](-companion/index.md)  <br><br><br>


## Functions  
  
|  Name|  Summary| 
|---|---|
| [blockingCreate](index.md#io.vertx.core.spi/VerticleFactory/blockingCreate/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [blockingCreate](index.md#io.vertx.core.spi/VerticleFactory/blockingCreate/#/PointingToDeclaration/)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [close](index.md#io.vertx.core.spi/VerticleFactory/close/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [close](index.md#io.vertx.core.spi/VerticleFactory/close/#/PointingToDeclaration/)()  <br><br><br>
| [createVerticle](create-verticle.md)| [jvm]  <br>Brief description  <br><br><br>创建<br><br>  <br>Content  <br>open override fun [createVerticle](create-verticle.md)(name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), loader: [ClassLoader](https://docs.oracle.com/javase/8/docs/api/java/lang/ClassLoader.html)): Verticle  <br><br><br>
| [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)| [jvm]  <br>Content  <br>open operator override fun [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [init](index.md#io.vertx.core.spi/VerticleFactory/init/#io.vertx.core.Vertx/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [init](index.md#io.vertx.core.spi/VerticleFactory/init/#io.vertx.core.Vertx/PointingToDeclaration/)(p0: Vertx)  <br><br><br>
| [order](index.md#io.vertx.core.spi/VerticleFactory/order/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [order](index.md#io.vertx.core.spi/VerticleFactory/order/#/PointingToDeclaration/)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [prefix](prefix.md)| [jvm]  <br>Brief description  <br><br><br>前缀<br><br>  <br>Content  <br>open override fun [prefix](prefix.md)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>
| [requiresResolve](index.md#io.vertx.core.spi/VerticleFactory/requiresResolve/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [requiresResolve](index.md#io.vertx.core.spi/VerticleFactory/requiresResolve/#/PointingToDeclaration/)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [resolve](index.md#io.vertx.core.spi/VerticleFactory/resolve/#kotlin.String#io.vertx.core.DeploymentOptions#java.lang.ClassLoader#io.vertx.core.Promise[kotlin.String]/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [resolve](index.md#io.vertx.core.spi/VerticleFactory/resolve/#kotlin.String#io.vertx.core.DeploymentOptions#java.lang.ClassLoader#io.vertx.core.Promise[kotlin.String]/PointingToDeclaration/)(p0: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), p1: DeploymentOptions, p2: [ClassLoader](https://docs.oracle.com/javase/8/docs/api/java/lang/ClassLoader.html), p3: Promise<[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)>)  <br><br><br>
| [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>

