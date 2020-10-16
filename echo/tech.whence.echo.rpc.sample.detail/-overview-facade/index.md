---
title: OverviewFacade -
---
//[echo](../../index.md)/[tech.whence.echo.rpc.sample.detail](../index.md)/[OverviewFacade](index.md)



# OverviewFacade  
 [jvm] 

概况门面

interface [OverviewFacade](index.md)<[S](index.md) : [Payload](../../tech.whence.echo.rpc.payload/-payload/index.md), [R](index.md) : [DetailData](../-detail-data/index.md)> : [Facade](../../tech.whence.echo.rpc/-facade/index.md)   


## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| R| <br><br>响应负载<br><br>
| S| <br><br>搜索负载<br><br>
  


## Functions  
  
|  Name|  Summary| 
|---|---|
| [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)| [jvm]  <br>Content  <br>open operator override fun [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [retrieve](retrieve.md)| [jvm]  <br>Brief description  <br><br><br>查询<br><br>  <br>Content  <br>abstract fun [retrieve](retrieve.md)(mainId: [Id](../../tech.whence.echo.rpc.request/-id/index.md), id: [Id](../../tech.whence.echo.rpc.request/-id/index.md), responder: [Responder](../../tech.whence.echo.rpc/index.md#tech.whence.echo.rpc/Responder///PointingToDeclaration/)<[R](index.md)>)  <br><br><br>
| [search](search.md)| [jvm]  <br>Brief description  <br><br><br>搜索<br><br>  <br>Content  <br>abstract fun [search](search.md)(mainId: [Id](../../tech.whence.echo.rpc.request/-id/index.md), request: [Request](../../tech.whence.echo.rpc.request/-request/index.md)<[Searching](../../tech.whence.echo.rpc.payload/-searching/index.md)<[S](index.md)>>, responder: [Responder](../../tech.whence.echo.rpc/index.md#tech.whence.echo.rpc/Responder///PointingToDeclaration/)<[Paged](../../tech.whence.echo.rpc.payload/-paged/index.md)<[R](index.md)>>)  <br><br><br>
| [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>


## Inheritors  
  
|  Name| 
|---|
| [DetailFacade](../-detail-facade/index.md)
| [OverviewService](../-overview-service/index.md)

