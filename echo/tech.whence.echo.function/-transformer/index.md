---
title: Transformer -
---
//[echo](../../index.md)/[tech.whence.echo.function](../index.md)/[Transformer](index.md)



# Transformer  
 [jvm] 

转换器

fun fun interface [Transformer](index.md)<[F](index.md), [T](index.md)>   


## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| F| <br><br>来源类型<br><br>
| T| <br><br>目的类型<br><br>
  


## Types  
  
|  Name|  Summary| 
|---|---|
| [Companion](-companion/index.md)| [jvm]  <br>Content  <br>object [Companion](-companion/index.md)  <br><br><br>


## Functions  
  
|  Name|  Summary| 
|---|---|
| [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)| [jvm]  <br>Content  <br>open operator override fun [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [invoke](invoke.md)| [jvm]  <br>Brief description  <br><br><br>调用<br><br>  <br>Content  <br>open operator fun [invoke](invoke.md)(value: [F](index.md)): [T](index.md)  <br><br><br>
| [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>
| [transform](transform.md)| [jvm]  <br>Brief description  <br><br><br>转换<br><br>  <br>Content  <br>abstract fun [transform](transform.md)(value: [F](index.md)): [T](index.md)  <br><br><br>
| [up](up.md)| [jvm]  <br>Brief description  <br><br><br>本地化<br><br>  <br>Content  <br>open fun [up](up.md)(): ([F](index.md)) -> [T](index.md)  <br>open fun <[C](up.md)> [up](up.md)(context: [C](up.md)): [C](up.md).([F](index.md)) -> [T](index.md)  <br><br><br>

