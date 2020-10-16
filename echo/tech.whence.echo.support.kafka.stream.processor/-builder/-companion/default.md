---
title: default -
---
//[echo](../../../index.md)/[tech.whence.echo.support.kafka.stream.processor](../../index.md)/[Builder](../index.md)/[Companion](index.md)/[default](default.md)



# default  
[jvm]  
Brief description  


构造



#### Return  


Builder<V>



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| collector| <br><br>Collector<Message> 收集器<br><br>
| converter| <br><br>Converter<V> 转换<br><br>
| delay| <br><br>Duration 延迟<br><br>
  
  
Content  
@[JvmStatic](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-static/index.html)()  
  
fun <[V](default.md)> [default](default.md)(collector: [Collector](../../../tech.whence.echo.job.stream.collector/-collector/index.md)<[Message](../../../tech.whence.echo.job.stream.message/-message/index.md)>, delay: [Duration](https://docs.oracle.com/javase/8/docs/api/java/time/Duration.html), converter: [Converter](../../-converter/index.md)<[V](default.md)>): [Builder](../index.md)<[V](default.md)>  


[jvm]  
Brief description  


构造



#### Return  


Builder<Accessor>



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| collector| <br><br>Collector<Message> 收集器<br><br>
| delay| <br><br>Duration 延迟<br><br>
  
  
Content  
@[JvmStatic](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-static/index.html)()  
  
fun [default](default.md)(collector: [Collector](../../../tech.whence.echo.job.stream.collector/-collector/index.md)<[Message](../../../tech.whence.echo.job.stream.message/-message/index.md)>, delay: [Duration](https://docs.oracle.com/javase/8/docs/api/java/time/Duration.html)): [Builder](../index.md)<[Accessor](../../../tech.whence.echo.container.accessor/-accessor/index.md)>  



