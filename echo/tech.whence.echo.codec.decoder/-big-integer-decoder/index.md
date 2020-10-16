---
title: BigIntegerDecoder -
---
//[echo](../../index.md)/[tech.whence.echo.codec.decoder](../index.md)/[BigIntegerDecoder](index.md)



# BigIntegerDecoder  
 [jvm] 

BigInteger 解码器 支持 BigDecimal,Number,Boolean,CharSequence

class [BigIntegerDecoder](index.md) : [Decoder](../../tech.whence.echo.codec/-decoder/index.md)<[BigInteger](https://docs.oracle.com/javase/8/docs/api/java/math/BigInteger.html), [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<[BigInteger](https://docs.oracle.com/javase/8/docs/api/java/math/BigInteger.html)>>    


## Constructors  
  
|  Name|  Summary| 
|---|---|
| [BigIntegerDecoder](-big-integer-decoder.md)|  [jvm] fun [BigIntegerDecoder](-big-integer-decoder.md)()   <br>


## Functions  
  
|  Name|  Summary| 
|---|---|
| [decode](decode.md)| [jvm]  <br>Brief description  <br><br><br>转换指定值到指定类型<br><br>  <br>Content  <br>open override fun [decode](decode.md)(value: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [BigInteger](https://docs.oracle.com/javase/8/docs/api/java/math/BigInteger.html)?  <br><br><br>[jvm]  <br>Brief description  <br><br><br>转换指定值到指定类型后继续下一步骤<br><br>  <br>Content  <br>open override fun <R> [decode](index.md#tech.whence.echo.codec/Decoder/decode/#kotlin.Any?#kotlin.Function1[java.math.BigInteger,TypeParam(bounds=[kotlin.Any?])?]/PointingToDeclaration/)(value: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?, next: [BigInteger](https://docs.oracle.com/javase/8/docs/api/java/math/BigInteger.html).() -> R?): R?  <br><br><br>
| [decodes](decodes.md)| [jvm]  <br>Brief description  <br><br><br>转换指定值到指定类型数组<br><br>  <br>Content  <br>open override fun [decodes](decodes.md)(value: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<[BigInteger](https://docs.oracle.com/javase/8/docs/api/java/math/BigInteger.html)>?  <br><br><br>
| [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)| [jvm]  <br>Content  <br>open operator override fun [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [stringify](index.md#tech.whence.echo.codec/Decoder/stringify/#java.math.BigInteger?/PointingToDeclaration/)| [jvm]  <br>Brief description  <br><br><br>字符串化<br><br>  <br>Content  <br>open override fun [stringify](index.md#tech.whence.echo.codec/Decoder/stringify/#java.math.BigInteger?/PointingToDeclaration/)(value: [BigInteger](https://docs.oracle.com/javase/8/docs/api/java/math/BigInteger.html)?): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>
| [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>

