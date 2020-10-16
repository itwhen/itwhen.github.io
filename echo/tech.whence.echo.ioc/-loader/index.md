---
title: Loader -
---
//[echo](../../index.md)/[tech.whence.echo.ioc](../index.md)/[Loader](index.md)



# Loader  
 [jvm] 

加载器

class [Loader](index.md)(**name**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), **loader**: [ClassLoader](https://docs.oracle.com/javase/8/docs/api/java/lang/ClassLoader.html)) : AbstractVerticle   


## Constructors  
  
|  Name|  Summary| 
|---|---|
| [Loader](-loader.md)|  [jvm] <br><br><br><br>fun [Loader](-loader.md)(name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), loader: [ClassLoader](https://docs.oracle.com/javase/8/docs/api/java/lang/ClassLoader.html))   <br>


## Types  
  
|  Name|  Summary| 
|---|---|
| [Companion](-companion/index.md)| [jvm]  <br>Content  <br>object [Companion](-companion/index.md)  <br><br><br>


## Functions  
  
|  Name|  Summary| 
|---|---|
| [config](index.md#io.vertx.core/AbstractVerticle/config/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [config](index.md#io.vertx.core/AbstractVerticle/config/#/PointingToDeclaration/)(): JsonObject  <br><br><br>
| [create](create.md)| [jvm]  <br>Brief description  <br><br><br>创建 根据指定名称查找指定类再创建<br><br>  <br>Content  <br>fun [create](create.md)(): Verticle  <br><br><br>
| [deploymentID](index.md#io.vertx.core/AbstractVerticle/deploymentID/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [deploymentID](index.md#io.vertx.core/AbstractVerticle/deploymentID/#/PointingToDeclaration/)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>
| [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)| [jvm]  <br>Content  <br>open operator override fun [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [getVertx](index.md#io.vertx.core/AbstractVerticle/getVertx/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [getVertx](index.md#io.vertx.core/AbstractVerticle/getVertx/#/PointingToDeclaration/)(): Vertx  <br><br><br>
| [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [init](init.md)| [jvm]  <br>Brief description  <br><br><br>初始化<br><br>  <br>Content  <br>open override fun [init](init.md)(vertx: Vertx, context: Context)  <br><br><br>
| [processArgs](index.md#io.vertx.core/AbstractVerticle/processArgs/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [processArgs](index.md#io.vertx.core/AbstractVerticle/processArgs/#/PointingToDeclaration/)(): [MutableList](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-list/index.html)<[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)>  <br><br><br>
| [start](index.md#io.vertx.core/AbstractVerticle/start/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [start](index.md#io.vertx.core/AbstractVerticle/start/#/PointingToDeclaration/)()  <br>~~open~~ ~~override~~ ~~fun~~ [~~start~~](index.md#io.vertx.core/AbstractVerticle/start/#io.vertx.core.Future[java.lang.Void]/PointingToDeclaration/)~~(~~~~p0~~~~:~~ Future<[Void](https://docs.oracle.com/javase/8/docs/api/java/lang/Void.html)>~~)~~  <br><br><br>[jvm]  <br>Brief description  <br><br><br>启动<br><br>  <br>Content  <br>open override fun [start](start.md)(promise: Promise<[Void](https://docs.oracle.com/javase/8/docs/api/java/lang/Void.html)>)  <br><br><br>
| [stop](index.md#io.vertx.core/AbstractVerticle/stop/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [stop](index.md#io.vertx.core/AbstractVerticle/stop/#/PointingToDeclaration/)()  <br>~~open~~ ~~override~~ ~~fun~~ [~~stop~~](index.md#io.vertx.core/AbstractVerticle/stop/#io.vertx.core.Future[java.lang.Void]/PointingToDeclaration/)~~(~~~~p0~~~~:~~ Future<[Void](https://docs.oracle.com/javase/8/docs/api/java/lang/Void.html)>~~)~~  <br><br><br>[jvm]  <br>Brief description  <br><br><br>停止<br><br>  <br>Content  <br>open override fun [stop](stop.md)(promise: Promise<[Void](https://docs.oracle.com/javase/8/docs/api/java/lang/Void.html)>)  <br><br><br>
| [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>


## Properties  
  
|  Name|  Summary| 
|---|---|
| [context](index.md#tech.whence.echo.ioc/Loader/context/#/PointingToDeclaration/)|  [jvm] override val [context](index.md#tech.whence.echo.ioc/Loader/context/#/PointingToDeclaration/): Context   <br>
| [name](index.md#tech.whence.echo.ioc/Loader/name/#/PointingToDeclaration/)|  [jvm] <br><br>String 指定名称<br><br>val [name](index.md#tech.whence.echo.ioc/Loader/name/#/PointingToDeclaration/): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)   <br>
| [vertx](index.md#tech.whence.echo.ioc/Loader/vertx/#/PointingToDeclaration/)|  [jvm] override val [vertx](index.md#tech.whence.echo.ioc/Loader/vertx/#/PointingToDeclaration/): Vertx   <br>

