---
title: Validated -
---
//[echo](../../index.md)/[tech.whence.echo.validation](../index.md)/[Validated](index.md)



# Validated  
 [jvm] 

校验结果

sealed class [Validated](index.md)   


## Types  
  
|  Name|  Summary| 
|---|---|
| [Failure](-failure/index.md)| [jvm]  <br>Brief description  <br><br><br>失败<br><br>  <br>Content  <br>class [Failure](-failure/index.md)(**message**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), **parameters**: [Map](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)<[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)>?) : [Validated](index.md)  <br><br><br>
| [Stop](-stop/index.md)| [jvm]  <br>Brief description  <br><br><br>终止当前链路<br><br>  <br>Content  <br>object [Stop](-stop/index.md) : [Validated](index.md)  <br><br><br>
| [Success](-success/index.md)| [jvm]  <br>Brief description  <br><br><br>成功 并执行下一个<br><br>  <br>Content  <br>object [Success](-success/index.md) : [Validated](index.md)  <br><br><br>


## Functions  
  
|  Name|  Summary| 
|---|---|
| [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)| [jvm]  <br>Content  <br>open operator override fun [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>


## Inheritors  
  
|  Name| 
|---|
| [Validated](-stop/index.md)
| [Validated](-success/index.md)
| [Validated](-failure/index.md)

