---
title: Builder -
---
//[echo](../../index.md)/[tech.whence.echo.support.kafka.stream.processor](../index.md)/[Builder](index.md)



# Builder  
 [jvm] 

构建器

class [Builder](index.md)<[V](index.md)>   


## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| V| <br><br>值类型<br><br>
  


## Types  
  
|  Name|  Summary| 
|---|---|
| [Companion](-companion/index.md)| [jvm]  <br>Content  <br>object [Companion](-companion/index.md)  <br><br><br>


## Functions  
  
|  Name|  Summary| 
|---|---|
| [build](build.md)| [jvm]  <br>Brief description  <br><br><br>构建<br><br>  <br>Content  <br>fun [build](build.md)(): [Processor](../-processor/index.md)<[V](index.md)>  <br><br><br>
| [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)| [jvm]  <br>Content  <br>open operator override fun [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [logBy](log-by.md)| [jvm]  <br>Brief description  <br><br><br>设置日志<br><br>  <br>Content  <br>fun [logBy](log-by.md)(logger: KLogger?): [Builder](index.md)<[V](index.md)>  <br><br><br>
| [name](name.md)| [jvm]  <br>Brief description  <br><br><br>设置名称<br><br>  <br>Content  <br>fun [name](name.md)(name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): [Builder](index.md)<[V](index.md)>  <br><br><br>
| [provideBy](provide-by.md)| [jvm]  <br>Brief description  <br><br><br>设置消息收集器<br><br>  <br>Content  <br>fun [provideBy](provide-by.md)(collector: [Collector](../../tech.whence.echo.job.stream.collector/-collector/index.md)<[Message](../../tech.whence.echo.job.stream.message/-message/index.md)>): [Builder](index.md)<[V](index.md)>  <br><br><br>
| [responseAt](response-at.md)| [jvm]  <br>Brief description  <br><br><br>设置响应时机<br><br>  <br>Content  <br>fun [responseAt](response-at.md)(vararg timings: [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<out [ResponseTiming](../../tech.whence.echo.job.stream.message/-response-timing/index.md)>): [Builder](index.md)<[V](index.md)>  <br>fun [responseAt](response-at.md)(timings: [Set](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-set/index.html)<[ResponseTiming](../../tech.whence.echo.job.stream.message/-response-timing/index.md)>): [Builder](index.md)<[V](index.md)>  <br><br><br>
| [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>

