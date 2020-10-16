---
title: DetailFacade -
---
//[echo](../../index.md)/[tech.whence.echo.rpc.sample.detail](../index.md)/[DetailFacade](index.md)



# DetailFacade  
 [jvm] 

明细门面

interface [DetailFacade](index.md)<[C](index.md) : [Payload](../../tech.whence.echo.rpc.payload/-payload/index.md), [U](index.md) : [Payload](../../tech.whence.echo.rpc.payload/-payload/index.md), [S](index.md) : [Payload](../../tech.whence.echo.rpc.payload/-payload/index.md), [R](index.md) : [DetailData](../-detail-data/index.md)> : [OverviewFacade](../-overview-facade/index.md)<[S](index.md), [R](index.md)>    


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
| [create](create.md)| [jvm]  <br>Brief description  <br><br><br>创建<br><br>  <br>Content  <br>abstract fun [create](create.md)(mainId: [Id](../../tech.whence.echo.rpc.request/-id/index.md), request: [Request](../../tech.whence.echo.rpc.request/-request/index.md)<[C](index.md)>, responder: [Responder](../../tech.whence.echo.rpc/index.md#tech.whence.echo.rpc/Responder///PointingToDeclaration/)<[R](index.md)>)  <br><br><br>
| [delete](delete.md)| [jvm]  <br>Brief description  <br><br><br>删除<br><br>  <br>Content  <br>abstract fun [delete](delete.md)(mainId: [Id](../../tech.whence.echo.rpc.request/-id/index.md), batch: [Batch](../../tech.whence.echo.rpc.request/-batch/index.md), responder: [Responder](../../tech.whence.echo.rpc/index.md#tech.whence.echo.rpc/Responder///PointingToDeclaration/)<[Empty](../../tech.whence.echo.rpc.payload/-empty/index.md)>)  <br><br><br>
| [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)| [jvm]  <br>Content  <br>open operator override fun [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [retrieve](../-overview-facade/retrieve.md)| [jvm]  <br>Brief description  <br><br><br>查询<br><br>  <br>Content  <br>abstract override fun [retrieve](../-overview-facade/retrieve.md)(mainId: [Id](../../tech.whence.echo.rpc.request/-id/index.md), id: [Id](../../tech.whence.echo.rpc.request/-id/index.md), responder: [Responder](../../tech.whence.echo.rpc/index.md#tech.whence.echo.rpc/Responder///PointingToDeclaration/)<[R](index.md)>)  <br><br><br>
| [search](../-overview-facade/search.md)| [jvm]  <br>Brief description  <br><br><br>搜索<br><br>  <br>Content  <br>abstract override fun [search](../-overview-facade/search.md)(mainId: [Id](../../tech.whence.echo.rpc.request/-id/index.md), request: [Request](../../tech.whence.echo.rpc.request/-request/index.md)<[Searching](../../tech.whence.echo.rpc.payload/-searching/index.md)<[S](index.md)>>, responder: [Responder](../../tech.whence.echo.rpc/index.md#tech.whence.echo.rpc/Responder///PointingToDeclaration/)<[Paged](../../tech.whence.echo.rpc.payload/-paged/index.md)<[R](index.md)>>)  <br><br><br>
| [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>
| [update](update.md)| [jvm]  <br>Brief description  <br><br><br>更新<br><br>  <br>Content  <br>abstract fun [update](update.md)(mainId: [Id](../../tech.whence.echo.rpc.request/-id/index.md), id: [Id](../../tech.whence.echo.rpc.request/-id/index.md), request: [Request](../../tech.whence.echo.rpc.request/-request/index.md)<[U](index.md)>, responder: [Responder](../../tech.whence.echo.rpc/index.md#tech.whence.echo.rpc/Responder///PointingToDeclaration/)<[Empty](../../tech.whence.echo.rpc.payload/-empty/index.md)>)  <br><br><br>


## Inheritors  
  
|  Name| 
|---|
| [DetailService](../-detail-service/index.md)

