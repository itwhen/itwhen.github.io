---
title: idle -
---
//[echo](../../index.md)/[tech.whence.echo.job.stream.work](../index.md)/[Conductor](index.md)/[idle](idle.md)



# idle  
[jvm]  
Brief description  


取空闲时间 若重试未设置则为空 若正常状态下重置重试返回空 否则取重试设置的下一个等待周期



#### Return  


Duration?



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| idled| <br><br>Retrying? 空闲重试设置<br><br>
| provided| <br><br>Int 已提供量<br><br>
  
  
Content  
fun [idle](idle.md)(provided: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), idled: [Retrying](../../tech.whence.echo.retry/-retrying/index.md)?): [Duration](https://docs.oracle.com/javase/8/docs/api/java/time/Duration.html)?  



