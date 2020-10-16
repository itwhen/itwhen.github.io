---
title: check -
---
//[echo](../../../index.md)/[tech.whence.echo.job.manager.management](../../index.md)/[Scheduling](../index.md)/[Companion](index.md)/[check](check.md)



# check  
[jvm]  
Brief description  


根据指定行为及检查器生成计划



#### Return  


Scheduling



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| actor| <br><br>Actor? 指定行为<br><br>
| checker| <br><br>Producer<Boolean> 检查是否需要执行指定行为<br><br>
| delay| <br><br>Duration 执行时间间隔<br><br>
  
  
Content  
@[JvmStatic](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-static/index.html)()  
  
fun [check](check.md)(actor: [Actor](../../-actor/index.md)?, checker: [Producer](../../../tech.whence.echo.function/-producer/index.md)<[Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)>, delay: [Duration](https://docs.oracle.com/javase/8/docs/api/java/time/Duration.html)): [Scheduling](../index.md)  



