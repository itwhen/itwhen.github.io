---
title: LocalTimeSerializer -
---
//[echo](../../index.md)/[tech.whence.echo.support.jackson](../index.md)/[LocalTimeSerializer](index.md)



# LocalTimeSerializer  
 [jvm] 

时间序列化器

class [LocalTimeSerializer](index.md) : JsonSerializer<[LocalTime](https://docs.oracle.com/javase/8/docs/api/java/time/LocalTime.html)>    


## Constructors  
  
|  Name|  Summary| 
|---|---|
| [LocalTimeSerializer](-local-time-serializer.md)|  [jvm] fun [LocalTimeSerializer](-local-time-serializer.md)()   <br>


## Functions  
  
|  Name|  Summary| 
|---|---|
| [acceptJsonFormatVisitor](index.md#com.fasterxml.jackson.databind/JsonSerializer/acceptJsonFormatVisitor/#com.fasterxml.jackson.databind.jsonFormatVisitors.JsonFormatVisitorWrapper#com.fasterxml.jackson.databind.JavaType/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [acceptJsonFormatVisitor](index.md#com.fasterxml.jackson.databind/JsonSerializer/acceptJsonFormatVisitor/#com.fasterxml.jackson.databind.jsonFormatVisitors.JsonFormatVisitorWrapper#com.fasterxml.jackson.databind.JavaType/PointingToDeclaration/)(p0: JsonFormatVisitorWrapper, p1: JavaType)  <br><br><br>
| [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)| [jvm]  <br>Content  <br>open operator override fun [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [getDelegatee](index.md#com.fasterxml.jackson.databind/JsonSerializer/getDelegatee/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [getDelegatee](index.md#com.fasterxml.jackson.databind/JsonSerializer/getDelegatee/#/PointingToDeclaration/)(): JsonSerializer<*>  <br><br><br>
| [handledType](index.md#com.fasterxml.jackson.databind/JsonSerializer/handledType/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [handledType](index.md#com.fasterxml.jackson.databind/JsonSerializer/handledType/#/PointingToDeclaration/)(): [Class](https://docs.oracle.com/javase/8/docs/api/java/lang/Class.html)<[LocalTime](https://docs.oracle.com/javase/8/docs/api/java/time/LocalTime.html)>  <br><br><br>
| [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [isEmpty](index.md#com.fasterxml.jackson.databind/JsonSerializer/isEmpty/#java.time.LocalTime/PointingToDeclaration/)| [jvm]  <br>Content  <br>~~open~~ ~~override~~ ~~fun~~ [~~isEmpty~~](index.md#com.fasterxml.jackson.databind/JsonSerializer/isEmpty/#java.time.LocalTime/PointingToDeclaration/)~~(~~~~p0~~~~:~~ [LocalTime](https://docs.oracle.com/javase/8/docs/api/java/time/LocalTime.html)~~)~~~~:~~ [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br>open override fun [isEmpty](index.md#com.fasterxml.jackson.databind/JsonSerializer/isEmpty/#com.fasterxml.jackson.databind.SerializerProvider#java.time.LocalTime/PointingToDeclaration/)(p0: SerializerProvider, p1: [LocalTime](https://docs.oracle.com/javase/8/docs/api/java/time/LocalTime.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [isUnwrappingSerializer](index.md#com.fasterxml.jackson.databind/JsonSerializer/isUnwrappingSerializer/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [isUnwrappingSerializer](index.md#com.fasterxml.jackson.databind/JsonSerializer/isUnwrappingSerializer/#/PointingToDeclaration/)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [properties](index.md#com.fasterxml.jackson.databind/JsonSerializer/properties/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [properties](index.md#com.fasterxml.jackson.databind/JsonSerializer/properties/#/PointingToDeclaration/)(): [MutableIterator](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-iterator/index.html)<PropertyWriter>  <br><br><br>
| [replaceDelegatee](index.md#com.fasterxml.jackson.databind/JsonSerializer/replaceDelegatee/#com.fasterxml.jackson.databind.JsonSerializer[*]/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [replaceDelegatee](index.md#com.fasterxml.jackson.databind/JsonSerializer/replaceDelegatee/#com.fasterxml.jackson.databind.JsonSerializer[*]/PointingToDeclaration/)(p0: JsonSerializer<*>): JsonSerializer<[LocalTime](https://docs.oracle.com/javase/8/docs/api/java/time/LocalTime.html)>  <br><br><br>
| [serialize](serialize.md)| [jvm]  <br>Brief description  <br><br><br>序列化<br><br>  <br>Content  <br>open override fun [serialize](serialize.md)(value: [LocalTime](https://docs.oracle.com/javase/8/docs/api/java/time/LocalTime.html), generator: JsonGenerator, provider: SerializerProvider)  <br><br><br>
| [serializeWithType](index.md#com.fasterxml.jackson.databind/JsonSerializer/serializeWithType/#java.time.LocalTime#com.fasterxml.jackson.core.JsonGenerator#com.fasterxml.jackson.databind.SerializerProvider#com.fasterxml.jackson.databind.jsontype.TypeSerializer/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [serializeWithType](index.md#com.fasterxml.jackson.databind/JsonSerializer/serializeWithType/#java.time.LocalTime#com.fasterxml.jackson.core.JsonGenerator#com.fasterxml.jackson.databind.SerializerProvider#com.fasterxml.jackson.databind.jsontype.TypeSerializer/PointingToDeclaration/)(p0: [LocalTime](https://docs.oracle.com/javase/8/docs/api/java/time/LocalTime.html), p1: JsonGenerator, p2: SerializerProvider, p3: TypeSerializer)  <br><br><br>
| [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>
| [unwrappingSerializer](index.md#com.fasterxml.jackson.databind/JsonSerializer/unwrappingSerializer/#com.fasterxml.jackson.databind.util.NameTransformer/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [unwrappingSerializer](index.md#com.fasterxml.jackson.databind/JsonSerializer/unwrappingSerializer/#com.fasterxml.jackson.databind.util.NameTransformer/PointingToDeclaration/)(p0: NameTransformer): JsonSerializer<[LocalTime](https://docs.oracle.com/javase/8/docs/api/java/time/LocalTime.html)>  <br><br><br>
| [usesObjectId](index.md#com.fasterxml.jackson.databind/JsonSerializer/usesObjectId/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [usesObjectId](index.md#com.fasterxml.jackson.databind/JsonSerializer/usesObjectId/#/PointingToDeclaration/)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [withFilterId](index.md#com.fasterxml.jackson.databind/JsonSerializer/withFilterId/#kotlin.Any/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [withFilterId](index.md#com.fasterxml.jackson.databind/JsonSerializer/withFilterId/#kotlin.Any/PointingToDeclaration/)(p0: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)): JsonSerializer<*>  <br><br><br>

