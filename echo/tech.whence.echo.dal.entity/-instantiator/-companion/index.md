---
title: Companion -
---
//[echo](../../../index.md)/[tech.whence.echo.dal.entity](../../index.md)/[Instantiator](../index.md)/[Companion](index.md)



# Companion  
 [jvm] object [Companion](index.md)   


## Functions  
  
|  Name|  Summary| 
|---|---|
| [create](create.md)| [jvm]  <br>Brief description  <br><br><br>根据静态实体类构建<br><br>  <br>Content  <br>@[JvmStatic](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-static/index.html)()  <br>  <br>fun <[D](create.md), [E](create.md) : [Entity](../../-entity/index.md)> [create](create.md)(declarer: [KClass](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-class/index.html)<[E](create.md)>, handler: [Transformer](../../../tech.whence.echo.function/-transformer/index.md)<[D](create.md), [E](create.md)>): [Instantiator](../index.md)<[D](create.md), [E](create.md)>  <br><br><br>
| [equals](../../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)| [jvm]  <br>Content  <br>open operator override fun [equals](../../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [hashCode](../../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [hashCode](../../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [pack](pack.md)| [jvm]  <br>Brief description  <br><br><br>构建动态实体相关<br><br>  <br>Content  <br>@[JvmStatic](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-static/index.html)()  <br>  <br>fun <[D](pack.md), [E](pack.md) : [Entity](../../-entity/index.md)> [pack](pack.md)(name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), keymaker: [Producer](../../../tech.whence.echo.function/-producer/index.md)<[Keys](../../../tech.whence.echo.dal.schema.key/-keys/index.md)>, handler: [Transformer](../../../tech.whence.echo.function/-transformer/index.md)<[D](pack.md), [Accessor](../../../tech.whence.echo.container.accessor/-accessor/index.md)>): [Instantiator](../index.md)<[D](pack.md), [E](pack.md)>  <br><br><br>
| [toString](../../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [toString](../../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>

