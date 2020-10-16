---
title: wrap -
---
//[echo](../../../index.md)/[tech.whence.echo.rpc.request](../../index.md)/[Request](../index.md)/[Companion](index.md)/[wrap](wrap.md)



# wrap  
[jvm]  
Brief description  


尝试构造 将校验指定数据有效性



#### Return  


Request<Single<T>>



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| data| <br><br>T 指定数据<br><br>
  
  
Content  
@[JvmStatic](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-static/index.html)()  
  
fun <[T](wrap.md) : [Payload](../../../tech.whence.echo.rpc.payload/-payload/index.md)> [wrap](wrap.md)(data: [T](wrap.md)): [Request](../index.md)<[T](wrap.md)>  


[jvm]  
Brief description  


搜索



#### Return  


Request<Searching<T>>



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| criterion| <br><br>T 搜索条件<br><br>
| limit| <br><br>UInt 每页负载<br><br>
| page| <br><br>UInt 指定页码<br><br>
  
  
Content  
@[JvmStatic](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-static/index.html)()  
  
fun <[T](wrap.md) : [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)> [wrap](wrap.md)(limit: [UInt](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-u-int/index.html), page: [UInt](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-u-int/index.html), criterion: [T](wrap.md)): [Request](../index.md)<[Searching](../../../tech.whence.echo.rpc.payload/-searching/index.md)<[T](wrap.md)>>  


[jvm]  
Brief description  


搜索



#### Return  


Request<Searching<T>>



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| consumer| <br><br>@kotlin.ExtensionFunctionType Function1<T, Unit> 搜索条件<br><br>
| limit| <br><br>UInt 每页负载<br><br>
| page| <br><br>UInt 指定页码<br><br>
  
  
Content  
@[JvmStatic](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-static/index.html)()  
  
inline fun <[T](wrap.md) : [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)> [wrap](wrap.md)(limit: [UInt](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-u-int/index.html), page: [UInt](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-u-int/index.html), consumer: [T](wrap.md).() -> [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)): [Request](../index.md)<[Searching](../../../tech.whence.echo.rpc.payload/-searching/index.md)<[T](wrap.md)>>  



