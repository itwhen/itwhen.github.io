---
title: handle -
---
//[echo](../../index.md)/[tech.whence.echo.webclient](../index.md)/[ExceptionHandler](index.md)/[handle](handle.md)



# handle  
[jvm]  
Brief description  


根据调用异常来决定重试策略



#### Return  


Retry?



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| cause| <br><br>InvocationException<br><br>
  
  
Content  
abstract fun [handle](handle.md)(cause: [InvocationException](../-invocation-exception/index.md)): [Retry](../../tech.whence.echo.retry/-retry/index.md)?  



