---
title: Codec -
---
//[echo](../../index.md)/[tech.whence.echo.codec](../index.md)/[Codec](index.md)



# Codec  
 [jvm] 

编解器 将数据源视作黑箱 取数据并解码出来呈现 编码封装数据存入数据源

interface [Codec](index.md) : [Namer](../../tech.whence.echo.definition/-namer/index.md)   


## Types  
  
|  Name|  Summary| 
|---|---|
| [Companion](-companion/index.md)| [jvm]  <br>Content  <br>object [Companion](-companion/index.md)  <br><br><br>
| [Definition](-definition/index.md)| [jvm]  <br>Brief description  <br><br><br>解编器定义<br><br>  <br>Content  <br>open class [Definition](-definition/index.md)(**name**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), **type**: [KClass](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-class/index.html)<*>, **declarer**: [KClass](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-class/index.html)<*>?, **property**: [KProperty](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-property/index.html)<*>?, **annotations**: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[Annotation](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-annotation/index.html)>)  <br><br><br>
| [Identity](-identity/index.md)| [jvm]  <br>Brief description  <br><br><br>解编器角色<br><br>  <br>Content  <br>enum [Identity](-identity/index.md) : [Enum](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-enum/index.html)<[Codec.Identity](-identity/index.md)>   <br><br><br>
| [Method](-method/index.md)| [jvm]  <br>Brief description  <br><br><br>编解方式<br><br>  <br>Content  <br>enum [Method](-method/index.md) : [Enum](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-enum/index.html)<[Codec.Method](-method/index.md)>   <br><br><br>


## Functions  
  
|  Name|  Summary| 
|---|---|
| [convert](convert.md)| [jvm]  <br>Brief description  <br><br><br>根据指定上下文解编码<br><br>  <br>Content  <br>open fun [convert](convert.md)(context: [Context](../-context/index.md)): [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?  <br><br><br>
| [decode](decode.md)| [jvm]  <br>Brief description  <br><br><br>根据定义将指定值解码<br><br>  <br>Content  <br>open fun [decode](decode.md)(definition: [Codec.Definition](-definition/index.md), value: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)): [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?  <br><br><br>
| [encode](encode.md)| [jvm]  <br>Brief description  <br><br><br>根据定义将指定值编码<br><br>  <br>Content  <br>open fun [encode](encode.md)(definition: [Codec.Definition](-definition/index.md), value: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)): [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?  <br><br><br>
| [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)| [jvm]  <br>Content  <br>open operator override fun [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [identify](identify.md)| [jvm]  <br>Brief description  <br><br><br>获取当前类角色<br><br>  <br>Content  <br>open fun [identify](identify.md)(): [Codec.Identity](-identity/index.md)  <br><br><br>
| [name](name.md)| [jvm]  <br>Brief description  <br><br><br>解编器名称<br><br>  <br>Content  <br>open override fun [name](name.md)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>
| [process](process.md)| [jvm]  <br>Brief description  <br><br><br>获取当前类可处理类型<br><br>  <br>Content  <br>open fun [process](process.md)(): [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<out [KClass](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-class/index.html)<*>>  <br><br><br>
| [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>


## Inheritors  
  
|  Name| 
|---|
| [Entitifier](../../tech.whence.echo.container.accessor/-entitifier/-entity-codec/index.md)
| [Entitifier](../../tech.whence.echo.container.accessor/-entitifier/-const-codec/index.md)
| [ConstCodec](../../tech.whence.echo.support.jdbc.codec/-const-codec/index.md)
| [DateCodec](../../tech.whence.echo.support.jdbc.codec/-date-codec/index.md)
| [EntityCodec](../../tech.whence.echo.support.jdbc.codec/-entity-codec/index.md)
| [DateCodec](../../tech.whence.echo.support.mongo.codec/-date-codec/index.md)
| [NumberCodec](../../tech.whence.echo.support.mongo.codec/-number-codec/index.md)

