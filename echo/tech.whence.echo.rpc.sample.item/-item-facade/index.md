---
title: ItemFacade -
---
//[echo](../../index.md)/[tech.whence.echo.rpc.sample.item](../index.md)/[ItemFacade](index.md)



# ItemFacade  
 [jvm] 

物品门面

interface [ItemFacade](index.md)<[C](index.md) : [Payload](../../tech.whence.echo.rpc.payload/-payload/index.md), [U](index.md) : [Payload](../../tech.whence.echo.rpc.payload/-payload/index.md), [S](index.md) : [ItemSearching](../-item-searching/index.md), [R](index.md) : [ItemData](../-item-data/index.md)> : [ResourceFacade](../../tech.whence.echo.rpc.sample.resource/-resource-facade/index.md)<[C](index.md), [U](index.md), [S](index.md), [R](index.md)>    


## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| C| <br><br>创建负载<br><br>
| R| <br><br>响应负载<br><br>
| S| <br><br>搜索负载<br><br>
| U| <br><br>更新负载<br><br>
  


## Functions  
  
|  Name|  Summary| 
|---|---|
| [create](../../tech.whence.echo.rpc.sample.resource/-resource-facade/create.md)| [jvm]  <br>Brief description  <br><br><br>创建<br><br>  <br>Content  <br>abstract override fun [create](../../tech.whence.echo.rpc.sample.resource/-resource-facade/create.md)(request: [Request](../../tech.whence.echo.rpc.request/-request/index.md)<[C](index.md)>, responder: [Responder](../../tech.whence.echo.rpc/index.md#tech.whence.echo.rpc/Responder///PointingToDeclaration/)<[Single](../../tech.whence.echo.rpc.payload/-single/index.md)<[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)>>)  <br><br><br>
| [delete](../../tech.whence.echo.rpc.sample.resource/-resource-facade/delete.md)| [jvm]  <br>Brief description  <br><br><br>删除<br><br>  <br>Content  <br>abstract override fun [delete](../../tech.whence.echo.rpc.sample.resource/-resource-facade/delete.md)(batch: [Batch](../../tech.whence.echo.rpc.request/-batch/index.md), responder: [Responder](../../tech.whence.echo.rpc/index.md#tech.whence.echo.rpc/Responder///PointingToDeclaration/)<[Empty](../../tech.whence.echo.rpc.payload/-empty/index.md)>)  <br><br><br>
| [disable](disable.md)| [jvm]  <br>Brief description  <br><br><br>禁用<br><br>  <br>Content  <br>abstract fun [disable](disable.md)(batch: [Batch](../../tech.whence.echo.rpc.request/-batch/index.md), responder: [Responder](../../tech.whence.echo.rpc/index.md#tech.whence.echo.rpc/Responder///PointingToDeclaration/)<[Empty](../../tech.whence.echo.rpc.payload/-empty/index.md)>)  <br><br><br>
| [enable](enable.md)| [jvm]  <br>Brief description  <br><br><br>启用<br><br>  <br>Content  <br>abstract fun [enable](enable.md)(batch: [Batch](../../tech.whence.echo.rpc.request/-batch/index.md), responder: [Responder](../../tech.whence.echo.rpc/index.md#tech.whence.echo.rpc/Responder///PointingToDeclaration/)<[Empty](../../tech.whence.echo.rpc.payload/-empty/index.md)>)  <br><br><br>
| [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)| [jvm]  <br>Content  <br>open operator override fun [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [retrieve](index.md#tech.whence.echo.rpc.sample.resource/ResourceFacade/retrieve/#tech.whence.echo.rpc.request.Id#io.vertx.core.Handler[io.vertx.core.AsyncResult[tech.whence.echo.rpc.response.Response[TypeParam(bounds=[tech.whence.echo.rpc.sample.item.ItemData])]]]/PointingToDeclaration/)| [jvm]  <br>Brief description  <br><br><br>查询<br><br>  <br>Content  <br>abstract override fun [retrieve](index.md#tech.whence.echo.rpc.sample.resource/ResourceFacade/retrieve/#tech.whence.echo.rpc.request.Id#io.vertx.core.Handler[io.vertx.core.AsyncResult[tech.whence.echo.rpc.response.Response[TypeParam(bounds=[tech.whence.echo.rpc.sample.item.ItemData])]]]/PointingToDeclaration/)(id: [Id](../../tech.whence.echo.rpc.request/-id/index.md), responder: [Responder](../../tech.whence.echo.rpc/index.md#tech.whence.echo.rpc/Responder///PointingToDeclaration/)<[R](index.md)>)  <br><br><br>
| [retrieves](index.md#tech.whence.echo.rpc.sample.resource/ResourceFacade/retrieves/#tech.whence.echo.rpc.request.Batch#io.vertx.core.Handler[io.vertx.core.AsyncResult[tech.whence.echo.rpc.response.Response[tech.whence.echo.rpc.payload.Listed[TypeParam(bounds=[tech.whence.echo.rpc.sample.item.ItemData])]]]]/PointingToDeclaration/)| [jvm]  <br>Brief description  <br><br><br>查询<br><br>  <br>Content  <br>abstract override fun [retrieves](index.md#tech.whence.echo.rpc.sample.resource/ResourceFacade/retrieves/#tech.whence.echo.rpc.request.Batch#io.vertx.core.Handler[io.vertx.core.AsyncResult[tech.whence.echo.rpc.response.Response[tech.whence.echo.rpc.payload.Listed[TypeParam(bounds=[tech.whence.echo.rpc.sample.item.ItemData])]]]]/PointingToDeclaration/)(batch: [Batch](../../tech.whence.echo.rpc.request/-batch/index.md), responder: [Responder](../../tech.whence.echo.rpc/index.md#tech.whence.echo.rpc/Responder///PointingToDeclaration/)<[Listed](../../tech.whence.echo.rpc.payload/-listed/index.md)<[R](index.md)>>)  <br><br><br>
| [search](index.md#tech.whence.echo.rpc.sample.resource/ResourceFacade/search/#tech.whence.echo.rpc.request.Request[tech.whence.echo.rpc.payload.Searching[TypeParam(bounds=[tech.whence.echo.rpc.sample.item.ItemSearching])]]#io.vertx.core.Handler[io.vertx.core.AsyncResult[tech.whence.echo.rpc.response.Response[tech.whence.echo.rpc.payload.Paged[TypeParam(bounds=[tech.whence.echo.rpc.sample.item.ItemData])]]]]/PointingToDeclaration/)| [jvm]  <br>Brief description  <br><br><br>搜索<br><br>  <br>Content  <br>abstract override fun [search](index.md#tech.whence.echo.rpc.sample.resource/ResourceFacade/search/#tech.whence.echo.rpc.request.Request[tech.whence.echo.rpc.payload.Searching[TypeParam(bounds=[tech.whence.echo.rpc.sample.item.ItemSearching])]]#io.vertx.core.Handler[io.vertx.core.AsyncResult[tech.whence.echo.rpc.response.Response[tech.whence.echo.rpc.payload.Paged[TypeParam(bounds=[tech.whence.echo.rpc.sample.item.ItemData])]]]]/PointingToDeclaration/)(request: [Request](../../tech.whence.echo.rpc.request/-request/index.md)<[Searching](../../tech.whence.echo.rpc.payload/-searching/index.md)<[S](index.md)>>, responder: [Responder](../../tech.whence.echo.rpc/index.md#tech.whence.echo.rpc/Responder///PointingToDeclaration/)<[Paged](../../tech.whence.echo.rpc.payload/-paged/index.md)<[R](index.md)>>)  <br><br><br>
| [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>
| [update](../../tech.whence.echo.rpc.sample.resource/-resource-facade/update.md)| [jvm]  <br>Brief description  <br><br><br>更新<br><br>  <br>Content  <br>abstract override fun [update](../../tech.whence.echo.rpc.sample.resource/-resource-facade/update.md)(id: [Id](../../tech.whence.echo.rpc.request/-id/index.md), request: [Request](../../tech.whence.echo.rpc.request/-request/index.md)<[U](index.md)>, responder: [Responder](../../tech.whence.echo.rpc/index.md#tech.whence.echo.rpc/Responder///PointingToDeclaration/)<[Empty](../../tech.whence.echo.rpc.payload/-empty/index.md)>)  <br><br><br>


## Inheritors  
  
|  Name| 
|---|
| [ItemService](../-item-service/index.md)

