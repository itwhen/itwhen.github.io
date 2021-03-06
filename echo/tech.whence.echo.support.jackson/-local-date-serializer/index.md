---
title: LocalDateSerializer -
---
//[echo](../../index.md)/[tech.whence.echo.support.jackson](../index.md)/[LocalDateSerializer](index.md)



# LocalDateSerializer  
 [jvm] 

日期序列化器

class [LocalDateSerializer](index.md) : JsonSerializer<[LocalDate](https://docs.oracle.com/javase/8/docs/api/java/time/LocalDate.html)>    


## Constructors  
  
|  Name|  Summary| 
|---|---|
| [LocalDateSerializer](-local-date-serializer.md)|  [jvm] fun [LocalDateSerializer](-local-date-serializer.md)()   <br>


## Functions  
  
|  Name|  Summary| 
|---|---|
| [acceptJsonFormatVisitor](../-local-time-serializer/index.md#com.fasterxml.jackson.databind/JsonSerializer/acceptJsonFormatVisitor/#com.fasterxml.jackson.databind.jsonFormatVisitors.JsonFormatVisitorWrapper#com.fasterxml.jackson.databind.JavaType/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [acceptJsonFormatVisitor](../-local-time-serializer/index.md#com.fasterxml.jackson.databind/JsonSerializer/acceptJsonFormatVisitor/#com.fasterxml.jackson.databind.jsonFormatVisitors.JsonFormatVisitorWrapper#com.fasterxml.jackson.databind.JavaType/PointingToDeclaration/)(p0: JsonFormatVisitorWrapper, p1: JavaType)  <br><br><br>
| [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)| [jvm]  <br>Content  <br>open operator override fun [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [getDelegatee](../-local-time-serializer/index.md#com.fasterxml.jackson.databind/JsonSerializer/getDelegatee/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [getDelegatee](../-local-time-serializer/index.md#com.fasterxml.jackson.databind/JsonSerializer/getDelegatee/#/PointingToDeclaration/)(): JsonSerializer<*>  <br><br><br>
| [handledType](../-local-time-serializer/index.md#com.fasterxml.jackson.databind/JsonSerializer/handledType/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [handledType](../-local-time-serializer/index.md#com.fasterxml.jackson.databind/JsonSerializer/handledType/#/PointingToDeclaration/)(): [Class](https://docs.oracle.com/javase/8/docs/api/java/lang/Class.html)<[LocalDate](https://docs.oracle.com/javase/8/docs/api/java/time/LocalDate.html)>  <br><br><br>
| [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [isEmpty](index.md#com.fasterxml.jackson.databind/JsonSerializer/isEmpty/#java.time.LocalDate/PointingToDeclaration/)| [jvm]  <br>Content  <br>~~open~~ ~~override~~ ~~fun~~ [~~isEmpty~~](index.md#com.fasterxml.jackson.databind/JsonSerializer/isEmpty/#java.time.LocalDate/PointingToDeclaration/)~~(~~~~p0~~~~:~~ [LocalDate](https://docs.oracle.com/javase/8/docs/api/java/time/LocalDate.html)~~)~~~~:~~ [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br>open override fun [isEmpty](index.md#com.fasterxml.jackson.databind/JsonSerializer/isEmpty/#com.fasterxml.jackson.databind.SerializerProvider#java.time.LocalDate/PointingToDeclaration/)(p0: SerializerProvider, p1: [LocalDate](https://docs.oracle.com/javase/8/docs/api/java/time/LocalDate.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [isUnwrappingSerializer](../-local-time-serializer/index.md#com.fasterxml.jackson.databind/JsonSerializer/isUnwrappingSerializer/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [isUnwrappingSerializer](../-local-time-serializer/index.md#com.fasterxml.jackson.databind/JsonSerializer/isUnwrappingSerializer/#/PointingToDeclaration/)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [properties](../-local-time-serializer/index.md#com.fasterxml.jackson.databind/JsonSerializer/properties/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [properties](../-local-time-serializer/index.md#com.fasterxml.jackson.databind/JsonSerializer/properties/#/PointingToDeclaration/)(): [MutableIterator](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-iterator/index.html)<PropertyWriter>  <br><br><br>
| [replaceDelegatee](../-local-time-serializer/index.md#com.fasterxml.jackson.databind/JsonSerializer/replaceDelegatee/#com.fasterxml.jackson.databind.JsonSerializer[*]/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [replaceDelegatee](../-local-time-serializer/index.md#com.fasterxml.jackson.databind/JsonSerializer/replaceDelegatee/#com.fasterxml.jackson.databind.JsonSerializer[*]/PointingToDeclaration/)(p0: JsonSerializer<*>): JsonSerializer<[LocalDate](https://docs.oracle.com/javase/8/docs/api/java/time/LocalDate.html)>  <br><br><br>
| [serialize](serialize.md)| [jvm]  <br>Brief description  <br><br><br>序列化<br><br>  <br>Content  <br>open override fun [serialize](serialize.md)(value: [LocalDate](https://docs.oracle.com/javase/8/docs/api/java/time/LocalDate.html), generator: JsonGenerator, provider: SerializerProvider)  <br><br><br>
| [serializeWithType](index.md#com.fasterxml.jackson.databind/JsonSerializer/serializeWithType/#java.time.LocalDate#com.fasterxml.jackson.core.JsonGenerator#com.fasterxml.jackson.databind.SerializerProvider#com.fasterxml.jackson.databind.jsontype.TypeSerializer/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [serializeWithType](index.md#com.fasterxml.jackson.databind/JsonSerializer/serializeWithType/#java.time.LocalDate#com.fasterxml.jackson.core.JsonGenerator#com.fasterxml.jackson.databind.SerializerProvider#com.fasterxml.jackson.databind.jsontype.TypeSerializer/PointingToDeclaration/)(p0: [LocalDate](https://docs.oracle.com/javase/8/docs/api/java/time/LocalDate.html), p1: JsonGenerator, p2: SerializerProvider, p3: TypeSerializer)  <br><br><br>
| [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>
| [unwrappingSerializer](../-local-time-serializer/index.md#com.fasterxml.jackson.databind/JsonSerializer/unwrappingSerializer/#com.fasterxml.jackson.databind.util.NameTransformer/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [unwrappingSerializer](../-local-time-serializer/index.md#com.fasterxml.jackson.databind/JsonSerializer/unwrappingSerializer/#com.fasterxml.jackson.databind.util.NameTransformer/PointingToDeclaration/)(p0: NameTransformer): JsonSerializer<[LocalDate](https://docs.oracle.com/javase/8/docs/api/java/time/LocalDate.html)>  <br><br><br>
| [usesObjectId](../-local-time-serializer/index.md#com.fasterxml.jackson.databind/JsonSerializer/usesObjectId/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [usesObjectId](../-local-time-serializer/index.md#com.fasterxml.jackson.databind/JsonSerializer/usesObjectId/#/PointingToDeclaration/)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [withFilterId](../-local-time-serializer/index.md#com.fasterxml.jackson.databind/JsonSerializer/withFilterId/#kotlin.Any/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [withFilterId](../-local-time-serializer/index.md#com.fasterxml.jackson.databind/JsonSerializer/withFilterId/#kotlin.Any/PointingToDeclaration/)(p0: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)): JsonSerializer<*>  <br><br><br>

