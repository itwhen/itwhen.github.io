---
title: Launcher -
---
//[echo](../../index.md)/[tech.whence.echo.rpc](../index.md)/[Launcher](index.md)



# Launcher  
 [jvm] 

引导器

abstract class [Launcher](index.md) : CoroutineVerticle   


## Constructors  
  
|  Name|  Summary| 
|---|---|
| [Launcher](-launcher.md)|  [jvm] fun [Launcher](-launcher.md)()   <br>


## Functions  
  
|  Name|  Summary| 
|---|---|
| [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)| [jvm]  <br>Content  <br>open operator override fun [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [getVertx](index.md#io.vertx.kotlin.coroutines/CoroutineVerticle/getVertx/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [getVertx](index.md#io.vertx.kotlin.coroutines/CoroutineVerticle/getVertx/#/PointingToDeclaration/)(): Vertx  <br><br><br>
| [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [init](index.md#io.vertx.kotlin.coroutines/CoroutineVerticle/init/#io.vertx.core.Vertx#io.vertx.core.Context/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [init](index.md#io.vertx.kotlin.coroutines/CoroutineVerticle/init/#io.vertx.core.Vertx#io.vertx.core.Context/PointingToDeclaration/)(vertx: Vertx, context: Context)  <br><br><br>
| [start](index.md#io.vertx.core/Verticle/start/#io.vertx.core.Promise[java.lang.Void]/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [start](index.md#io.vertx.core/Verticle/start/#io.vertx.core.Promise[java.lang.Void]/PointingToDeclaration/)(p0: Promise<[Void](https://docs.oracle.com/javase/8/docs/api/java/lang/Void.html)>)  <br>open override fun [start](index.md#io.vertx.kotlin.coroutines/CoroutineVerticle/start/#io.vertx.core.Future[java.lang.Void]?/PointingToDeclaration/)(startFuture: Future<[Void](https://docs.oracle.com/javase/8/docs/api/java/lang/Void.html)>?)  <br><br><br>
| [stop](index.md#io.vertx.core/Verticle/stop/#io.vertx.core.Promise[java.lang.Void]/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [stop](index.md#io.vertx.core/Verticle/stop/#io.vertx.core.Promise[java.lang.Void]/PointingToDeclaration/)(p0: Promise<[Void](https://docs.oracle.com/javase/8/docs/api/java/lang/Void.html)>)  <br>open override fun [stop](index.md#io.vertx.kotlin.coroutines/CoroutineVerticle/stop/#io.vertx.core.Future[java.lang.Void]?/PointingToDeclaration/)(stopFuture: Future<[Void](https://docs.oracle.com/javase/8/docs/api/java/lang/Void.html)>?)  <br><br><br>
| [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>


## Properties  
  
|  Name|  Summary| 
|---|---|
| [coroutineContext](index.md#tech.whence.echo.rpc/Launcher/coroutineContext/#/PointingToDeclaration/)|  [jvm] open override val [coroutineContext](index.md#tech.whence.echo.rpc/Launcher/coroutineContext/#/PointingToDeclaration/): [CoroutineContext](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.coroutines/-coroutine-context/index.html)   <br>
| [vertxInstance](index.md#tech.whence.echo.rpc/Launcher/vertxInstance/#/PointingToDeclaration/)|  [jvm] lateinit override var [vertxInstance](index.md#tech.whence.echo.rpc/Launcher/vertxInstance/#/PointingToDeclaration/): Vertx   <br>

