---
title: onProviderCycleEnd -
---
//[echo](../../index.md)/[tech.whence.echo.job.stream.monitor](../index.md)/[DefaultMonitor](index.md)/[onProviderCycleEnd](on-provider-cycle-end.md)



# onProviderCycleEnd  
[jvm]  
Brief description  


消息提供者循环停止时



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| blockingAt| <br><br>Instant 阻塞时间<br><br>
| provided| <br><br>Int 已提供量<br><br>
| provider| <br><br>Provider 消息提供者<br><br>
  
  
Content  
open override fun [onProviderCycleEnd](on-provider-cycle-end.md)(provider: [Provider](../../tech.whence.echo.job.stream.provider/-provider/index.md), provided: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), blockingAt: [Instant](https://docs.oracle.com/javase/8/docs/api/java/time/Instant.html))  



