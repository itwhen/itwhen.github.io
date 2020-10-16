---
title: KeyValueHandler -
---
//[echo](../../../index.md)/[tech.whence.echo.dal.entity](../../index.md)/[EntityAccessor](../index.md)/[KeyValueHandler](index.md)



# KeyValueHandler  
 [jvm] 

键值处理器

interface [KeyValueHandler](index.md)<[V](index.md)>   


## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| V| <br><br><br><br>
  


## Types  
  
|  Name|  Summary| 
|---|---|
| [Companion](-companion/index.md)| [jvm]  <br>Content  <br>object [Companion](-companion/index.md)  <br><br><br>


## Functions  
  
|  Name|  Summary| 
|---|---|
| [equals](../../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)| [jvm]  <br>Content  <br>open operator override fun [equals](../../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [filter](filter.md)| [jvm]  <br>Brief description  <br><br><br>过滤<br><br>  <br>Content  <br>open fun [filter](filter.md)(key: [Key](../../../tech.whence.echo.dal.schema.key/-key/index.md), original: [Accessor](../../../tech.whence.echo.container.accessor/-accessor/index.md), creating: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [hashCode](../../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [hashCode](../../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [postprocess](postprocess.md)| [jvm]  <br>Brief description  <br><br><br>后置处理<br><br>  <br>Content  <br>abstract fun [postprocess](postprocess.md)(key: [Key](../../../tech.whence.echo.dal.schema.key/-key/index.md), value: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [V](index.md)?  <br><br><br>
| [preprocess](preprocess.md)| [jvm]  <br>Brief description  <br><br><br>前置处理<br><br>  <br>Content  <br>open fun [preprocess](preprocess.md)(key: [Key](../../../tech.whence.echo.dal.schema.key/-key/index.md), value: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?  <br><br><br>
| [toString](../../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [toString](../../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>

