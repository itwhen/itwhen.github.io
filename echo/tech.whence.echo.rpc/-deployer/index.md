---
title: Deployer -
---
//[echo](../../index.md)/[tech.whence.echo.rpc](../index.md)/[Deployer](index.md)



# Deployer  
 [jvm] 

部署器

class [Deployer](index.md)   


## Constructors  
  
|  Name|  Summary| 
|---|---|
| [Deployer](-deployer.md)|  [jvm] fun [Deployer](-deployer.md)()   <br>


## Types  
  
|  Name|  Summary| 
|---|---|
| [Companion](-companion/index.md)| [jvm]  <br>Content  <br>object [Companion](-companion/index.md)  <br><br><br>


## Functions  
  
|  Name|  Summary| 
|---|---|
| [deploy](deploy.md)| [jvm]  <br>Brief description  <br><br><br>执行<br><br>  <br>Content  <br>@[JvmOverloads](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-overloads/index.html)()  <br>  <br>fun [deploy](deploy.md)(configurer: [Consumer](../../tech.whence.echo.function/-consumer/index.md)<DeploymentOptions>?)  <br><br><br>
| [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)| [jvm]  <br>Content  <br>open operator override fun [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [inject](inject.md)| [jvm]  <br>Brief description  <br><br><br>设置自动注入类<br><br>  <br>Content  <br>fun [inject](inject.md)(vararg declarer: [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<out [KClass](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-class/index.html)<*>>): [Deployer](index.md)  <br><br><br>
| [locate](locate.md)| [jvm]  <br>Brief description  <br><br><br>根据类定位<br><br>  <br>Content  <br>fun [locate](locate.md)(declarer: [KClass](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-class/index.html)<*>): [Deployer](index.md)  <br><br><br>[jvm]  <br>Brief description  <br><br><br>根据文件定位<br><br>  <br>Content  <br>fun [locate](locate.md)(prefix: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), file: [File](https://docs.oracle.com/javase/8/docs/api/java/io/File.html)): [Deployer](index.md)  <br><br><br>[jvm]  <br>Brief description  <br><br><br>定位<br><br>  <br>Content  <br>fun [locate](locate.md)(dir: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), id: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): [Deployer](index.md)  <br><br><br>[jvm]  <br>Brief description  <br><br><br>根据目录与类定位<br><br>  <br>Content  <br>fun [locate](locate.md)(dir: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), declarer: [KClass](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-class/index.html)<*>): [Deployer](index.md)  <br><br><br>
| [option](option.md)| [jvm]  <br>Brief description  <br><br><br>设置<br><br>  <br>Content  <br>fun [option](option.md)(consumer: [Consumer](../../tech.whence.echo.function/-consumer/index.md)<VertxOptions>): [Deployer](index.md)  <br><br><br>
| [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>

