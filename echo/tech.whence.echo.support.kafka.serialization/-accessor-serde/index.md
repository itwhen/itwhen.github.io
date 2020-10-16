---
title: AccessorSerde -
---
//[echo](../../index.md)/[tech.whence.echo.support.kafka.serialization](../index.md)/[AccessorSerde](index.md)



# AccessorSerde  
 [jvm] 

数据序列反序列化器

class [AccessorSerde](index.md) : Serde<[Accessor](../../tech.whence.echo.container.accessor/-accessor/index.md)>    


## Constructors  
  
|  Name|  Summary| 
|---|---|
| [AccessorSerde](-accessor-serde.md)|  [jvm] fun [AccessorSerde](-accessor-serde.md)()   <br>


## Functions  
  
|  Name|  Summary| 
|---|---|
| [close](close.md)| [jvm]  <br>Brief description  <br><br><br>关闭<br><br>  <br>Content  <br>open override fun [close](close.md)()  <br><br><br>
| [configure](configure.md)| [jvm]  <br>Brief description  <br><br><br>配置<br><br>  <br>Content  <br>open override fun [configure](configure.md)(configs: [Map](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)<[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), *>, isKey: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html))  <br><br><br>
| [deserializer](deserializer.md)| [jvm]  <br>Brief description  <br><br><br>反序列化器<br><br>  <br>Content  <br>open override fun [deserializer](deserializer.md)(): Deserializer<[Accessor](../../tech.whence.echo.container.accessor/-accessor/index.md)>  <br><br><br>
| [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)| [jvm]  <br>Content  <br>open operator override fun [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [serializer](serializer.md)| [jvm]  <br>Brief description  <br><br><br>序列化器<br><br>  <br>Content  <br>open override fun [serializer](serializer.md)(): Serializer<[Accessor](../../tech.whence.echo.container.accessor/-accessor/index.md)>  <br><br><br>
| [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>

