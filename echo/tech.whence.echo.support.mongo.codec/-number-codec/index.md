---
title: NumberCodec -
---
//[echo](../../index.md)/[tech.whence.echo.support.mongo.codec](../index.md)/[NumberCodec](index.md)



# NumberCodec  
 [jvm] 

Number编解器

class [NumberCodec](index.md) : [Codec](../../tech.whence.echo.codec/-codec/index.md)   


## Constructors  
  
|  Name|  Summary| 
|---|---|
| [NumberCodec](-number-codec.md)|  [jvm] fun [NumberCodec](-number-codec.md)()   <br>


## Functions  
  
|  Name|  Summary| 
|---|---|
| [convert](../../tech.whence.echo.codec/-codec/convert.md)| [jvm]  <br>Brief description  <br><br><br>根据指定上下文解编码<br><br>  <br>Content  <br>open override fun [convert](../../tech.whence.echo.codec/-codec/convert.md)(context: [Context](../../tech.whence.echo.codec/-context/index.md)): [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?  <br><br><br>
| [decode](../../tech.whence.echo.codec/-codec/decode.md)| [jvm]  <br>Brief description  <br><br><br>根据定义将指定值解码<br><br>  <br>Content  <br>open override fun [decode](../../tech.whence.echo.codec/-codec/decode.md)(definition: [Codec.Definition](../../tech.whence.echo.codec/-codec/-definition/index.md), value: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)): [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?  <br><br><br>
| [encode](encode.md)| [jvm]  <br>Brief description  <br><br><br>根据定义将指定值编码<br><br>  <br>Content  <br>open override fun [encode](encode.md)(definition: [Codec.Definition](../../tech.whence.echo.codec/-codec/-definition/index.md), value: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)): [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?  <br><br><br>
| [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)| [jvm]  <br>Content  <br>open operator override fun [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [identify](../../tech.whence.echo.codec/-codec/identify.md)| [jvm]  <br>Brief description  <br><br><br>获取当前类角色<br><br>  <br>Content  <br>open override fun [identify](../../tech.whence.echo.codec/-codec/identify.md)(): [Codec.Identity](../../tech.whence.echo.codec/-codec/-identity/index.md)  <br><br><br>
| [name](../../tech.whence.echo.codec/-codec/name.md)| [jvm]  <br>Brief description  <br><br><br>解编器名称<br><br>  <br>Content  <br>open override fun [name](../../tech.whence.echo.codec/-codec/name.md)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>
| [process](../../tech.whence.echo.codec/-codec/process.md)| [jvm]  <br>Brief description  <br><br><br>获取当前类可处理类型<br><br>  <br>Content  <br>open override fun [process](../../tech.whence.echo.codec/-codec/process.md)(): [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<out [KClass](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-class/index.html)<*>>  <br><br><br>
| [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>

