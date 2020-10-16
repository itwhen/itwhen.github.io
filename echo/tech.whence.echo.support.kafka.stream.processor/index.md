---
title: tech.whence.echo.support.kafka.stream.processor -
---
//[echo](../index.md)/[tech.whence.echo.support.kafka.stream.processor](index.md)



# Package tech.whence.echo.support.kafka.stream.processor  


## Types  
  
|  Name|  Summary| 
|---|---|
| [AbstractProcessor](-abstract-processor/index.md)| [jvm]  <br>Brief description  <br><br><br>抽象处理器<br><br>  <br>Content  <br>abstract class [AbstractProcessor](-abstract-processor/index.md)<[V](-abstract-processor/index.md)>(**name**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), **converter**: [Converter](-converter/index.md)<[V](-abstract-processor/index.md)>, **collector**: [Collector](../tech.whence.echo.job.stream.collector/-collector/index.md)<[Message](../tech.whence.echo.job.stream.message/-message/index.md)>, **timings**: [Set](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-set/index.html)<[ResponseTiming](../tech.whence.echo.job.stream.message/-response-timing/index.md)>, **logger**: KLogger?) : [Processor](-processor/index.md)<[V](-abstract-processor/index.md)>   <br><br><br>
| [Builder](-builder/index.md)| [jvm]  <br>Brief description  <br><br><br>构建器<br><br>  <br>Content  <br>class [Builder](-builder/index.md)<[V](-builder/index.md)>  <br><br><br>
| [Converter](-converter/index.md)| [jvm]  <br>Brief description  <br><br><br>转换器<br><br>  <br>Content  <br>interface [Converter](-converter/index.md)<[V](-converter/index.md)>  <br><br><br>
| [DefaultProcessor](-default-processor/index.md)| [jvm]  <br>Brief description  <br><br><br>默认处理器<br><br>  <br>Content  <br>class [DefaultProcessor](-default-processor/index.md)<[V](-default-processor/index.md)>(**name**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), **delay**: [Duration](https://docs.oracle.com/javase/8/docs/api/java/time/Duration.html), **converter**: [Converter](-converter/index.md)<[V](-default-processor/index.md)>, **collector**: [Collector](../tech.whence.echo.job.stream.collector/-collector/index.md)<[Message](../tech.whence.echo.job.stream.message/-message/index.md)>, **timings**: [Set](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-set/index.html)<[ResponseTiming](../tech.whence.echo.job.stream.message/-response-timing/index.md)>, **logger**: KLogger?) : [AbstractProcessor](-abstract-processor/index.md)<[V](-default-processor/index.md)>   <br><br><br>
| [DirectlyProcessor](-directly-processor/index.md)| [jvm]  <br>Brief description  <br><br><br>消息直接处理器<br><br>  <br>Content  <br>class [DirectlyProcessor](-directly-processor/index.md)<[V](-directly-processor/index.md)>(**name**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), **converter**: [Converter](-converter/index.md)<[V](-directly-processor/index.md)>, **scheduler**: [Collector](../tech.whence.echo.job.stream.collector/-collector/index.md)<[Message](../tech.whence.echo.job.stream.message/-message/index.md)>, **timing**: [Set](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-set/index.html)<[ResponseTiming](../tech.whence.echo.job.stream.message/-response-timing/index.md)>, **logger**: KLogger?) : [AbstractProcessor](-abstract-processor/index.md)<[V](-directly-processor/index.md)>   <br><br><br>
| [Factory](-factory/index.md)| [jvm]  <br>Brief description  <br><br><br>处理器工厂<br><br>  <br>Content  <br>fun fun interface [Factory](-factory/index.md)<[V](-factory/index.md)>  <br><br><br>
| [Processor](-processor/index.md)| [jvm]  <br>Brief description  <br><br><br>处理器<br><br>  <br>Content  <br>interface [Processor](-processor/index.md)<[V](-processor/index.md)> : Processor<[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), [V](-processor/index.md)>   <br><br><br>

