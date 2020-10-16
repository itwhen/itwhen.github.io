---
title: tech.whence.echo.ioc -
---
//[echo](../index.md)/[tech.whence.echo.ioc](index.md)



# Package tech.whence.echo.ioc  


## Types  
  
|  Name|  Summary| 
|---|---|
| [AbstractBinder](-abstract-binder/index.md)| [jvm]  <br>Brief description  <br><br><br>抽象模块<br><br>  <br>Content  <br>abstract class [AbstractBinder](-abstract-binder/index.md) : AbstractModule  <br><br><br>
| [Factory](-factory/index.md)| [jvm]  <br>Brief description  <br><br><br>Verticle工厂<br><br>  <br>Content  <br>class [Factory](-factory/index.md) : VerticleFactory  <br><br><br>
| [Loader](-loader/index.md)| [jvm]  <br>Brief description  <br><br><br>加载器<br><br>  <br>Content  <br>class [Loader](-loader/index.md)(**name**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), **loader**: [ClassLoader](https://docs.oracle.com/javase/8/docs/api/java/lang/ClassLoader.html)) : AbstractVerticle  <br><br><br>


## Functions  
  
|  Name|  Summary| 
|---|---|
| [config](config.md)| [jvm]  <br>Brief description  <br><br><br>取配置<br><br>  <br>Content  <br>fun Vertx.[config](config.md)(): [Accessor](../tech.whence.echo.container.accessor/-accessor/index.md)  <br><br><br>
| [instance](instance.md)| [jvm]  <br>Brief description  <br><br><br>取实例<br><br>  <br>Content  <br>inline fun <[T](instance.md)> [instance](instance.md)(): [T](instance.md)  <br>fun <[T](instance.md) : [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)> [instance](instance.md)(declarer: [KClass](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-class/index.html)<out [T](instance.md)>): [T](instance.md)  <br><br><br>

