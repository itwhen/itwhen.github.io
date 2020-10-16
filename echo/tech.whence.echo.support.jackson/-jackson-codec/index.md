---
title: JacksonCodec -
---
//[echo](../../index.md)/[tech.whence.echo.support.jackson](../index.md)/[JacksonCodec](index.md)



# JacksonCodec  
 [jvm] 

Json解编器

class [JacksonCodec](index.md) : JsonCodec   


## Constructors  
  
|  Name|  Summary| 
|---|---|
| [JacksonCodec](-jackson-codec.md)|  [jvm] fun [JacksonCodec](-jackson-codec.md)()   <br>


## Types  
  
|  Name|  Summary| 
|---|---|
| [Companion](-companion/index.md)| [jvm]  <br>Content  <br>object [Companion](-companion/index.md)  <br><br><br>


## Functions  
  
|  Name|  Summary| 
|---|---|
| [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)| [jvm]  <br>Content  <br>open operator override fun [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [fromBuffer](from-buffer.md)| [jvm]  <br>Brief description  <br><br><br>解码为指定对象<br><br>  <br>Content  <br>open override fun <[T](from-buffer.md) : [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)> [fromBuffer](from-buffer.md)(data: Buffer, declarer: [Class](https://docs.oracle.com/javase/8/docs/api/java/lang/Class.html)<[T](from-buffer.md)>): [T](from-buffer.md)  <br><br><br>
| [fromString](from-string.md)| [jvm]  <br>Brief description  <br><br><br>解码为指定对象<br><br>  <br>Content  <br>open override fun <[T](from-string.md) : [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)> [fromString](from-string.md)(data: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), declarer: [Class](https://docs.oracle.com/javase/8/docs/api/java/lang/Class.html)<[T](from-string.md)>): [T](from-string.md)  <br><br><br>
| [fromValue](from-value.md)| [jvm]  <br>Brief description  <br><br><br>解码为指定对象<br><br>  <br>Content  <br>open override fun <[T](from-value.md) : [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)> [fromValue](from-value.md)(data: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?, declarer: [Class](https://docs.oracle.com/javase/8/docs/api/java/lang/Class.html)<[T](from-value.md)>): [T](from-value.md)  <br><br><br>
| [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [toBuffer](index.md#io.vertx.core.spi.json/JsonCodec/toBuffer/#kotlin.Any/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [toBuffer](index.md#io.vertx.core.spi.json/JsonCodec/toBuffer/#kotlin.Any/PointingToDeclaration/)(p0: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)): Buffer  <br><br><br>[jvm]  <br>Brief description  <br><br><br>编码为缓冲<br><br>  <br>Content  <br>open override fun [toBuffer](to-buffer.md)(data: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html), pretty: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)): Buffer  <br><br><br>
| [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br>open override fun [toString](index.md#io.vertx.core.spi.json/JsonCodec/toString/#kotlin.Any/PointingToDeclaration/)(p0: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>[jvm]  <br>Brief description  <br><br><br>编码为字符串<br><br>  <br>Content  <br>open override fun [toString](to-string.md)(data: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html), pretty: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>

