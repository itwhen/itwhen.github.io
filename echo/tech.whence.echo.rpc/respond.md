---
title: respond -
---
//[echo](../index.md)/[tech.whence.echo.rpc](index.md)/[respond](respond.md)



# respond  
[jvm]  
Brief description  


响应



#### Return  


Unit



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| <receiver>| <br><br>Responder<T><br><br>
| response| <br><br>Response<T><br><br>
  
  
Content  
fun <[T](respond.md) : [Payload](../tech.whence.echo.rpc.payload/-payload/index.md)> [Responder](index.md#tech.whence.echo.rpc/Responder///PointingToDeclaration/)<[T](respond.md)>.[respond](respond.md)(response: [Response](../tech.whence.echo.rpc.response/-response/index.md)<[T](respond.md)>)  


[jvm]  
Brief description  


响应



#### Return  


Unit



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| <receiver>| <br><br>OperationResponder<br><br>
| consumer| <br><br>Consumer<Handler<AsyncResult<OperationResponse>>><br><br>
  
  
Content  
fun [OperationResponder](index.md#tech.whence.echo.rpc/OperationResponder///PointingToDeclaration/).[respond](respond.md)(consumer: [Consumer](../tech.whence.echo.function/-consumer/index.md)<[OperationResponder](index.md#tech.whence.echo.rpc/OperationResponder///PointingToDeclaration/)>)  



