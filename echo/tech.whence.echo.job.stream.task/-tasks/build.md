---
title: build -
---
//[echo](../../index.md)/[tech.whence.echo.job.stream.task](../index.md)/[Tasks](index.md)/[build](build.md)



# build  
[jvm]  
Brief description  


构造



#### Return  


Responder.Batcher<R>



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| builder| <br><br>Builder<V> 构造器<br><br>
| converter| <br><br>Converter<V, R> 批量转换器<br><br>
  
  
Content  
fun <[R](build.md) : [Traceable](../../tech.whence.echo.job/-traceable/index.md), [V](build.md)> [build](build.md)(builder: [Builder](../-builder/index.md)<[V](build.md)>, converter: [Converter](../-converter/index.md)<[V](build.md), [R](build.md)>): [Responder.Batcher](../-responder/-batcher/index.md)<[R](build.md)>  


[jvm]  
Brief description  


构造



#### Return  


Responder.Batcher<R>



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| builder| <br><br>Builder<V> 构造器<br><br>
| callback| <br><br>Consumer<List<R>> 回调<br><br>
| converter| <br><br>Transformer<V, R> 转换<br><br>
  
  
Content  
fun <[R](build.md) : [Traceable](../../tech.whence.echo.job/-traceable/index.md), [V](build.md)> [build](build.md)(builder: [Builder](../-builder/index.md)<[V](build.md)>, converter: [Transformer](../../tech.whence.echo.function/-transformer/index.md)<[V](build.md), [R](build.md)>, callback: [Consumer](../../tech.whence.echo.function/-consumer/index.md)<[List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[R](build.md)>>): [Responder.Batcher](../-responder/-batcher/index.md)<[R](build.md)>  


[jvm]  
Brief description  


构造



#### Return  


Responder.Batcher<R>



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| usable| <br><br>List<R> 可用数据<br><br>
  
  
Content  
fun <[R](build.md) : [Traceable](../../tech.whence.echo.job/-traceable/index.md)> [build](build.md)(usable: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[R](build.md)>): [Responder.Batcher](../-responder/-batcher/index.md)<[R](build.md)>  


[jvm]  
Brief description  


构造



#### Return  


Responder.Batcher<R>



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| builder| <br><br>Builder<R> 构造器<br><br>
  
  
Content  
fun <[R](build.md) : [Traceable](../../tech.whence.echo.job/-traceable/index.md)> [build](build.md)(builder: [Builder](../-builder/index.md)<[R](build.md)>): [Responder.Batcher](../-responder/-batcher/index.md)<[R](build.md)>  



