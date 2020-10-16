---
title: Decoder -
---
//[echo](../../index.md)/[tech.whence.echo.codec](../index.md)/[Decoder](index.md)



# Decoder  
 [jvm] 

解码器 提供转化任意值到指定类型的能力 能力不足时返回空值

interface [Decoder](index.md)<[T](index.md), out [P](index.md)>   


## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| P| <br><br>可转值数组类型<br><br>
| T| <br><br>可转值类型<br><br>
  


## Types  
  
|  Name|  Summary| 
|---|---|
| [Companion](-companion/index.md)| [jvm]  <br>Content  <br>object [Companion](-companion/index.md)  <br><br><br>


## Functions  
  
|  Name|  Summary| 
|---|---|
| [decode](decode.md)| [jvm]  <br>Brief description  <br><br><br>转换指定值到指定类型<br><br>  <br>Content  <br>abstract fun [decode](decode.md)(value: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [T](index.md)?  <br><br><br>[jvm]  <br>Brief description  <br><br><br>转换指定值到指定类型后继续下一步骤<br><br>  <br>Content  <br>open fun <[R](decode.md)> [decode](decode.md)(value: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?, next: [T](index.md).() -> [R](decode.md)?): [R](decode.md)?  <br><br><br>
| [decodes](decodes.md)| [jvm]  <br>Brief description  <br><br><br>转换指定值到指定类型数组<br><br>  <br>Content  <br>abstract fun [decodes](decodes.md)(value: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [P](index.md)?  <br><br><br>
| [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)| [jvm]  <br>Content  <br>open operator override fun [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [stringify](stringify.md)| [jvm]  <br>Brief description  <br><br><br>字符串化<br><br>  <br>Content  <br>open fun [stringify](stringify.md)(value: [T](index.md)?): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>
| [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>


## Inheritors  
  
|  Name| 
|---|
| [BigDecimalDecoder](../../tech.whence.echo.codec.decoder/-big-decimal-decoder/index.md)
| [BigIntegerDecoder](../../tech.whence.echo.codec.decoder/-big-integer-decoder/index.md)
| [BooleanDecoder](../../tech.whence.echo.codec.decoder/-boolean-decoder/index.md)
| [ByteDecoder](../../tech.whence.echo.codec.decoder/-byte-decoder/index.md)
| [CharDecoder](../../tech.whence.echo.codec.decoder/-char-decoder/index.md)
| [DateDecoder](../../tech.whence.echo.codec.decoder/-date-decoder/index.md)
| [DoubleDecoder](../../tech.whence.echo.codec.decoder/-double-decoder/index.md)
| [DurationDecoder](../../tech.whence.echo.codec.decoder/-duration-decoder/index.md)
| [FloatDecoder](../../tech.whence.echo.codec.decoder/-float-decoder/index.md)
| [InstantDecoder](../../tech.whence.echo.codec.decoder/-instant-decoder/index.md)
| [IntDecoder](../../tech.whence.echo.codec.decoder/-int-decoder/index.md)
| [LocalDateDecoder](../../tech.whence.echo.codec.decoder/-local-date-decoder/index.md)
| [LocalDateTimeDecoder](../../tech.whence.echo.codec.decoder/-local-date-time-decoder/index.md)
| [LocalTimeDecoder](../../tech.whence.echo.codec.decoder/-local-time-decoder/index.md)
| [LongDecoder](../../tech.whence.echo.codec.decoder/-long-decoder/index.md)
| [PeriodDecoder](../../tech.whence.echo.codec.decoder/-period-decoder/index.md)
| [ShortDecoder](../../tech.whence.echo.codec.decoder/-short-decoder/index.md)
| [StringDecoder](../../tech.whence.echo.codec.decoder/-string-decoder/index.md)
| [UByteDecoder](../../tech.whence.echo.codec.decoder/-u-byte-decoder/index.md)
| [UIntDecoder](../../tech.whence.echo.codec.decoder/-u-int-decoder/index.md)
| [ULongDecoder](../../tech.whence.echo.codec.decoder/-u-long-decoder/index.md)
| [UShortDecoder](../../tech.whence.echo.codec.decoder/-u-short-decoder/index.md)

