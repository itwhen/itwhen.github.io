---
title: allow -
---
//[echo](../../index.md)/[tech.whence.echo.retry](../index.md)/[Retry](index.md)/[allow](allow.md)



# allow  
[jvm]  
Brief description  


是否允许下一步操作



#### Return  


Boolean



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| elapsed| <br><br>Duration 持续时间<br><br>
| sleeper| <br><br>RetrySleeper? 休眠器<br><br>
| times| <br><br>Int 可重试次数<br><br>
  
  
Content  
open fun [allow](allow.md)(times: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), elapsed: [Duration](https://docs.oracle.com/javase/8/docs/api/java/time/Duration.html), sleeper: [RetrySleeper](../-retry-sleeper/index.md)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  


[jvm]  
Brief description  


是否允许下一步操作



#### Return  


Boolean



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| retrying| <br><br>Retrying 重试设置<br><br>
| sleeper| <br><br>RetrySleeper? 休眠器<br><br>
  
  
Content  
abstract fun [allow](allow.md)(retrying: [Retrying](../-retrying/index.md), sleeper: [RetrySleeper](../-retry-sleeper/index.md)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  



