---
title: run -
---
//[echo](../../index.md)/[tech.whence.echo.job.stream.task](../index.md)/[Tasks](index.md)/[run](run.md)



# run  
[jvm]  
Brief description  


消费可执行数据同时构造



#### Return  


Responder.Batcher<R>



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| consumer| <br><br>Consumer<List<R>> 消费<br><br>
| target| <br><br>KClass<R> 指定数据类型<br><br>
  
  
Content  
fun <[R](run.md) : [Traceable](../../tech.whence.echo.job/-traceable/index.md)> [run](run.md)(target: [KClass](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-class/index.html)<[R](run.md)>, consumer: [Consumer](../../tech.whence.echo.function/-consumer/index.md)<[List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[R](run.md)>>): [Responder.Batcher](../-responder/-batcher/index.md)<[R](run.md)>  



