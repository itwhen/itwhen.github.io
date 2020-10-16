---
title: drain -
---
//[echo](../../index.md)/[tech.whence.echo.job.stream.collector](../index.md)/[Collector](index.md)/[drain](drain.md)



# drain  
[jvm]  
Brief description  


取出剩余所有任务



#### Return  


List<T>

  
Content  
abstract fun [drain](drain.md)(): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[T](index.md)>  


[jvm]  
Brief description  


取出任务 若限制小于等于0时返回空 若超过等待时间则停止且返回已收集任务 结果将按创建时间排序



#### Return  


List<T>



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| limit| <br><br>Int 限制<br><br>
| waiting| <br><br>Duration? 等待时间<br><br>
  
  
Content  
open fun [drain](drain.md)(limit: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), waiting: [Duration](https://docs.oracle.com/javase/8/docs/api/java/time/Duration.html)?): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[T](index.md)>  



