---
title: LocalDateTimeDecoder -
---
//[echo](../../index.md)/[tech.whence.echo.codec.decoder](../index.md)/[LocalDateTimeDecoder](index.md)



# LocalDateTimeDecoder  
 [jvm] 

LocalDateTime 解码器

class [LocalDateTimeDecoder](index.md) : [Decoder](../../tech.whence.echo.codec/-decoder/index.md)<[LocalDateTime](https://docs.oracle.com/javase/8/docs/api/java/time/LocalDateTime.html), [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<[LocalDateTime](https://docs.oracle.com/javase/8/docs/api/java/time/LocalDateTime.html)>>    


## Constructors  
  
|  Name|  Summary| 
|---|---|
| [LocalDateTimeDecoder](-local-date-time-decoder.md)|  [jvm] fun [LocalDateTimeDecoder](-local-date-time-decoder.md)()   <br>


## Types  
  
|  Name|  Summary| 
|---|---|
| [Companion](-companion/index.md)| [jvm]  <br>Content  <br>object [Companion](-companion/index.md)  <br><br><br>


## Functions  
  
|  Name|  Summary| 
|---|---|
| [decode](decode.md)| [jvm]  <br>Brief description  <br><br><br>转换指定值到指定类型<br><br>  <br>Content  <br>open override fun [decode](decode.md)(value: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [LocalDateTime](https://docs.oracle.com/javase/8/docs/api/java/time/LocalDateTime.html)?  <br><br><br>[jvm]  <br>Brief description  <br><br><br>转换指定值到指定类型后继续下一步骤<br><br>  <br>Content  <br>open override fun <R> [decode](index.md#tech.whence.echo.codec/Decoder/decode/#kotlin.Any?#kotlin.Function1[java.time.LocalDateTime,TypeParam(bounds=[kotlin.Any?])?]/PointingToDeclaration/)(value: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?, next: [LocalDateTime](https://docs.oracle.com/javase/8/docs/api/java/time/LocalDateTime.html).() -> R?): R?  <br><br><br>
| [decodes](decodes.md)| [jvm]  <br>Brief description  <br><br><br>转换指定值到指定类型数组<br><br>  <br>Content  <br>open override fun [decodes](decodes.md)(value: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<[LocalDateTime](https://docs.oracle.com/javase/8/docs/api/java/time/LocalDateTime.html)>?  <br><br><br>
| [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)| [jvm]  <br>Content  <br>open operator override fun [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [stringify](stringify.md)| [jvm]  <br>Brief description  <br><br><br>字符串化<br><br>  <br>Content  <br>open override fun [stringify](stringify.md)(value: [LocalDateTime](https://docs.oracle.com/javase/8/docs/api/java/time/LocalDateTime.html)?): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>
| [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>

