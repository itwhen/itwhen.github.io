---
title: LocalTimeDeserializer -
---
//[echo](../../index.md)/[tech.whence.echo.support.jackson](../index.md)/[LocalTimeDeserializer](index.md)



# LocalTimeDeserializer  
 [jvm] 

时间反序列化器

class [LocalTimeDeserializer](index.md) : JsonDeserializer<[LocalTime](https://docs.oracle.com/javase/8/docs/api/java/time/LocalTime.html)>    


## Constructors  
  
|  Name|  Summary| 
|---|---|
| [LocalTimeDeserializer](-local-time-deserializer.md)|  [jvm] fun [LocalTimeDeserializer](-local-time-deserializer.md)()   <br>


## Functions  
  
|  Name|  Summary| 
|---|---|
| [deserialize](deserialize.md)| [jvm]  <br>Brief description  <br><br><br>反序列化<br><br>  <br>Content  <br>open override fun [deserialize](deserialize.md)(parser: JsonParser, context: DeserializationContext): [LocalTime](https://docs.oracle.com/javase/8/docs/api/java/time/LocalTime.html)?  <br><br><br>[jvm]  <br>Content  <br>open override fun [deserialize](index.md#com.fasterxml.jackson.databind/JsonDeserializer/deserialize/#com.fasterxml.jackson.core.JsonParser#com.fasterxml.jackson.databind.DeserializationContext#java.time.LocalTime/PointingToDeclaration/)(p0: JsonParser, p1: DeserializationContext, p2: [LocalTime](https://docs.oracle.com/javase/8/docs/api/java/time/LocalTime.html)): [LocalTime](https://docs.oracle.com/javase/8/docs/api/java/time/LocalTime.html)  <br><br><br>
| [deserializeWithType](index.md#com.fasterxml.jackson.databind/JsonDeserializer/deserializeWithType/#com.fasterxml.jackson.core.JsonParser#com.fasterxml.jackson.databind.DeserializationContext#com.fasterxml.jackson.databind.jsontype.TypeDeserializer/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [deserializeWithType](index.md#com.fasterxml.jackson.databind/JsonDeserializer/deserializeWithType/#com.fasterxml.jackson.core.JsonParser#com.fasterxml.jackson.databind.DeserializationContext#com.fasterxml.jackson.databind.jsontype.TypeDeserializer/PointingToDeclaration/)(p0: JsonParser, p1: DeserializationContext, p2: TypeDeserializer): [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)  <br>open override fun [deserializeWithType](index.md#com.fasterxml.jackson.databind/JsonDeserializer/deserializeWithType/#com.fasterxml.jackson.core.JsonParser#com.fasterxml.jackson.databind.DeserializationContext#com.fasterxml.jackson.databind.jsontype.TypeDeserializer#java.time.LocalTime/PointingToDeclaration/)(p0: JsonParser, p1: DeserializationContext, p2: TypeDeserializer, p3: [LocalTime](https://docs.oracle.com/javase/8/docs/api/java/time/LocalTime.html)): [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)  <br><br><br>
| [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)| [jvm]  <br>Content  <br>open operator override fun [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [findBackReference](index.md#com.fasterxml.jackson.databind/JsonDeserializer/findBackReference/#kotlin.String/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [findBackReference](index.md#com.fasterxml.jackson.databind/JsonDeserializer/findBackReference/#kotlin.String/PointingToDeclaration/)(p0: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): SettableBeanProperty  <br><br><br>
| [getDelegatee](index.md#com.fasterxml.jackson.databind/JsonDeserializer/getDelegatee/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [getDelegatee](index.md#com.fasterxml.jackson.databind/JsonDeserializer/getDelegatee/#/PointingToDeclaration/)(): JsonDeserializer<*>  <br><br><br>
| [getEmptyAccessPattern](index.md#com.fasterxml.jackson.databind/JsonDeserializer/getEmptyAccessPattern/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [getEmptyAccessPattern](index.md#com.fasterxml.jackson.databind/JsonDeserializer/getEmptyAccessPattern/#/PointingToDeclaration/)(): AccessPattern  <br><br><br>
| [getEmptyValue](index.md#com.fasterxml.jackson.databind/JsonDeserializer/getEmptyValue/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>~~open~~ ~~override~~ ~~fun~~ [~~getEmptyValue~~](index.md#com.fasterxml.jackson.databind/JsonDeserializer/getEmptyValue/#/PointingToDeclaration/)~~(~~~~)~~~~:~~ [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)  <br>open override fun [getEmptyValue](index.md#com.fasterxml.jackson.databind/JsonDeserializer/getEmptyValue/#com.fasterxml.jackson.databind.DeserializationContext/PointingToDeclaration/)(p0: DeserializationContext): [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)  <br><br><br>
| [getKnownPropertyNames](index.md#com.fasterxml.jackson.databind/JsonDeserializer/getKnownPropertyNames/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [getKnownPropertyNames](index.md#com.fasterxml.jackson.databind/JsonDeserializer/getKnownPropertyNames/#/PointingToDeclaration/)(): [MutableCollection](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-collection/index.html)<[Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>  <br><br><br>
| [getNullAccessPattern](index.md#com.fasterxml.jackson.databind/JsonDeserializer/getNullAccessPattern/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [getNullAccessPattern](index.md#com.fasterxml.jackson.databind/JsonDeserializer/getNullAccessPattern/#/PointingToDeclaration/)(): AccessPattern  <br><br><br>
| [getNullValue](index.md#com.fasterxml.jackson.databind/JsonDeserializer/getNullValue/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>~~open~~ ~~override~~ ~~fun~~ [~~getNullValue~~](index.md#com.fasterxml.jackson.databind/JsonDeserializer/getNullValue/#/PointingToDeclaration/)~~(~~~~)~~~~:~~ [LocalTime](https://docs.oracle.com/javase/8/docs/api/java/time/LocalTime.html)  <br>open override fun [getNullValue](index.md#com.fasterxml.jackson.databind/JsonDeserializer/getNullValue/#com.fasterxml.jackson.databind.DeserializationContext/PointingToDeclaration/)(p0: DeserializationContext): [LocalTime](https://docs.oracle.com/javase/8/docs/api/java/time/LocalTime.html)  <br><br><br>
| [getObjectIdReader](index.md#com.fasterxml.jackson.databind/JsonDeserializer/getObjectIdReader/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [getObjectIdReader](index.md#com.fasterxml.jackson.databind/JsonDeserializer/getObjectIdReader/#/PointingToDeclaration/)(): ObjectIdReader  <br><br><br>
| [handledType](index.md#com.fasterxml.jackson.databind/JsonDeserializer/handledType/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [handledType](index.md#com.fasterxml.jackson.databind/JsonDeserializer/handledType/#/PointingToDeclaration/)(): [Class](https://docs.oracle.com/javase/8/docs/api/java/lang/Class.html)<*>  <br><br><br>
| [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [isCachable](index.md#com.fasterxml.jackson.databind/JsonDeserializer/isCachable/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [isCachable](index.md#com.fasterxml.jackson.databind/JsonDeserializer/isCachable/#/PointingToDeclaration/)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [replaceDelegatee](index.md#com.fasterxml.jackson.databind/JsonDeserializer/replaceDelegatee/#com.fasterxml.jackson.databind.JsonDeserializer[*]/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [replaceDelegatee](index.md#com.fasterxml.jackson.databind/JsonDeserializer/replaceDelegatee/#com.fasterxml.jackson.databind.JsonDeserializer[*]/PointingToDeclaration/)(p0: JsonDeserializer<*>): JsonDeserializer<*>  <br><br><br>
| [supportsUpdate](index.md#com.fasterxml.jackson.databind/JsonDeserializer/supportsUpdate/#com.fasterxml.jackson.databind.DeserializationConfig/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [supportsUpdate](index.md#com.fasterxml.jackson.databind/JsonDeserializer/supportsUpdate/#com.fasterxml.jackson.databind.DeserializationConfig/PointingToDeclaration/)(p0: DeserializationConfig): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>
| [unwrappingDeserializer](index.md#com.fasterxml.jackson.databind/JsonDeserializer/unwrappingDeserializer/#com.fasterxml.jackson.databind.util.NameTransformer/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [unwrappingDeserializer](index.md#com.fasterxml.jackson.databind/JsonDeserializer/unwrappingDeserializer/#com.fasterxml.jackson.databind.util.NameTransformer/PointingToDeclaration/)(p0: NameTransformer): JsonDeserializer<[LocalTime](https://docs.oracle.com/javase/8/docs/api/java/time/LocalTime.html)>  <br><br><br>
