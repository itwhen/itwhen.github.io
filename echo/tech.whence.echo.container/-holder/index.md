---
title: Holder -
---
//[echo](../../index.md)/[tech.whence.echo.container](../index.md)/[Holder](index.md)



# Holder  
 [jvm] 

延迟加载器

class [Holder](index.md)<[T](index.md) : [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>(**name**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), **factory**: [Transformer](../../tech.whence.echo.function/-transformer/index.md)<[T](index.md)?, [T](index.md)>)   


## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| T| <br><br>值类型<br><br>
  


## Constructors  
  
|  Name|  Summary| 
|---|---|
| [Holder](-holder.md)|  [jvm] <br><br><br><br>fun <[T](index.md) : [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)> [Holder](-holder.md)(name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), factory: [Transformer](../../tech.whence.echo.function/-transformer/index.md)<[T](index.md)?, [T](index.md)>)   <br>


## Types  
  
|  Name|  Summary| 
|---|---|
| [Companion](-companion/index.md)| [jvm]  <br>Content  <br>object [Companion](-companion/index.md)  <br><br><br>


## Functions  
  
|  Name|  Summary| 
|---|---|
| [clear](clear.md)| [jvm]  <br>Brief description  <br><br><br>清理值<br><br>  <br>Content  <br>fun [clear](clear.md)()  <br><br><br>[jvm]  <br>Brief description  <br><br><br>清理<br><br>  <br>Content  <br>suspend fun [clear](clear.md)(block: [SuspendFunction1](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.coroutines/-suspend-function1/index.html)<[T](index.md), [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)>)  <br><br><br>
| [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)| [jvm]  <br>Content  <br>open operator override fun [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [invoke](invoke.md)| [jvm]  <br>Brief description  <br><br><br>取值<br><br>  <br>Content  <br>operator fun [invoke](invoke.md)(auto: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)): [T](index.md)  <br><br><br>
| [reset](reset.md)| [jvm]  <br>Brief description  <br><br><br>重置<br><br>  <br>Content  <br>fun [reset](reset.md)()  <br><br><br>
| [set](set.md)| [jvm]  <br>Brief description  <br><br><br>设置值<br><br>  <br>Content  <br>fun [set](set.md)(value: [T](index.md))  <br><br><br>
| [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>

