---
title: Errors -
---
//[echo](../../index.md)/[tech.whence.echo.validation](../index.md)/[Errors](index.md)



# Errors  
 [jvm] 

错误消息

class [Errors](index.md) : [Container](../../tech.whence.echo.container/-container/index.md), [Readable](../../tech.whence.echo.container.accessor/-readable/index.md)   


## Constructors  
  
|  Name|  Summary| 
|---|---|
| [Errors](-errors.md)|  [jvm] fun [Errors](-errors.md)()   <br>


## Types  
  
|  Name|  Summary| 
|---|---|
| [Companion](-companion/index.md)| [jvm]  <br>Content  <br>object [Companion](-companion/index.md)  <br><br><br>


## Functions  
  
|  Name|  Summary| 
|---|---|
| [access](access.md)| [jvm]  <br>Brief description  <br><br><br>转换为数据访问器<br><br>  <br>Content  <br>open override fun [access](access.md)(): [Accessor](../../tech.whence.echo.container.accessor/-accessor/index.md)  <br><br><br>
| [add](add.md)| [jvm]  <br>Brief description  <br><br><br>设置错误消息<br><br>  <br>Content  <br>fun [add](add.md)(key: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), message: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html))  <br>fun [add](add.md)(key: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), data: [Localizer.Data](../../tech.whence.echo.support/-localizer/-data/index.md))  <br><br><br>
| [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)| [jvm]  <br>Content  <br>open operator override fun [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [flatten](flatten.md)| [jvm]  <br>Brief description  <br><br><br>聚合错误信息<br><br>  <br>Content  <br>fun [flatten](flatten.md)(): [Map](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)<[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)>?  <br><br><br>
| [get](get.md)| [jvm]  <br>Brief description  <br><br><br>取错误信息<br><br>  <br>Content  <br>fun [get](get.md)(key: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): [Set](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-set/index.html)<[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)>?  <br><br><br>
| [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [stringify](stringify.md)| [jvm]  <br>Brief description  <br><br><br>转换为字符串<br><br>  <br>Content  <br>@[JvmOverloads](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-overloads/index.html)()  <br>  <br>fun [stringify](stringify.md)(encode: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>
| [toString](to-string.md)| [jvm]  <br>Content  <br>open override fun [toString](to-string.md)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>
| [translate](translate.md)| [jvm]  <br>Brief description  <br><br><br>本地化消息 若从未本地化 或者数据变化时 或指定语言与当前语言不一直时<br><br>  <br>Content  <br>@[JvmOverloads](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-overloads/index.html)()  <br>  <br>fun [translate](translate.md)(locale: [Locale](https://docs.oracle.com/javase/8/docs/api/java/util/Locale.html)?): [Map](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)<[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), [Set](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-set/index.html)<[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)>>  <br><br><br>


## Properties  
  
|  Name|  Summary| 
|---|---|
| [empty](index.md#tech.whence.echo.validation/Errors/empty/#/PointingToDeclaration/)|  [jvm] <br><br>Boolean 是否为空<br><br>open override val [empty](index.md#tech.whence.echo.validation/Errors/empty/#/PointingToDeclaration/): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)   <br>
| [size](index.md#tech.whence.echo.validation/Errors/size/#/PointingToDeclaration/)|  [jvm] <br><br>UInt 大小<br><br>open override val [size](index.md#tech.whence.echo.validation/Errors/size/#/PointingToDeclaration/): [UInt](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-u-int/index.html)   <br>

