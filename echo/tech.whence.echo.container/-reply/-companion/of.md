---
title: of -
---
//[echo](../../../index.md)/[tech.whence.echo.container](../../index.md)/[Reply](../index.md)/[Companion](index.md)/[of](of.md)



# of  
[jvm]  
Brief description  


构造



#### Return  


Result<K, V>



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| name| <br><br>String 名称<br><br>
| producer| <br><br>Producer<V?> 值提供<br><br>
  
  
Content  
@[JvmStatic](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-static/index.html)()  
  
fun <[V](of.md) : [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)> [of](of.md)(name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), producer: [Producer](../../../tech.whence.echo.function/-producer/index.md)<[V](of.md)?>): [Reply](../index.md)<[V](of.md)>  


[jvm]  
Brief description  


根据异步结果构造



#### Return  


Result<V>



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| result| <br><br>AsyncResult<V> 异步结果<br><br>
  
  
Content  
@[JvmStatic](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-static/index.html)()  
  
fun <[V](of.md) : [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)> [of](of.md)(result: AsyncResult<[V](of.md)>): [Reply](../index.md)<[V](of.md)>  


[jvm]  
Brief description  


构造



#### Return  


Reply<V>



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| context| <br><br>CoroutineContext 上下文<br><br>
| producer| <br><br>SuspendFunction0<V?> 生产<br><br>
  
  
Content  
fun <[V](of.md) : [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)> [of](of.md)(context: [CoroutineContext](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.coroutines/-coroutine-context/index.html), producer: [SuspendFunction0](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.coroutines/-suspend-function0/index.html)<[V](of.md)?>): [Reply](../index.md)<[V](of.md)>  


[jvm]  
Brief description  


构造



#### Return  


Reply<V>



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| value| <br><br>V<br><br>
  
  
Content  
fun <[V](of.md) : [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)> [of](of.md)(value: [V](of.md)): [Reply](../index.md)<[V](of.md)>  



