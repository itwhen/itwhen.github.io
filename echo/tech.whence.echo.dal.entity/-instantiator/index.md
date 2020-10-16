---
title: Instantiator -
---
//[echo](../../index.md)/[tech.whence.echo.dal.entity](../index.md)/[Instantiator](index.md)



# Instantiator  
 [jvm] 

实例化器

interface [Instantiator](index.md)<[D](index.md), [E](index.md) : [Entity](../-entity/index.md)>   


## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| D| <br><br>待实例化数据类型<br><br>
| E| <br><br>: Entity  实体类型<br><br>
  


## Types  
  
|  Name|  Summary| 
|---|---|
| [Companion](-companion/index.md)| [jvm]  <br>Content  <br>object [Companion](-companion/index.md)  <br><br><br>


## Functions  
  
|  Name|  Summary| 
|---|---|
| [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)| [jvm]  <br>Content  <br>open operator override fun [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [instantiate](instantiate.md)| [jvm]  <br>Brief description  <br><br><br>实例化指定数据<br><br>  <br>Content  <br>abstract fun [instantiate](instantiate.md)(data: [D](index.md)): [E](index.md)  <br><br><br>
| [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>


## Properties  
  
|  Name|  Summary| 
|---|---|
| [declarer](index.md#tech.whence.echo.dal.entity/Instantiator/declarer/#/PointingToDeclaration/)|  [jvm] <br><br>KClass<out E> 实体类<br><br>abstract val [declarer](index.md#tech.whence.echo.dal.entity/Instantiator/declarer/#/PointingToDeclaration/): [KClass](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-class/index.html)<[E](index.md)>   <br>

