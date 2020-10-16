---
title: statistics -
---
//[echo](../../index.md)/[tech.whence.echo.job.monitor](../index.md)/[Monitor](index.md)/[statistics](statistics.md)



# statistics  
[jvm]  
Brief description  


统计指定时间段内数据



#### Return  


Map<String, Map<State, Int>> 阶段状态及其数量



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| duration| <br><br>Duration 指定时间段<br><br>
  
  
Content  
fun [statistics](statistics.md)(duration: [Duration](https://docs.oracle.com/javase/8/docs/api/java/time/Duration.html)): [Map](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)<[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), [Map](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)<[Stage](../-stage/index.md), [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)>>  



