---
title: introduceBy -
---
//[echo](../../index.md)/[tech.whence.echo.job.manager.management](../index.md)/[Management](index.md)/[introduceBy](introduce-by.md)



# introduceBy  
[jvm]  
Brief description  


设置行为增强器



#### Return  


Management



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| action| <br><br>Action 指定行为<br><br>
| actor| <br><br>Actor 指定扩展方法<br><br>
| advice| <br><br>Array<out Advice> 指定扩展点<br><br>
  
  
Content  
fun [introduceBy](introduce-by.md)(action: [Action](../-action/index.md), actor: [Actor](../-actor/index.md), vararg advice: [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<out [Scheduler.Advice](../-scheduler/-advice/index.md)>): [Management](index.md)  


[jvm]  
Brief description  


在行为后设置增强器



#### Return  


Management



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| action| <br><br>Action 指定行为<br><br>
| actor| <br><br>Actor 指定扩展方法<br><br>
  
  
Content  
fun [introduceBy](introduce-by.md)(action: [Action](../-action/index.md), actor: [Actor](../-actor/index.md)): [Management](index.md)  



