---
title: introduce -
---
//[echo](../../index.md)/[tech.whence.echo.job.manager.management](../index.md)/[Scheduler](index.md)/[introduce](introduce.md)



# introduce  
[jvm]  
Brief description  


引入行为 引入后将在指定增强处被触发时执行指定行为



#### Return  


Scheduler



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| action| <br><br>Actor 指定行为<br><br>
| advices| <br><br>Array<out Advice> 指定增强<br><br>
  
  
Content  
fun [introduce](introduce.md)(action: [Actor](../-actor/index.md), vararg advices: [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<out [Scheduler.Advice](-advice/index.md)>): [Scheduler](index.md)  



