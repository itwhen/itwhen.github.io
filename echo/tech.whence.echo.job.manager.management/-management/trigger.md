---
title: trigger -
---
//[echo](../../index.md)/[tech.whence.echo.job.manager.management](../index.md)/[Management](index.md)/[trigger](trigger.md)



# trigger  
[jvm]  
Brief description  


触发事件



#### Return  


Duration?



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| event| <br><br>KClass<out Event> 指定事件类型<br><br>
  
  
Content  
fun [trigger](trigger.md)(event: [KClass](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-class/index.html)<out [Event](../../tech.whence.echo.job.manager/-event/index.md)>): [Duration](https://docs.oracle.com/javase/8/docs/api/java/time/Duration.html)?  


[jvm]  
Brief description  


触发事件



#### Return  


Duration?



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| event| <br><br>KClass<out Event> 指定事件类型<br><br>
| identity| <br><br>Identity 指定身份<br><br>
  
  
Content  
fun [trigger](trigger.md)(event: [KClass](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-class/index.html)<out [Event](../../tech.whence.echo.job.manager/-event/index.md)>, identity: [Identity](../-identity/index.md)): [Duration](https://docs.oracle.com/javase/8/docs/api/java/time/Duration.html)?  



