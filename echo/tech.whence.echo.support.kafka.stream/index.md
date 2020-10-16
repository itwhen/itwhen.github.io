---
title: tech.whence.echo.support.kafka.stream -
---
//[echo](../index.md)/[tech.whence.echo.support.kafka.stream](index.md)



# Package tech.whence.echo.support.kafka.stream  


## Types  
  
|  Name|  Summary| 
|---|---|
| [ClientSupplier](-client-supplier/index.md)| [jvm]  <br>Brief description  <br><br><br>客户端提供者<br><br>  <br>Content  <br>class [ClientSupplier](-client-supplier/index.md) : KafkaClientSupplier  <br><br><br>
| [DataSource](-data-source/index.md)| [jvm]  <br>Brief description  <br><br><br>数据源<br><br>  <br>Content  <br>class [DataSource](-data-source/index.md) : [AbstractDataSource](../tech.whence.echo.support.kafka/-abstract-data-source/index.md)  <br><br><br>
| [Stream](-stream/index.md)| [jvm]  <br>Brief description  <br><br><br>消息流<br><br>  <br>Content  <br>class [Stream](-stream/index.md)(**vertx**: Vertx, **source**: [DataSource](-data-source/index.md), **subscription**: [Subscription](../tech.whence.echo.job.stream.subscription/-subscription/index.md)) : [AbstractManager](../tech.whence.echo.job.manager/-abstract-manager/index.md), [MessagingProvider.Messager](../tech.whence.echo.job.stream.provider/-messaging-provider/-messager/index.md)  <br><br><br>
| [StreamUnstartableException](-stream-unstartable-exception/index.md)| [jvm]  <br>Brief description  <br><br><br>消息流无法启动<br><br>  <br>Content  <br>class [StreamUnstartableException](-stream-unstartable-exception/index.md)(**message**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), **cause**: [Throwable](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-throwable/index.html)?) : [RuntimeException](https://docs.oracle.com/javase/8/docs/api/java/lang/RuntimeException.html)  <br><br><br>
| [SubscribedMessage](-subscribed-message/index.md)| [jvm]  <br>Brief description  <br><br><br>已订阅消息<br><br>  <br>Content  <br>class [SubscribedMessage](-subscribed-message/index.md)(**key**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), **value**: [Accessor](../tech.whence.echo.container.accessor/-accessor/index.md), **source**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, **createdAt**: [Instant](https://docs.oracle.com/javase/8/docs/api/java/time/Instant.html), **responder**: [Responder](../tech.whence.echo.job.stream.message/-responder/index.md)) : [AbstractResponsiveMessage](../tech.whence.echo.job.stream.message/-abstract-responsive-message/index.md)  <br><br><br>

