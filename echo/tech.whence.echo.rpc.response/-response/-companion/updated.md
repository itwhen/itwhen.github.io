---
title: updated -
---
//[echo](../../../index.md)/[tech.whence.echo.rpc.response](../../index.md)/[Response](../index.md)/[Companion](index.md)/[updated](updated.md)



# updated  
[jvm]  
Brief description  


完成更新



#### Return  


Responsive



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| successful| <br><br>Boolean 是否成功<br><br>
  
  
Content  
@[JvmStatic](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-static/index.html)()  
  
fun [updated](updated.md)(successful: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)): [Response](../index.md)<[Empty](../../../tech.whence.echo.rpc.payload/-empty/index.md)>  


[jvm]  
Brief description  


完成更新



#### Return  


Response<T>



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| data| <br><br>Producer<T> 创建成后负载生成<br><br>
| decorator| <br><br>Decorator<E, T>? 有效负载纠正<br><br>
| successful| <br><br>Boolean 是否成功<br><br>
  
  
Content  
inline fun <[E](updated.md) : [Entity](../../../tech.whence.echo.dal.entity/-entity/index.md), [T](updated.md) : [Payload](../../../tech.whence.echo.rpc.payload/-payload/index.md)> [updated](updated.md)(successful: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), data: [E](updated.md), decorator: [Decorator](../../-decorator/index.md)<[T](updated.md), [E](updated.md)>?): [Response](../index.md)<[T](updated.md)>  



