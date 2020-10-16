---
title: call -
---
//[echo](../../../index.md)/[tech.whence.echo.rpc.request](../../index.md)/[Request](../index.md)/[Companion](index.md)/[call](call.md)



# call  
[jvm]  
Brief description  


提供调用的封装 捕获预料或之外的异常



#### Return  


Response<P>



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| consumer| <br><br>Consumer<Handler<AsyncResult<Response<P>>>><br><br>
  
  
Content  
@[JvmStatic](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-static/index.html)()  
  
suspend fun <[P](call.md) : [Payload](../../../tech.whence.echo.rpc.payload/-payload/index.md)> [call](call.md)(consumer: [Consumer](../../../tech.whence.echo.function/-consumer/index.md)<[Responder](../../../tech.whence.echo.rpc/index.md#tech.whence.echo.rpc/Responder///PointingToDeclaration/)<[P](call.md)>>): [Response](../../../tech.whence.echo.rpc.response/-response/index.md)<[P](call.md)>  



