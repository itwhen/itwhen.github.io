---
title: retrieves -
---
//[echo](../../../index.md)/[tech.whence.echo.rpc.request](../../index.md)/[Request](../index.md)/[Companion](index.md)/[retrieves](retrieves.md)



# retrieves  
[jvm]  
Brief description  


发起资源获取请求



#### Return  


Map<String, R>



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| batch| <br><br>Batch 编号批次<br><br>
| facade| <br><br>F 资源门面<br><br>
| handler| <br><br>Handler? 异常处理<br><br>
  
  
Content  
inline suspend fun <[F](retrieves.md) : [ResourceFacade](../../../tech.whence.echo.rpc.sample.resource/-resource-facade/index.md)<*, *, *, [R](retrieves.md)>, [R](retrieves.md) : [ResourceData](../../../tech.whence.echo.rpc.sample.resource/-resource-data/index.md)> [retrieves](retrieves.md)(facade: [F](retrieves.md), batch: [Batch](../../-batch/index.md), handler: [Failure.Handler](../../../tech.whence.echo.rpc.response/-failure/-handler/index.md)?): [Map](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)<[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), [R](retrieves.md)>  


[jvm]  
Brief description  


发起资源获取请求



#### Return  


Map<String, R>



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| batch| <br><br>Collection<String> 编号批次<br><br>
| facade| <br><br>F 资源门面<br><br>
| handler| <br><br>Handler? 异常处理<br><br>
  
  
Content  
inline suspend fun <[F](retrieves.md) : [ResourceFacade](../../../tech.whence.echo.rpc.sample.resource/-resource-facade/index.md)<*, *, *, [R](retrieves.md)>, [R](retrieves.md) : [ResourceData](../../../tech.whence.echo.rpc.sample.resource/-resource-data/index.md)> [retrieves](retrieves.md)(facade: [F](retrieves.md), batch: [Collection](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-collection/index.html)<[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)>, handler: [Failure.Handler](../../../tech.whence.echo.rpc.response/-failure/-handler/index.md)?): [Map](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)<[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), [R](retrieves.md)>  



