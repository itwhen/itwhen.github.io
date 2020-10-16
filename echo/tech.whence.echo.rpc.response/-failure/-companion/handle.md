---
title: handle -
---
//[echo](../../../index.md)/[tech.whence.echo.rpc.response](../../index.md)/[Failure](../index.md)/[Companion](index.md)/[handle](handle.md)



# handle  
[jvm]  
Brief description  


门面访问异常处理 若超时或不可用时重定义后抛出 若找不到相关资源时不处理 其他直接抛出



#### Return  


Handler



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| facade| <br><br>KClass<out Facade><br><br>
  
  
Content  
@[JvmStatic](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-static/index.html)()  
  
fun [handle](handle.md)(facade: [KClass](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-class/index.html)<out [Facade](../../../tech.whence.echo.rpc/-facade/index.md)>): [Failure.Handler](../-handler/index.md)  



