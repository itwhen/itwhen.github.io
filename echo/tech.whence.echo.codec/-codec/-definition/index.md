---
title: Definition -
---
//[echo](../../../index.md)/[tech.whence.echo.codec](../../index.md)/[Codec](../index.md)/[Definition](index.md)



# Definition  
 [jvm] 

解编器定义

open class [Definition](index.md)(**name**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), **type**: [KClass](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-class/index.html)<*>, **declarer**: [KClass](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-class/index.html)<*>?, **property**: [KProperty](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-property/index.html)<*>?, **annotations**: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[Annotation](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-annotation/index.html)>)   


## Constructors  
  
|  Name|  Summary| 
|---|---|
| [Definition](-definition.md)|  [jvm] <br><br><br><br>fun [Definition](-definition.md)(name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), type: [KClass](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-class/index.html)<*>, declarer: [KClass](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-class/index.html)<*>?, property: [KProperty](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-property/index.html)<*>?, annotations: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[Annotation](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-annotation/index.html)>)   <br>


## Types  
  
|  Name|  Summary| 
|---|---|
| [Companion](-companion/index.md)| [jvm]  <br>Content  <br>object [Companion](-companion/index.md)  <br><br><br>


## Functions  
  
|  Name|  Summary| 
|---|---|
| [annotate](annotate.md)| [jvm]  <br>Brief description  <br><br><br>取相关字段指定注解<br><br>  <br>Content  <br>inline fun <[T](annotate.md) : [Annotation](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-annotation/index.html)> [annotate](annotate.md)(): [T](annotate.md)?  <br><br><br>
| [belong](belong.md)| [jvm]  <br>Brief description  <br><br><br>判断是否是指定类型<br><br>  <br>Content  <br>fun [belong](belong.md)(type: [KClass](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-class/index.html)<*>): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [equals](../../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)| [jvm]  <br>Content  <br>open operator override fun [equals](../../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [fit](fit.md)| [jvm]  <br>Brief description  <br><br><br>判断指定值是否无需解析<br><br>  <br>Content  <br>fun [fit](fit.md)(value: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [hashCode](../../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [hashCode](../../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [respond](respond.md)| [jvm]  <br>Brief description  <br><br><br>判断是否由指定类型定义<br><br>  <br>Content  <br>fun [respond](respond.md)(declarer: [KClass](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-class/index.html)<*>): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [toString](../../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [toString](../../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>


## Properties  
  
|  Name|  Summary| 
|---|---|
| [annotations](index.md#tech.whence.echo.codec/Codec.Definition/annotations/#/PointingToDeclaration/)|  [jvm] <br><br>List<Annotation>? 相关注解<br><br>open val [annotations](index.md#tech.whence.echo.codec/Codec.Definition/annotations/#/PointingToDeclaration/): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[Annotation](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-annotation/index.html)>   <br>
| [declarer](index.md#tech.whence.echo.codec/Codec.Definition/declarer/#/PointingToDeclaration/)|  [jvm] <br><br>KClass<*>? 所属类<br><br>open val [declarer](index.md#tech.whence.echo.codec/Codec.Definition/declarer/#/PointingToDeclaration/): [KClass](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-class/index.html)<*>?   <br>
| [name](index.md#tech.whence.echo.codec/Codec.Definition/name/#/PointingToDeclaration/)|  [jvm] <br><br>String 名称<br><br>open val [name](index.md#tech.whence.echo.codec/Codec.Definition/name/#/PointingToDeclaration/): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)   <br>
| [property](index.md#tech.whence.echo.codec/Codec.Definition/property/#/PointingToDeclaration/)|  [jvm] <br><br>KProperty<*>? 相关字段<br><br>open val [property](index.md#tech.whence.echo.codec/Codec.Definition/property/#/PointingToDeclaration/): [KProperty](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-property/index.html)<*>?   <br>
| [type](index.md#tech.whence.echo.codec/Codec.Definition/type/#/PointingToDeclaration/)|  [jvm] <br><br>KClass<*> 指定解析类型<br><br>open val [type](index.md#tech.whence.echo.codec/Codec.Definition/type/#/PointingToDeclaration/): [KClass](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-class/index.html)<*>   <br>


## Inheritors  
  
|  Name| 
|---|
| [Key](../../../tech.whence.echo.dal.schema.key/-key/index.md)

