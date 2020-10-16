---
title: Pipelines -
---
//[echo](../../index.md)/[tech.whence.echo.job.stream.subscription](../index.md)/[Pipelines](index.md)



# Pipelines  
 [jvm] 

消息管道集合

class [Pipelines](index.md)(**data**: [Map](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)<[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), [Pipeline](../-pipeline/index.md)>, **modes**: [EnumSet](https://docs.oracle.com/javase/8/docs/api/java/util/EnumSet.html)<[Pipelines.Mode](-mode/index.md)>)   


## Constructors  
  
|  Name|  Summary| 
|---|---|
| [Pipelines](-pipelines.md)|  [jvm] <br><br><br><br>fun [Pipelines](-pipelines.md)(data: [Map](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)<[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), [Pipeline](../-pipeline/index.md)>, modes: [EnumSet](https://docs.oracle.com/javase/8/docs/api/java/util/EnumSet.html)<[Pipelines.Mode](-mode/index.md)>)   <br>


## Types  
  
|  Name|  Summary| 
|---|---|
| [Companion](-companion/index.md)| [jvm]  <br>Content  <br>object [Companion](-companion/index.md)  <br><br><br>
| [Mode](-mode/index.md)| [jvm]  <br>Brief description  <br><br><br>模式<br><br>  <br>Content  <br>enum [Mode](-mode/index.md) : [Enum](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-enum/index.html)<[Pipelines.Mode](-mode/index.md)>   <br><br><br>
| [Relocator](-relocator/index.md)| [jvm]  <br>Brief description  <br><br><br>重定位器<br><br>  <br>Content  <br>fun fun interface [Relocator](-relocator/index.md)  <br><br><br>


## Functions  
  
|  Name|  Summary| 
|---|---|
| [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)| [jvm]  <br>Content  <br>open operator override fun [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [fit](fit.md)| [jvm]  <br>Brief description  <br><br><br>判断是否符合指定模式<br><br>  <br>Content  <br>@[JvmOverloads](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-overloads/index.html)()  <br>  <br>fun [fit](fit.md)(mode: [Pipelines.Mode](-mode/index.md), exact: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [get](get.md)| [jvm]  <br>Brief description  <br><br><br>取指定管道<br><br>  <br>Content  <br>operator fun [get](get.md)(name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): [Pipeline](../-pipeline/index.md)?  <br><br><br>
| [getData](get-data.md)| [jvm]  <br>Brief description  <br><br><br>取所有管道<br><br>  <br>Content  <br>fun [getData](get-data.md)(): [Collection](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-collection/index.html)<[Pipeline](../-pipeline/index.md)>  <br><br><br>
| [getPartition](get-partition.md)| [jvm]  <br>Brief description  <br><br><br>取指定管道分区<br><br>  <br>Content  <br>fun [getPartition](get-partition.md)(name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): [Partitions](../-partitions/index.md)?  <br><br><br>
| [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [relocate](relocate.md)| [jvm]  <br>Brief description  <br><br><br>重定位<br><br>  <br>Content  <br>fun [relocate](relocate.md)(relocator: [Pipelines.Relocator](-relocator/index.md)): [Set](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-set/index.html)<[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)>  <br><br><br>
| [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>

