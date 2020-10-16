---
title: search -
---
//[echo](../../../index.md)/[tech.whence.echo.rpc.request](../../index.md)/[Request](../index.md)/[Companion](index.md)/[search](search.md)



# search  
[jvm]  
Brief description  


发起资源搜索请求



#### Return  


Paged<R>



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| facade| <br><br>F 资源门面<br><br>
| handler| <br><br>Handler? 异常处理<br><br>
| request| <br><br>Request<Searching<S>> 搜索条件<br><br>
  
  
Content  
suspend fun <[F](search.md) : [ResourceFacade](../../../tech.whence.echo.rpc.sample.resource/-resource-facade/index.md)<*, *, [S](search.md), [R](search.md)>, [S](search.md) : [Payload](../../../tech.whence.echo.rpc.payload/-payload/index.md), [R](search.md) : [Payload](../../../tech.whence.echo.rpc.payload/-payload/index.md)> [search](search.md)(facade: [F](search.md), request: [Request](../index.md)<[Searching](../../../tech.whence.echo.rpc.payload/-searching/index.md)<[S](search.md)>>, handler: [Failure.Handler](../../../tech.whence.echo.rpc.response/-failure/-handler/index.md)?): [Paged](../../../tech.whence.echo.rpc.payload/-paged/index.md)<[R](search.md)>  


[jvm]  
Brief description  


发起资源搜索请求



#### Return  


Paged<R>



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| facade| <br><br>F 资源门面<br><br>
| handler| <br><br>Handler? 异常处理<br><br>
| request| <br><br>S 搜索条件<br><br>
  
  
Content  
suspend fun <[F](search.md) : [ResourceFacade](../../../tech.whence.echo.rpc.sample.resource/-resource-facade/index.md)<*, *, [S](search.md), [R](search.md)>, [S](search.md) : [Payload](../../../tech.whence.echo.rpc.payload/-payload/index.md), [R](search.md) : [Payload](../../../tech.whence.echo.rpc.payload/-payload/index.md)> [search](search.md)(facade: [F](search.md), request: [S](search.md), handler: [Failure.Handler](../../../tech.whence.echo.rpc.response/-failure/-handler/index.md)?): [Paged](../../../tech.whence.echo.rpc.payload/-paged/index.md)<[R](search.md)>  



