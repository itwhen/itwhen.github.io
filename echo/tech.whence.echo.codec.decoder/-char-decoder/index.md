---
title: CharDecoder -
---
//[echo](../../index.md)/[tech.whence.echo.codec.decoder](../index.md)/[CharDecoder](index.md)



# CharDecoder  
 [jvm] 

Char 解码器 支持 Number,Boolean,CharSequence

class [CharDecoder](index.md) : [Decoder](../../tech.whence.echo.codec/-decoder/index.md)<[Char](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-char/index.html), [CharArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-char-array/index.html)>    


## Constructors  
  
|  Name|  Summary| 
|---|---|
| [CharDecoder](-char-decoder.md)|  [jvm] fun [CharDecoder](-char-decoder.md)()   <br>


## Functions  
  
|  Name|  Summary| 
|---|---|
| [decode](decode.md)| [jvm]  <br>Brief description  <br><br><br>转换指定值到指定类型<br><br>  <br>Content  <br>open override fun [decode](decode.md)(value: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Char](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-char/index.html)?  <br><br><br>[jvm]  <br>Brief description  <br><br><br>转换指定值到指定类型后继续下一步骤<br><br>  <br>Content  <br>open override fun <R> [decode](index.md#tech.whence.echo.codec/Decoder/decode/#kotlin.Any?#kotlin.Function1[kotlin.Char,TypeParam(bounds=[kotlin.Any?])?]/PointingToDeclaration/)(value: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?, next: [Char](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-char/index.html).() -> R?): R?  <br><br><br>
| [decodes](decodes.md)| [jvm]  <br>Brief description  <br><br><br>转换指定值到指定类型数组<br><br>  <br>Content  <br>open override fun [decodes](decodes.md)(value: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [CharArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-char-array/index.html)?  <br><br><br>
| [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)| [jvm]  <br>Content  <br>open operator override fun [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [stringify](index.md#tech.whence.echo.codec/Decoder/stringify/#kotlin.Char?/PointingToDeclaration/)| [jvm]  <br>Brief description  <br><br><br>字符串化<br><br>  <br>Content  <br>open override fun [stringify](index.md#tech.whence.echo.codec/Decoder/stringify/#kotlin.Char?/PointingToDeclaration/)(value: [Char](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-char/index.html)?): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>
| [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>

