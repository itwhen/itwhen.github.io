---
title: take -
---
//[echo](../../index.md)/[tech.whence.echo.job.stream.work](../index.md)/[Conductor](index.md)/[take](take.md)



# take  
[jvm]  
Brief description  


取出任务



#### Return  


List<Task>



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| count| <br><br>Int 数量<br><br>
| cycle| <br><br>Duration? 等待时间<br><br>
  
  
Content  
fun [take](take.md)(count: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), cycle: [Duration](https://docs.oracle.com/javase/8/docs/api/java/time/Duration.html)?): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[Task](../../tech.whence.echo.job.stream.task/-task/index.md)>  


[jvm]  
Brief description  


取出所有任务



#### Return  


List<Task>

  
Content  
fun [take](take.md)(): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[Task](../../tech.whence.echo.job.stream.task/-task/index.md)>  



