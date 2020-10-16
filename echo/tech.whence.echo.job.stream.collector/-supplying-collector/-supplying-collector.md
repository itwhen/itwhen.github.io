---
title: SupplyingCollector -
---
//[echo](../../index.md)/[tech.whence.echo.job.stream.collector](../index.md)/[SupplyingCollector](index.md)/[SupplyingCollector](-supplying-collector.md)



# SupplyingCollector  
[jvm]  
Brief description  


## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| C| <br><br>: Collector<T> 收集者类型<br><br>
| T| <br><br>: Message 消息类型<br><br>
  
  
Content  
fun <[T](index.md) : [Message](../../tech.whence.echo.job.stream.message/-message/index.md), [C](index.md) : [Collector](../-collector/index.md)<[T](index.md)>> [SupplyingCollector](-supplying-collector.md)(proxy: [C](index.md), producer: [Producer](../../tech.whence.echo.function/-producer/index.md)<[List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[T](index.md)>>)  



