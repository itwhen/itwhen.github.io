---
title: Association -
---
//[echo](../../index.md)/[tech.whence.echo.rpc.association](../index.md)/[Association](index.md)



# Association  
 [jvm] 

关联

data class [Association](index.md)<[F](index.md) : [ItemFacade](../../tech.whence.echo.rpc.sample.item/-item-facade/index.md)<*, *, *, [FR](index.md)>, [FR](index.md) : [ItemData](../../tech.whence.echo.rpc.sample.item/-item-data/index.md), [E](index.md) : [Resource](../../tech.whence.echo.rpc.sample.resource/-resource/index.md), [ER](index.md) : [ResourceData](../../tech.whence.echo.rpc.sample.resource/-resource-data/index.md)>(**associate**: [Associate](../-associate/index.md)<[F](index.md), [FR](index.md)>, **inhere**: ([E](index.md)) -> [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, **externalize**: ([ER](index.md), [FR](index.md)) -> [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html))   


## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| E| <br><br>当前数据<br><br>
| ER| <br><br>当前响应<br><br>
| F| <br><br>来源门面<br><br>
| FR| <br><br>来源门面响应<br><br>
  


## Constructors  
  
|  Name|  Summary| 
|---|---|
| [Association](-association.md)|  [jvm] <br><br><br><br>fun <[F](index.md) : [ItemFacade](../../tech.whence.echo.rpc.sample.item/-item-facade/index.md)<*, *, *, [FR](index.md)>, [FR](index.md) : [ItemData](../../tech.whence.echo.rpc.sample.item/-item-data/index.md), [E](index.md) : [Resource](../../tech.whence.echo.rpc.sample.resource/-resource/index.md), [ER](index.md) : [ResourceData](../../tech.whence.echo.rpc.sample.resource/-resource-data/index.md)> [Association](-association.md)(associate: [Associate](../-associate/index.md)<[F](index.md), [FR](index.md)>, inhere: ([E](index.md)) -> [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, externalize: ([ER](index.md), [FR](index.md)) -> [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html))   <br>


## Functions  
  
|  Name|  Summary| 
|---|---|
| [component1](component1.md)| [jvm]  <br>Content  <br>operator fun [component1](component1.md)(): [Associate](../-associate/index.md)<[F](index.md), [FR](index.md)>  <br><br><br>
| [copy](copy.md)| [jvm]  <br>Content  <br>fun [copy](copy.md)(associate: [Associate](../-associate/index.md)<[F](index.md), [FR](index.md)>, inhere: ([E](index.md)) -> [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, externalize: ([ER](index.md), [FR](index.md)) -> [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)): [Association](index.md)<[F](index.md), [FR](index.md), [E](index.md), [ER](index.md)>  <br><br><br>
| [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)| [jvm]  <br>Content  <br>open operator override fun [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [fix](fix.md)| [jvm]  <br>Brief description  <br><br><br>纠正当前响应中相关门面数据<br><br>  <br>Content  <br>fun [fix](fix.md)(main: [ER](index.md), data: [ItemData](../../tech.whence.echo.rpc.sample.item/-item-data/index.md)?)  <br><br><br>
| [from](from.md)| [jvm]  <br>Brief description  <br><br><br>从门面数据中找到实体相应的<br><br>  <br>Content  <br>fun [from](from.md)(data: [Map](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)<[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), [ItemData](../../tech.whence.echo.rpc.sample.item/-item-data/index.md)>, entity: [E](index.md)): [ItemData](../../tech.whence.echo.rpc.sample.item/-item-data/index.md)?  <br><br><br>
| [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [id](id.md)| [jvm]  <br>Brief description  <br><br><br>取关联编号<br><br>  <br>Content  <br>fun [id](id.md)(entity: [E](index.md)): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?  <br><br><br>
| [retrieve](retrieve.md)| [jvm]  <br>Brief description  <br><br><br>根据实体内关联编号获取<br><br>  <br>Content  <br>suspend fun [retrieve](retrieve.md)(entity: [E](index.md)): [FR](index.md)?  <br><br><br>
| [retrieves](retrieves.md)| [jvm]  <br>Brief description  <br><br><br>根据实体内关联编号搜索<br><br>  <br>Content  <br>suspend fun [retrieves](retrieves.md)(entities: [Paginator](../../tech.whence.echo.container/-paginator/index.md)<[E](index.md)>): [Map](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)<[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), [FR](index.md)>  <br>suspend fun [retrieves](retrieves.md)(entities: [Entities](../../tech.whence.echo.dal.entity/-entities/index.md)<[E](index.md)>): [Map](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)<[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), [FR](index.md)>  <br><br><br>
| [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>
| [valid](valid.md)| [jvm]  <br>Brief description  <br><br><br>根据实体累关联编号检验关联数据是否有效<br><br>  <br>Content  <br>suspend fun [valid](valid.md)(entity: [E](index.md))  <br>suspend fun [valid](valid.md)(entities: [Entities](../../tech.whence.echo.dal.entity/-entities/index.md)<[E](index.md)>)  <br><br><br>


## Properties  
  
|  Name|  Summary| 
|---|---|
| [associate](index.md#tech.whence.echo.rpc.association/Association/associate/#/PointingToDeclaration/)|  [jvm] <br><br>Associate<F, FR> 关联人<br><br>val [associate](index.md#tech.whence.echo.rpc.association/Association/associate/#/PointingToDeclaration/): [Associate](../-associate/index.md)<[F](index.md), [FR](index.md)>   <br>

