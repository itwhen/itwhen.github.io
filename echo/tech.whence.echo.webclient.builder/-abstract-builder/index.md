---
title: AbstractBuilder -
---
//[echo](../../index.md)/[tech.whence.echo.webclient.builder](../index.md)/[AbstractBuilder](index.md)



# AbstractBuilder  
 [jvm] 

抽象构建者

abstract class [AbstractBuilder](index.md)<[A](index.md) : [AbstractBuilder](index.md)<[A](index.md), [D](index.md)>, [D](index.md) : [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>(**clazz**: [KClass](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-class/index.html)<[D](index.md)>) : [Builder](../-builder/index.md)<[D](index.md)>    


## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| A| <br><br>子类<br><br>
| D| <br><br>数据<br><br>
  


## Constructors  
  
|  Name|  Summary| 
|---|---|
| [AbstractBuilder](-abstract-builder.md)|  [jvm] <br><br><br><br>fun <[D](index.md) : [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)> [AbstractBuilder](-abstract-builder.md)(clazz: [KClass](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-class/index.html)<[D](index.md)>)   <br>


## Functions  
  
|  Name|  Summary| 
|---|---|
| [build](build.md)| [jvm]  <br>Brief description  <br><br><br>构建<br><br>  <br>Content  <br>open override fun [build](build.md)(): [D](index.md)  <br><br><br>
| [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)| [jvm]  <br>Content  <br>open operator override fun [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [fix](fix.md)| [jvm]  <br>Brief description  <br><br><br>设置纠正器<br><br>  <br>Content  <br>fun [fix](fix.md)(fixer: [Consumer](../../tech.whence.echo.function/-consumer/index.md)<[D](index.md)>?): [A](index.md)  <br><br><br>
| [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>

