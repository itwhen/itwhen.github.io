---
title: ResourceService -
---
//[echo](../../index.md)/[tech.whence.echo.rpc.sample.resource](../index.md)/[ResourceService](index.md)



# ResourceService  
 [jvm] 

资源服务抽象

abstract class [ResourceService](index.md)<[T](index.md) : [ResourceService](index.md)<[T](index.md), [C](index.md), [U](index.md), [S](index.md), [R](index.md), [E](index.md), [D](index.md)>, [C](index.md) : [Payload](../../tech.whence.echo.rpc.payload/-payload/index.md), [U](index.md) : [Payload](../../tech.whence.echo.rpc.payload/-payload/index.md), [S](index.md) : [ResourceSearching](../-resource-searching/index.md), [R](index.md) : [ResourceData](../-resource-data/index.md), [E](index.md) : [Resource](../-resource/index.md), [D](index.md) : [Dao](../../tech.whence.echo.dal.dao/-dao/index.md)<[E](index.md), [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), *>, [Queriable](../../tech.whence.echo.dal.dao/-queriable/index.md)<[E](index.md), *, *, *, *, *, *, *, *, *>>(**source**: [KClass](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-class/index.html)<[E](index.md)>, **dao**: [D](index.md), **identifier**: [Identifier](../../tech.whence.echo.dal.entity.id/-identifier/index.md)) : [AbstractService](../../tech.whence.echo.rpc/-abstract-service/index.md)<[T](index.md)> , [ResourceFacade](../-resource-facade/index.md)<[C](index.md), [U](index.md), [S](index.md), [R](index.md)>    


## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| C| <br><br>创建负载<br><br>
| D| <br><br>数据层<br><br>
| E| <br><br>实体<br><br>
| R| <br><br>响应负载<br><br>
| S| <br><br>搜索负载<br><br>
| T| <br><br>子类<br><br>
| U| <br><br>更新负载<br><br>
  


## Constructors  
  
|  Name|  Summary| 
|---|---|
| [ResourceService](-resource-service.md)|  [jvm] <br><br><br><br>fun <[E](index.md) : [Resource](../-resource/index.md), [D](index.md) : [Dao](../../tech.whence.echo.dal.dao/-dao/index.md)<[E](index.md), [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), *>, [Queriable](../../tech.whence.echo.dal.dao/-queriable/index.md)<[E](index.md), *, *, *, *, *, *, *, *, *>> [ResourceService](-resource-service.md)(source: [KClass](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-class/index.html)<[E](index.md)>, dao: [D](index.md), identifier: [Identifier](../../tech.whence.echo.dal.entity.id/-identifier/index.md))   <br>


## Functions  
  
|  Name|  Summary| 
|---|---|
| [create](create.md)| [jvm]  <br>Brief description  <br><br><br>创建<br><br>  <br>Content  <br>open override fun [create](create.md)(request: [Request](../../tech.whence.echo.rpc.request/-request/index.md)<[C](index.md)>, responder: [Responder](../../tech.whence.echo.rpc/index.md#tech.whence.echo.rpc/Responder///PointingToDeclaration/)<[Single](../../tech.whence.echo.rpc.payload/-single/index.md)<[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)>>)  <br><br><br>
| [delete](delete.md)| [jvm]  <br>Brief description  <br><br><br>删除<br><br>  <br>Content  <br>open override fun [delete](delete.md)(batch: [Batch](../../tech.whence.echo.rpc.request/-batch/index.md), responder: [Responder](../../tech.whence.echo.rpc/index.md#tech.whence.echo.rpc/Responder///PointingToDeclaration/)<[Empty](../../tech.whence.echo.rpc.payload/-empty/index.md)>)  <br><br><br>
| [detail](detail.md)| [jvm]  <br>Brief description  <br><br><br>是否支持变更明细<br><br>  <br>Content  <br>open fun [detail](detail.md)(data: [E](index.md)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)| [jvm]  <br>Content  <br>open operator override fun [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [retrieve](retrieve.md)| [jvm]  <br>Brief description  <br><br><br>查询<br><br>  <br>Content  <br>open override fun [retrieve](retrieve.md)(id: [Id](../../tech.whence.echo.rpc.request/-id/index.md), responder: [Responder](../../tech.whence.echo.rpc/index.md#tech.whence.echo.rpc/Responder///PointingToDeclaration/)<[R](index.md)>)  <br><br><br>
| [retrieves](retrieves.md)| [jvm]  <br>Brief description  <br><br><br>查询<br><br>  <br>Content  <br>open override fun [retrieves](retrieves.md)(batch: [Batch](../../tech.whence.echo.rpc.request/-batch/index.md), responder: [Responder](../../tech.whence.echo.rpc/index.md#tech.whence.echo.rpc/Responder///PointingToDeclaration/)<[Listed](../../tech.whence.echo.rpc.payload/-listed/index.md)<[R](index.md)>>)  <br><br><br>
| [search](search.md)| [jvm]  <br>Brief description  <br><br><br>搜索<br><br>  <br>Content  <br>open override fun [search](search.md)(request: [Request](../../tech.whence.echo.rpc.request/-request/index.md)<[Searching](../../tech.whence.echo.rpc.payload/-searching/index.md)<[S](index.md)>>, responder: [Responder](../../tech.whence.echo.rpc/index.md#tech.whence.echo.rpc/Responder///PointingToDeclaration/)<[Paged](../../tech.whence.echo.rpc.payload/-paged/index.md)<[R](index.md)>>)  <br><br><br>
| [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>
| [update](update.md)| [jvm]  <br>Brief description  <br><br><br>更新<br><br>  <br>Content  <br>open override fun [update](update.md)(id: [Id](../../tech.whence.echo.rpc.request/-id/index.md), request: [Request](../../tech.whence.echo.rpc.request/-request/index.md)<[U](index.md)>, responder: [Responder](../../tech.whence.echo.rpc/index.md#tech.whence.echo.rpc/Responder///PointingToDeclaration/)<[Empty](../../tech.whence.echo.rpc.payload/-empty/index.md)>)  <br><br><br>


## Inheritors  
  
|  Name| 
|---|
| [FlowService](../../tech.whence.echo.rpc.sample.flow/-flow-service/index.md)
| [ItemService](../../tech.whence.echo.rpc.sample.item/-item-service/index.md)

