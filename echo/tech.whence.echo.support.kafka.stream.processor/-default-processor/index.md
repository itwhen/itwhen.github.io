---
title: DefaultProcessor -
---
//[echo](../../index.md)/[tech.whence.echo.support.kafka.stream.processor](../index.md)/[DefaultProcessor](index.md)



# DefaultProcessor  
 [jvm] 

默认处理器

class [DefaultProcessor](index.md)<[V](index.md)>(**name**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), **delay**: [Duration](https://docs.oracle.com/javase/8/docs/api/java/time/Duration.html), **converter**: [Converter](../-converter/index.md)<[V](index.md)>, **collector**: [Collector](../../tech.whence.echo.job.stream.collector/-collector/index.md)<[Message](../../tech.whence.echo.job.stream.message/-message/index.md)>, **timings**: [Set](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-set/index.html)<[ResponseTiming](../../tech.whence.echo.job.stream.message/-response-timing/index.md)>, **logger**: KLogger?) : [AbstractProcessor](../-abstract-processor/index.md)<[V](index.md)>    


## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| V| <br><br>值类型<br><br>
  


## Constructors  
  
|  Name|  Summary| 
|---|---|
| [DefaultProcessor](-default-processor.md)|  [jvm] <br><br><br><br>fun <[V](index.md)> [DefaultProcessor](-default-processor.md)(name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), delay: [Duration](https://docs.oracle.com/javase/8/docs/api/java/time/Duration.html), converter: [Converter](../-converter/index.md)<[V](index.md)>, collector: [Collector](../../tech.whence.echo.job.stream.collector/-collector/index.md)<[Message](../../tech.whence.echo.job.stream.message/-message/index.md)>, timings: [Set](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-set/index.html)<[ResponseTiming](../../tech.whence.echo.job.stream.message/-response-timing/index.md)>, logger: KLogger?)   <br>


## Functions  
  
|  Name|  Summary| 
|---|---|
| [close](../-abstract-processor/close.md)| [jvm]  <br>Brief description  <br><br><br>关闭<br><br>  <br>Content  <br>open override fun [close](../-abstract-processor/close.md)()  <br><br><br>
| [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)| [jvm]  <br>Content  <br>open operator override fun [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [init](init.md)| [jvm]  <br>Brief description  <br><br><br>初始化<br><br>  <br>Content  <br>open override fun [init](init.md)(context: ProcessorContext)  <br><br><br>
| [process](../-abstract-processor/process.md)| [jvm]  <br>Brief description  <br><br><br>处理<br><br>  <br>Content  <br>open override fun [process](../-abstract-processor/process.md)(key: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), value: [V](index.md))  <br><br><br>
| [punctuate](punctuate.md)| [jvm]  <br>Brief description  <br><br><br>标记时间<br><br>  <br>Content  <br>open override fun [punctuate](punctuate.md)(timestamp: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html))  <br><br><br>
| [reprocess](../-abstract-processor/reprocess.md)| [jvm]  <br>Brief description  <br><br><br>重新处理消息<br><br>  <br>Content  <br>open override fun [reprocess](../-abstract-processor/reprocess.md)(key: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html))  <br><br><br>
| [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>

