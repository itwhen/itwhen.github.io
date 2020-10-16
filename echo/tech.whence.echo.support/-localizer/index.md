---
title: Localizer -
---
//[echo](../../index.md)/[tech.whence.echo.support](../index.md)/[Localizer](index.md)



# Localizer  
 [jvm] 

信息本地化器

class [Localizer](index.md)(**name**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html))   


## Constructors  
  
|  Name|  Summary| 
|---|---|
| [Localizer](-localizer.md)|  [jvm] fun [Localizer](-localizer.md)(name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html))   <br>


## Types  
  
|  Name|  Summary| 
|---|---|
| [Data](-data/index.md)| [jvm]  <br>Brief description  <br><br><br>待格式化数据<br><br>  <br>Content  <br>data class [Data](-data/index.md)(**id**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), **message**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), **name**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, **parameters**: [Map](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)<[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?>?)  <br><br><br>


## Functions  
  
|  Name|  Summary| 
|---|---|
| [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)| [jvm]  <br>Content  <br>open operator override fun [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [localize](localize.md)| [jvm]  <br>Brief description  <br><br><br>语言设定<br><br>  <br>Content  <br>fun [localize](localize.md)(locale: [Locale](https://docs.oracle.com/javase/8/docs/api/java/util/Locale.html))  <br><br><br>
| [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>
| [translate](translate.md)| [jvm]  <br>Brief description  <br><br><br>本地化消息<br><br>  <br>Content  <br>fun [translate](translate.md)(data: [Localizer.Data](-data/index.md)): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>[jvm]  <br>Brief description  <br><br><br>本地化消息 若数据中找不到指定message则用本身代替 将用name替换消息中占位符:it 若simplify为真时将占位符:it替换为空字符串<br><br>  <br>Content  <br>fun [translate](translate.md)(id: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), message: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, parameters: [Map](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)<[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?>?, simplify: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>


## Properties  
  
|  Name|  Summary| 
|---|---|
| [locale](index.md#tech.whence.echo.support/Localizer/locale/#/PointingToDeclaration/)|  [jvm] <br><br>(java.util.Locale..java.util.Locale?) 语言设置<br><br>var [locale](index.md#tech.whence.echo.support/Localizer/locale/#/PointingToDeclaration/): [Locale](https://docs.oracle.com/javase/8/docs/api/java/util/Locale.html)   <br>

