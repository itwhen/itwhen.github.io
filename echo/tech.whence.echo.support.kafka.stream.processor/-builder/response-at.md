---
title: responseAt -
---
//[echo](../../index.md)/[tech.whence.echo.support.kafka.stream.processor](../index.md)/[Builder](index.md)/[responseAt](response-at.md)



# responseAt  
[jvm]  
Brief description  


设置响应时机



#### Return  


Builder<V>



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| timings| <br><br>Set<ResponseTiming> 时机<br><br>
  
  
Content  
fun [responseAt](response-at.md)(timings: [Set](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-set/index.html)<[ResponseTiming](../../tech.whence.echo.job.stream.message/-response-timing/index.md)>): [Builder](index.md)<[V](index.md)>  


[jvm]  
Brief description  


设置响应时机



#### Return  


Builder<V>



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| timings| <br><br>Array<out ResponseTiming> 时机<br><br>
  
  
Content  
fun [responseAt](response-at.md)(vararg timings: [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<out [ResponseTiming](../../tech.whence.echo.job.stream.message/-response-timing/index.md)>): [Builder](index.md)<[V](index.md)>  



