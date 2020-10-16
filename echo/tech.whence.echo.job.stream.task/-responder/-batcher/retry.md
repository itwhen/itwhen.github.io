---
title: retry -
---
//[echo](../../../index.md)/[tech.whence.echo.job.stream.task](../../index.md)/[Responder](../index.md)/[Batcher](index.md)/[retry](retry.md)



# retry  
[jvm]  
Brief description  


重试



#### Return  


Batcher<R>



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| filter| <br><br>Predicate<R>? 过滤条件<br><br>
| retry| <br><br>Retry? 重试设置<br><br>
  
  
Content  
@[JvmOverloads](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-overloads/index.html)()  
  
fun [retry](retry.md)(filter: [Predicate](../../../tech.whence.echo.function/-predicate/index.md)<[R](index.md)>?, retry: [Retry](../../../tech.whence.echo.retry/-retry/index.md)?): [Responder.Batcher](index.md)<[R](index.md)>  



