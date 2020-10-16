---
title: SourcedInitializer -
---
//[echo](../../index.md)/[tech.whence.echo.support.kafka.stream.initializer](../index.md)/[SourcedInitializer](index.md)



# SourcedInitializer  
 [jvm] 

可溯源初始化器

class [SourcedInitializer](index.md)<[V](index.md)>(**factory**: [Factory](../../tech.whence.echo.support.kafka.stream.processor/-factory/index.md)<[V](index.md)>, **serde**: Serde<[Accessor](../../tech.whence.echo.container.accessor/-accessor/index.md)>) : [Initializer](../-initializer/index.md)   


## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| V| <br><br>值类型<br><br>
  


## Constructors  
  
|  Name|  Summary| 
|---|---|
| [SourcedInitializer](-sourced-initializer.md)|  [jvm] <br><br><br><br>fun <[V](index.md)> [SourcedInitializer](-sourced-initializer.md)(factory: [Factory](../../tech.whence.echo.support.kafka.stream.processor/-factory/index.md)<[V](index.md)>, serde: Serde<[Accessor](../../tech.whence.echo.container.accessor/-accessor/index.md)>)   <br>


## Functions  
  
|  Name|  Summary| 
|---|---|
| [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)| [jvm]  <br>Content  <br>open operator override fun [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [initialize](initialize.md)| [jvm]  <br>Brief description  <br><br><br>初始化<br><br>  <br>Content  <br>open override fun [initialize](initialize.md)(subscription: [Subscription](../../tech.whence.echo.job.stream.subscription/-subscription/index.md), builder: StreamsBuilder)  <br><br><br>
| [name](../-initializer/name.md)| [jvm]  <br>Brief description  <br><br><br>命名<br><br>  <br>Content  <br>open override fun [name](../-initializer/name.md)(subscription: [Subscription](../../tech.whence.echo.job.stream.subscription/-subscription/index.md), name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>
| [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>

