---
title: Factory -
---
//[echo](../../index.md)/[tech.whence.echo.container.accessor](../index.md)/[Factory](index.md)



# Factory  
 [jvm] 

表单生成器

interface [Factory](index.md)   


## Types  
  
|  Name|  Summary| 
|---|---|
| [ArrayData](-array-data/index.md)| [jvm]  <br>Brief description  <br><br><br>表单列表<br><br>  <br>Content  <br>data class [ArrayData](-array-data/index.md)<[T](-array-data/index.md)>(**data**: [MutableList](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-list/index.html)<[T](-array-data/index.md)>) : [MutableList](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-list/index.html)<[T](-array-data/index.md)>   <br><br><br>
| [Companion](-companion/index.md)| [jvm]  <br>Content  <br>object [Companion](-companion/index.md)  <br><br><br>
| [ObjectData](-object-data/index.md)| [jvm]  <br>Brief description  <br><br><br>表单对象<br><br>  <br>Content  <br>data class [ObjectData](-object-data/index.md)(**data**: [MutableMap](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-map/index.html)<[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?>) : [MutableMap](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-map/index.html)<[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?>   <br><br><br>


## Functions  
  
|  Name|  Summary| 
|---|---|
| [arr](arr.md)| [jvm]  <br>Brief description  <br><br><br>创建子列表<br><br>  <br>Content  <br>open fun <[T](arr.md), [S](arr.md) : [Factory.ArrayData](-array-data/index.md)<[T](arr.md)>> [arr](arr.md)(sub: [S](arr.md)): [Factory.ArrayData](-array-data/index.md)<[S](arr.md)>  <br><br><br>[jvm]  <br>Brief description  <br><br><br>创建列表<br><br>  <br>Content  <br>open fun [arr](arr.md)(vararg args: [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?>): [Factory.ArrayData](-array-data/index.md)<[Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?>  <br>open fun [arr](arr.md)(args: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?>): [Factory.ArrayData](-array-data/index.md)<[Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?>  <br><br><br>
| [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)| [jvm]  <br>Content  <br>open operator override fun [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [obj](obj.md)| [jvm]  <br>Brief description  <br><br><br>创建对象<br><br>  <br>Content  <br>open fun [obj](obj.md)(vararg args: [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<out [Pair](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-pair/index.html)<[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), *>>): [Factory.ObjectData](-object-data/index.md)  <br>open fun [obj](obj.md)(args: [Iterable](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-iterable/index.html)<[Pair](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-pair/index.html)<[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), *>>): [Factory.ObjectData](-object-data/index.md)  <br><br><br>
| [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>

