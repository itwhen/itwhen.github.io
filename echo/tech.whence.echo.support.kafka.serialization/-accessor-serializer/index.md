---
title: AccessorSerializer -
---
//[echo](../../index.md)/[tech.whence.echo.support.kafka.serialization](../index.md)/[AccessorSerializer](index.md)



# AccessorSerializer  
 [jvm] 

数据序列化器

class [AccessorSerializer](index.md) : Serializer<[Accessor](../../tech.whence.echo.container.accessor/-accessor/index.md)>    


## Constructors  
  
|  Name|  Summary| 
|---|---|
| [AccessorSerializer](-accessor-serializer.md)|  [jvm] fun [AccessorSerializer](-accessor-serializer.md)()   <br>


## Functions  
  
|  Name|  Summary| 
|---|---|
| [close](index.md#org.apache.kafka.common.serialization/Serializer/close/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [close](index.md#org.apache.kafka.common.serialization/Serializer/close/#/PointingToDeclaration/)()  <br><br><br>
| [configure](configure.md)| [jvm]  <br>Brief description  <br><br><br>配置<br><br>  <br>Content  <br>open override fun [configure](configure.md)(configs: [Map](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)<[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), *>, isKey: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html))  <br><br><br>
| [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)| [jvm]  <br>Content  <br>open operator override fun [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [serialize](serialize.md)| [jvm]  <br>Brief description  <br><br><br>序列化<br><br>  <br>Content  <br>open override fun [serialize](serialize.md)(topic: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, data: [Accessor](../../tech.whence.echo.container.accessor/-accessor/index.md)): [ByteArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte-array/index.html)?  <br><br><br>[jvm]  <br>Content  <br>open override fun [serialize](index.md#org.apache.kafka.common.serialization/Serializer/serialize/#kotlin.String#org.apache.kafka.common.header.Headers#tech.whence.echo.container.accessor.Accessor/PointingToDeclaration/)(p0: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), p1: Headers, p2: [Accessor](../../tech.whence.echo.container.accessor/-accessor/index.md)): [ByteArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte-array/index.html)  <br><br><br>
| [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>

