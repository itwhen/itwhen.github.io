---
title: map -
---
//[echo](../../index.md)/[tech.whence.echo.job.stream.task](../index.md)/[Tasks](index.md)/[map](map.md)



# map  
[jvm]  
Brief description  


转换可执行数据构造



#### Return  


Responder.Batcher<R>



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| converter| <br><br>Converter<R, R> 批量转换器<br><br>
| target| <br><br>KClass<R> 指定数据类型<br><br>
  
  
Content  
fun <[R](map.md) : [Traceable](../../tech.whence.echo.job/-traceable/index.md)> [map](map.md)(target: [KClass](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-class/index.html)<[R](map.md)>, converter: [Converter](../-converter/index.md)<[R](map.md), [R](map.md)>): [Responder.Batcher](../-responder/-batcher/index.md)<[R](map.md)>  


[jvm]  
Brief description  


转换可执行数据构造



#### Return  


Responder.Batcher<R>



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| converter| <br><br>Converter<V, R> 批量转换器<br><br>
| mapper| <br><br>Transformer<R, V?> 转换<br><br>
| target| <br><br>KClass<R> 指定数据类型<br><br>
  
  
Content  
fun <[R](map.md) : [Traceable](../../tech.whence.echo.job/-traceable/index.md), [V](map.md)> [map](map.md)(target: [KClass](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-class/index.html)<[R](map.md)>, mapper: [Transformer](../../tech.whence.echo.function/-transformer/index.md)<[R](map.md), [V](map.md)?>, converter: [Converter](../-converter/index.md)<[V](map.md), [R](map.md)>): [Responder.Batcher](../-responder/-batcher/index.md)<[R](map.md)>  



