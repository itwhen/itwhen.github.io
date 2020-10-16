---
title: tech.whence.echo.support.kafka.receiver.processor -
---
//[echo](../index.md)/[tech.whence.echo.support.kafka.receiver.processor](index.md)



# Package tech.whence.echo.support.kafka.receiver.processor  


## Types  
  
|  Name|  Summary| 
|---|---|
| [AbstractProcessor](-abstract-processor/index.md)| [jvm]  <br>Brief description  <br><br><br>抽象处理器<br><br>  <br>Content  <br>abstract class [AbstractProcessor](-abstract-processor/index.md)(**subject**: KafkaConsumer<[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), [Accessor](../tech.whence.echo.container.accessor/-accessor/index.md)>, **work**: [Consumer](../tech.whence.echo.function/-consumer/index.md)<[List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[Result](../tech.whence.echo.support.kafka.receiver/-result/index.md)>>, **latency**: [Duration](https://docs.oracle.com/javase/8/docs/api/java/time/Duration.html)) : [Processor](-processor/index.md)  <br><br><br>
| [DefaultProcessor](-default-processor/index.md)| [jvm]  <br>Brief description  <br><br><br>默认处理器<br><br>  <br>Content  <br>class [DefaultProcessor](-default-processor/index.md)(**subject**: KafkaConsumer<[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), [Accessor](../tech.whence.echo.container.accessor/-accessor/index.md)>, **work**: [Consumer](../tech.whence.echo.function/-consumer/index.md)<[List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[Result](../tech.whence.echo.support.kafka.receiver/-result/index.md)>>, **latency**: [Duration](https://docs.oracle.com/javase/8/docs/api/java/time/Duration.html)) : [AbstractProcessor](-abstract-processor/index.md)  <br><br><br>
| [Processor](-processor/index.md)| [jvm]  <br>Brief description  <br><br><br>处理器<br><br>  <br>Content  <br>interface [Processor](-processor/index.md) : [Manager](../tech.whence.echo.job.manager/-manager/index.md)  <br><br><br>
| [Processors](-processors/index.md)| [jvm]  <br>Brief description  <br><br><br>处理器集合<br><br>  <br>Content  <br>class [Processors](-processors/index.md)(**factory**: [Transformer](../tech.whence.echo.function/-transformer/index.md)<[Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), [Processor](-processor/index.md)>) : [Processor](-processor/index.md)  <br><br><br>
| [WaitingProcessor](-waiting-processor/index.md)| [jvm]  <br>Brief description  <br><br><br>等待型处理器<br><br>  <br>Content  <br>class [WaitingProcessor](-waiting-processor/index.md)(**subject**: KafkaConsumer<[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), [Accessor](../tech.whence.echo.container.accessor/-accessor/index.md)>, **work**: [Consumer](../tech.whence.echo.function/-consumer/index.md)<[List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[Result](../tech.whence.echo.support.kafka.receiver/-result/index.md)>>, **latency**: [Duration](https://docs.oracle.com/javase/8/docs/api/java/time/Duration.html), **payload**: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)) : [AbstractProcessor](-abstract-processor/index.md)  <br><br><br>

