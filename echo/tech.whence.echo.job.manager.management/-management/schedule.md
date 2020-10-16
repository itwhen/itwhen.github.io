---
title: schedule -
---
//[echo](../../index.md)/[tech.whence.echo.job.manager.management](../index.md)/[Management](index.md)/[schedule](schedule.md)



# schedule  
[jvm]  
Brief description  


调度



#### Return  


Unit



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| action| <br><br>Action 指定行为<br><br>
| delay| <br><br>Duration 延迟<br><br>
| identity| <br><br>Identity 指定身份<br><br>
  
  
Content  
fun [schedule](schedule.md)(action: [Action](../-action/index.md), identity: [Identity](../-identity/index.md), delay: [Duration](https://docs.oracle.com/javase/8/docs/api/java/time/Duration.html))  


[jvm]  
Brief description  


调度



#### Return  


Unit



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| action| <br><br>Action 指定行为<br><br>
| delay| <br><br>Duration 延迟<br><br>
| management| <br><br>Management 指定管理器<br><br>
  
  
Content  
fun [schedule](schedule.md)(management: [Management](index.md), action: [Action](../-action/index.md), delay: [Duration](https://docs.oracle.com/javase/8/docs/api/java/time/Duration.html))  


[jvm]  
Brief description  


调度



#### Return  


Unit



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| actor| <br><br>Runner 执行方法<br><br>
| delay| <br><br>Duration 延迟<br><br>
| name| <br><br>String 名称<br><br>
  
  
Content  
fun [schedule](schedule.md)(name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), actor: [Actor](../-actor/index.md), delay: [Duration](https://docs.oracle.com/javase/8/docs/api/java/time/Duration.html))  


[jvm]  
Brief description  


调度



#### Return  


Unit



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| actor| <br><br>Actor? 执行方法<br><br>
| checker| <br><br>Producer<Boolean> 结果检查<br><br>
| delay| <br><br>Duration 延迟<br><br>
| name| <br><br>String 名称<br><br>
  
  
Content  
fun [schedule](schedule.md)(name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), checker: [Producer](../../tech.whence.echo.function/-producer/index.md)<[Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)>, actor: [Actor](../-actor/index.md)?, delay: [Duration](https://docs.oracle.com/javase/8/docs/api/java/time/Duration.html))  


[jvm]  
Brief description  


调度



#### Return  


Unit



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| delay| <br><br>Duration 延迟<br><br>
| interval| <br><br>Duration 间隔<br><br>
| name| <br><br>String 名称<br><br>
| scheduling| <br><br>Scheduling 计划<br><br>
  
  
Content  
@[JvmOverloads](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-overloads/index.html)()  
  
fun [schedule](schedule.md)(name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), scheduling: [Scheduling](../-scheduling/index.md), delay: [Duration](https://docs.oracle.com/javase/8/docs/api/java/time/Duration.html), interval: [Duration](https://docs.oracle.com/javase/8/docs/api/java/time/Duration.html))  



