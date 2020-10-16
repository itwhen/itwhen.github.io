---
title: Associations -
---
//[echo](../../index.md)/[tech.whence.echo.rpc.association](../index.md)/[Associations](index.md)



# Associations  
 [jvm] 

关联集合

class [Associations](index.md)<[E](index.md) : [Resource](../../tech.whence.echo.rpc.sample.resource/-resource/index.md), [R](index.md) : [ResourceData](../../tech.whence.echo.rpc.sample.resource/-resource-data/index.md)>   


## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| E| <br><br>当前实体<br><br>
| R| <br><br>当前响应<br><br>
  


## Constructors  
  
|  Name|  Summary| 
|---|---|
| [Associations](-associations.md)|  [jvm] <br><br>当前实体<br><br>fun [Associations](-associations.md)()   <br>


## Functions  
  
|  Name|  Summary| 
|---|---|
| [add](add.md)| [jvm]  <br>Brief description  <br><br><br>添加关联<br><br>  <br>Content  <br>inline fun <[F](add.md) : [ItemFacade](../../tech.whence.echo.rpc.sample.item/-item-facade/index.md)<*, *, *, [FR](add.md)>, [FR](add.md) : [ItemData](../../tech.whence.echo.rpc.sample.item/-item-data/index.md)> [add](add.md)(noinline facade: () -> [F](add.md), noinline inhere: ([E](index.md)) -> [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, noinline externalize: ([R](index.md), [FR](add.md)) -> [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)): [Associations](index.md)<[E](index.md), [R](index.md)>  <br><br><br>
| [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)| [jvm]  <br>Content  <br>open operator override fun [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [scan](scan.md)| [jvm]  <br>Brief description  <br><br><br>收集实体相关门面数据<br><br>  <br>Content  <br>suspend fun [scan](scan.md)(data: [E](index.md)): [Result.Single](../-result/-single/index.md)<[E](index.md), [R](index.md)>  <br><br><br>[jvm]  <br>Brief description  <br><br><br>收集分页实体内相关门面数据<br><br>  <br>Content  <br>suspend fun [scan](scan.md)(data: [Paginator](../../tech.whence.echo.container/-paginator/index.md)<[E](index.md)>): [Result.Multiple](../-result/-multiple/index.md)<[E](index.md), [R](index.md)>  <br>suspend fun [scan](scan.md)(data: [Entities](../../tech.whence.echo.dal.entity/-entities/index.md)<[E](index.md)>): [Result.Multiple](../-result/-multiple/index.md)<[E](index.md), [R](index.md)>  <br><br><br>
| [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>
| [valid](valid.md)| [jvm]  <br>Brief description  <br><br><br>检查实体相关门面数据是否有效<br><br>  <br>Content  <br>suspend fun [valid](valid.md)(data: [E](index.md))  <br>suspend fun [valid](valid.md)(data: [Entities](../../tech.whence.echo.dal.entity/-entities/index.md)<[E](index.md)>)  <br><br><br>


## Properties  
  
|  Name|  Summary| 
|---|---|
| [data](index.md#tech.whence.echo.rpc.association/Associations/data/#/PointingToDeclaration/)|  [jvm] <br><br>MutableList<Association<*, *, E, R>> 数据存放<br><br>val [data](index.md#tech.whence.echo.rpc.association/Associations/data/#/PointingToDeclaration/): [MutableMap](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-map/index.html)<[Associate](../-associate/index.md)<*, *>, [Association](../-association/index.md)<*, *, [E](index.md), [R](index.md)>>   <br>

