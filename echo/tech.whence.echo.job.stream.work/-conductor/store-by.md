---
title: storeBy -
---
//[echo](../../index.md)/[tech.whence.echo.job.stream.work](../index.md)/[Conductor](index.md)/[storeBy](store-by.md)



# storeBy  
[jvm]  
Brief description  


设置任务存储器



#### Return  


Conductor



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| collectable| <br><br>Int 可收集量<br><br>
| collector| <br><br>Collector<Task> 普通任务收集器<br><br>
| dumper| <br><br>Collector<Task> 丢弃任务收集器<br><br>
  
  
Content  
fun [storeBy](store-by.md)(collector: [Collector](../../tech.whence.echo.job.stream.collector/-collector/index.md)<[Task](../../tech.whence.echo.job.stream.task/-task/index.md)>, dumper: [Collector](../../tech.whence.echo.job.stream.collector/-collector/index.md)<[Task](../../tech.whence.echo.job.stream.task/-task/index.md)>, collectable: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [Conductor](index.md)  



