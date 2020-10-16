---
title: respond -
---
//[echo](../../index.md)/[tech.whence.echo.job.stream.task](../index.md)/[Tasks](index.md)/[respond](respond.md)



# respond  
[jvm]  
Brief description  


响应



#### Return  


Tasks



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| callback| <br><br>Consumer<Task> 回调<br><br>
| result| <br><br>Traceable 可跟踪数据<br><br>
  
  
Content  
fun [respond](respond.md)(result: [Traceable](../../tech.whence.echo.job/-traceable/index.md), callback: [Consumer](../../tech.whence.echo.function/-consumer/index.md)<[Task](../-task/index.md)>): [Tasks](index.md)  


[jvm]  
Brief description  


响应



#### Return  


Tasks



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| callback| <br><br>Consumer<Task> 回调<br><br>
| key| <br><br>String 数据键<br><br>
  
  
Content  
fun [respond](respond.md)(key: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), callback: [Consumer](../../tech.whence.echo.function/-consumer/index.md)<[Task](../-task/index.md)>): [Tasks](index.md)  


[jvm]  
Brief description  


响应所有数据



#### Return  


Tasks



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| consumer| <br><br>Consumer<Task>? 回调<br><br>
  
  
Content  
fun [respond](respond.md)(consumer: [Consumer](../../tech.whence.echo.function/-consumer/index.md)<[Task](../-task/index.md)>?): [Tasks](index.md)  


[jvm]  
Brief description  


响应所有数据 若判断为空或返回真则消费相应任务并移除



#### Return  


Tasks



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| consumer| <br><br>Consumer<Task>? 回调<br><br>
| predicate| <br><br>Predicate<R>? 判断<br><br>
  
  
Content  
fun <[R](respond.md) : [Traceable](../../tech.whence.echo.job/-traceable/index.md)> [respond](respond.md)(predicate: [Predicate](../../tech.whence.echo.function/-predicate/index.md)<[R](respond.md)>?, consumer: [Consumer](../../tech.whence.echo.function/-consumer/index.md)<[Task](../-task/index.md)>?): [Tasks](index.md)  



