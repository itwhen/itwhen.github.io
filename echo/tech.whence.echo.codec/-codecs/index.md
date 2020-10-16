---
title: Codecs -
---
//[echo](../../index.md)/[tech.whence.echo.codec](../index.md)/[Codecs](index.md)



# Codecs  
 [jvm] 

解编器容器

class [Codecs](index.md)(**name**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html))   


## Constructors  
  
|  Name|  Summary| 
|---|---|
| [Codecs](-codecs.md)|  [jvm] <br><br><br><br>fun [Codecs](-codecs.md)(name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html))   <br>


## Types  
  
|  Name|  Summary| 
|---|---|
| [Companion](-companion/index.md)| [jvm]  <br>Content  <br>object [Companion](-companion/index.md)  <br><br><br>


## Functions  
  
|  Name|  Summary| 
|---|---|
| [clear](clear.md)| [jvm]  <br>Brief description  <br><br><br>清理所有注册数据<br><br>  <br>Content  <br>fun [clear](clear.md)(): [Codecs](index.md)  <br><br><br>
| [decode](decode.md)| [jvm]  <br>Brief description  <br><br><br>解码指定值<br><br>  <br>Content  <br>fun [decode](decode.md)(definition: [Codec.Definition](../-codec/-definition/index.md), value: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?  <br><br><br>
| [encode](encode.md)| [jvm]  <br>Brief description  <br><br><br>编码指定值<br><br>  <br>Content  <br>fun [encode](encode.md)(definition: [Codec.Definition](../-codec/-definition/index.md), value: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?  <br><br><br>
| [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)| [jvm]  <br>Content  <br>open operator override fun [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [merge](merge.md)| [jvm]  <br>Brief description  <br><br><br>合并解编器<br><br>  <br>Content  <br>fun [merge](merge.md)(codecs: [Codecs](index.md)): [Codecs](index.md)  <br><br><br>
| [process](process.md)| [jvm]  <br>Brief description  <br><br><br>设置指定类型处理器 若为内置时不允许设置 若存在指定类型时将覆盖之<br><br>  <br>Content  <br>fun [process](process.md)(target: [KClass](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-class/index.html)<*>, processor: [Codec](../-codec/index.md)): [Codecs](index.md)  <br><br><br>
| [register](register.md)| [jvm]  <br>Brief description  <br><br><br>注册解编器 根据解编器身份自动设置<br><br>  <br>Content  <br>fun [register](register.md)(vararg codecs: [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<out [Codec](../-codec/index.md)>): [Codecs](index.md)  <br><br><br>[jvm]  <br>Brief description  <br><br><br>注册解编器类<br><br>  <br>Content  <br>fun [register](register.md)(codec: [KClass](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-class/index.html)<out [Codec](../-codec/index.md)>): [Codecs](index.md)  <br><br><br>[jvm]  <br>Brief description  <br><br><br>注册解码器 将解码器转换为解码器再注册<br><br>  <br>Content  <br>inline fun <[T](register.md)> [register](register.md)(decoder: [Decoder](../-decoder/index.md)<[T](register.md), *>): [Codecs](index.md)  <br><br><br>
| [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>
| [transfer](transfer.md)| [jvm]  <br>Brief description  <br><br><br>新增解编器 若为内置时不允许设置 若已存在则忽略<br><br>  <br>Content  <br>fun [transfer](transfer.md)(transfer: [Codec](../-codec/index.md)): [Codecs](index.md)  <br><br><br>


## Properties  
  
|  Name|  Summary| 
|---|---|
| [builtin](index.md#tech.whence.echo.codec/Codecs/builtin/#/PointingToDeclaration/)|  [jvm] <br><br>Boolean 是否是内置的<br><br>var [builtin](index.md#tech.whence.echo.codec/Codecs/builtin/#/PointingToDeclaration/): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)   <br>
| [debug](index.md#tech.whence.echo.codec/Codecs/debug/#/PointingToDeclaration/)|  [jvm] <br><br>Boolean 是否调试模式<br><br>var [debug](index.md#tech.whence.echo.codec/Codecs/debug/#/PointingToDeclaration/): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)   <br>
| [name](index.md#tech.whence.echo.codec/Codecs/name/#/PointingToDeclaration/)|  [jvm] <br><br>String 当前容器名称<br><br>val [name](index.md#tech.whence.echo.codec/Codecs/name/#/PointingToDeclaration/): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)   <br>
| [processable](index.md#tech.whence.echo.codec/Codecs/processable/#/PointingToDeclaration/)|  [jvm] <br><br>Int 类型处理器数量<br><br>val [processable](index.md#tech.whence.echo.codec/Codecs/processable/#/PointingToDeclaration/): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)   <br>
| [transferable](index.md#tech.whence.echo.codec/Codecs/transferable/#/PointingToDeclaration/)|  [jvm] <br><br>Int 解编器数量<br><br>val [transferable](index.md#tech.whence.echo.codec/Codecs/transferable/#/PointingToDeclaration/): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)   <br>

