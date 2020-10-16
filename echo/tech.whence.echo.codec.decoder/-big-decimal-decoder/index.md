---
title: BigDecimalDecoder -
---
//[echo](../../index.md)/[tech.whence.echo.codec.decoder](../index.md)/[BigDecimalDecoder](index.md)



# BigDecimalDecoder  
 [jvm] 

BigDecimal解码器 支持对BigInteger,Number,Boolean,CharSequence的转换

class [BigDecimalDecoder](index.md) : [Decoder](../../tech.whence.echo.codec/-decoder/index.md)<[BigDecimal](https://docs.oracle.com/javase/8/docs/api/java/math/BigDecimal.html), [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<[BigDecimal](https://docs.oracle.com/javase/8/docs/api/java/math/BigDecimal.html)>>    


## Constructors  
  
|  Name|  Summary| 
|---|---|
| [BigDecimalDecoder](-big-decimal-decoder.md)|  [jvm] fun [BigDecimalDecoder](-big-decimal-decoder.md)()   <br>


## Functions  
  
|  Name|  Summary| 
|---|---|
| [decode](decode.md)| [jvm]  <br>Brief description  <br><br><br>转换指定值到指定类型<br><br>  <br>Content  <br>open override fun [decode](decode.md)(value: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [BigDecimal](https://docs.oracle.com/javase/8/docs/api/java/math/BigDecimal.html)?  <br><br><br>[jvm]  <br>Brief description  <br><br><br>转换字符串 为空时置零<br><br>  <br>Content  <br>@[JvmOverloads](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-overloads/index.html)()  <br>  <br>fun [decode](decode.md)(value: [CharSequence](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-char-sequence/index.html), context: [MathContext](https://docs.oracle.com/javase/8/docs/api/java/math/MathContext.html)?): [BigDecimal](https://docs.oracle.com/javase/8/docs/api/java/math/BigDecimal.html)  <br><br><br>[jvm]  <br>Brief description  <br><br><br>转换指定值到指定类型后继续下一步骤<br><br>  <br>Content  <br>open override fun <R> [decode](index.md#tech.whence.echo.codec/Decoder/decode/#kotlin.Any?#kotlin.Function1[java.math.BigDecimal,TypeParam(bounds=[kotlin.Any?])?]/PointingToDeclaration/)(value: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?, next: [BigDecimal](https://docs.oracle.com/javase/8/docs/api/java/math/BigDecimal.html).() -> R?): R?  <br><br><br>
| [decodes](decodes.md)| [jvm]  <br>Brief description  <br><br><br>转换指定值到指定类型数组<br><br>  <br>Content  <br>open override fun [decodes](decodes.md)(value: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<[BigDecimal](https://docs.oracle.com/javase/8/docs/api/java/math/BigDecimal.html)>?  <br><br><br>
| [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)| [jvm]  <br>Content  <br>open operator override fun [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [stringify](stringify.md)| [jvm]  <br>Brief description  <br><br><br>字符串化<br><br>  <br>Content  <br>open override fun [stringify](stringify.md)(value: [BigDecimal](https://docs.oracle.com/javase/8/docs/api/java/math/BigDecimal.html)?): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>
| [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>

