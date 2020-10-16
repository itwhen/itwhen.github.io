---
title: StringDecoder -
---
//[echo](../../index.md)/[tech.whence.echo.codec.decoder](../index.md)/[StringDecoder](index.md)



# StringDecoder  
 [jvm] 

String 解码器

class [StringDecoder](index.md) : [Decoder](../../tech.whence.echo.codec/-decoder/index.md)<[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), [StringArray](../../tech.whence.echo.type/index.md#tech.whence.echo.type/StringArray///PointingToDeclaration/)>    


## Constructors  
  
|  Name|  Summary| 
|---|---|
| [StringDecoder](-string-decoder.md)|  [jvm] fun [StringDecoder](-string-decoder.md)()   <br>


## Types  
  
|  Name|  Summary| 
|---|---|
| [Companion](-companion/index.md)| [jvm]  <br>Content  <br>object [Companion](-companion/index.md)  <br><br><br>


## Functions  
  
|  Name|  Summary| 
|---|---|
| [decode](decode.md)| [jvm]  <br>Brief description  <br><br><br>转换指定值到指定类型<br><br>  <br>Content  <br>open override fun [decode](decode.md)(value: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?  <br><br><br>[jvm]  <br>Brief description  <br><br><br>转换指定值到指定类型后继续下一步骤<br><br>  <br>Content  <br>open override fun <R> [decode](index.md#tech.whence.echo.codec/Decoder/decode/#kotlin.Any?#kotlin.Function1[kotlin.String,TypeParam(bounds=[kotlin.Any?])?]/PointingToDeclaration/)(value: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?, next: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html).() -> R?): R?  <br><br><br>[jvm]  <br>Brief description  <br><br><br>转换为字符串<br><br>  <br>Content  <br>fun [decode](decode.md)(value: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?, trim: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), blankable: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?  <br><br><br>
| [decodes](decodes.md)| [jvm]  <br>Brief description  <br><br><br>转换指定值到指定类型数组<br><br>  <br>Content  <br>open override fun [decodes](decodes.md)(value: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [StringArray](../../tech.whence.echo.type/index.md#tech.whence.echo.type/StringArray///PointingToDeclaration/)?  <br><br><br>[jvm]  <br>Brief description  <br><br><br>转换为字符串数组<br><br>  <br>Content  <br>fun [decodes](decodes.md)(value: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?, trim: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), blankable: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)): [StringArray](../../tech.whence.echo.type/index.md#tech.whence.echo.type/StringArray///PointingToDeclaration/)?  <br><br><br>
| [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)| [jvm]  <br>Content  <br>open operator override fun [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [extract](extract.md)| [jvm]  <br>Brief description  <br><br><br>转换为查询字符串数据<br><br>  <br>Content  <br>@[JvmOverloads](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-overloads/index.html)()  <br>  <br>fun [extract](extract.md)(value: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?, separator: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), assignment: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), fixer: [Fixer](../../tech.whence.echo.function/-fixer/index.md)<[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)>?): [Map](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)<[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?>?  <br><br><br>
| [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [split](split.md)| [jvm]  <br>Brief description  <br><br><br>使用正则分割字符串<br><br>  <br>Content  <br>inline fun <[T](split.md) : [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)> [split](split.md)(value: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?, delimiter: [Regex](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.text/-regex/index.html)?, caster: [Transformer](../../tech.whence.echo.function/-transformer/index.md)<[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), [T](split.md)>): [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<out [T](split.md)>?  <br><br><br>[jvm]  <br>Brief description  <br><br><br>分割字符串<br><br>  <br>Content  <br>inline fun <[T](split.md) : [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)> [split](split.md)(value: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?, splitter: [Transformer](../../tech.whence.echo.function/-transformer/index.md)<[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<out [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)>>, caster: [Transformer](../../tech.whence.echo.function/-transformer/index.md)<[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), [T](split.md)>): [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<out [T](split.md)>?  <br><br><br>
| [stringify](index.md#tech.whence.echo.codec/Decoder/stringify/#kotlin.String?/PointingToDeclaration/)| [jvm]  <br>Brief description  <br><br><br>字符串化<br><br>  <br>Content  <br>open override fun [stringify](index.md#tech.whence.echo.codec/Decoder/stringify/#kotlin.String?/PointingToDeclaration/)(value: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>
| [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>

