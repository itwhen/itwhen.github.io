---
title: directly -
---
//[echo](../../../index.md)/[tech.whence.echo.support.kafka.stream.processor](../../index.md)/[Builder](../index.md)/[Companion](index.md)/[directly](directly.md)



# directly  
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
  
  
Content  
@[JvmStatic](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-static/index.html)()  
  
fun <[V](directly.md)> [directly](directly.md)(collector: [Collector](../../../tech.whence.echo.job.stream.collector/-collector/index.md)<[Message](../../../tech.whence.echo.job.stream.message/-message/index.md)>, converter: [Converter](../../-converter/index.md)<[V](directly.md)>): [Builder](../index.md)<[V](directly.md)>  


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
  
  
Content  
@[JvmStatic](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-static/index.html)()  
  
fun [directly](directly.md)(collector: [Collector](../../../tech.whence.echo.job.stream.collector/-collector/index.md)<[Message](../../../tech.whence.echo.job.stream.message/-message/index.md)>): [Builder](../index.md)<[Accessor](../../../tech.whence.echo.container.accessor/-accessor/index.md)>  



