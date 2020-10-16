---
title: tech.whence.echo.support.kafka.receiver -
---
//[echo](../index.md)/[tech.whence.echo.support.kafka.receiver](index.md)



# Package tech.whence.echo.support.kafka.receiver  


## Types  
  
|  Name|  Summary| 
|---|---|
| [DataSource](-data-source/index.md)| [jvm]  <br>Brief description  <br><br><br>数据源<br><br>  <br>Content  <br>class [DataSource](-data-source/index.md) : [AbstractDataSource](../tech.whence.echo.support.kafka/-abstract-data-source/index.md)  <br><br><br>
| [Receiver](-receiver/index.md)| [jvm]  <br>Brief description  <br><br><br>接收器<br><br>  <br>Content  <br>class [Receiver](-receiver/index.md)(**vertx**: Vertx, **source**: [DataSource](-data-source/index.md), **subscription**: [Subscription](../tech.whence.echo.job.stream.subscription/-subscription/index.md)) : [AbstractManager](../tech.whence.echo.job.manager/-abstract-manager/index.md)  <br><br><br>
| [Result](-result/index.md)| [jvm]  <br>Brief description  <br><br><br>结果<br><br>  <br>Content  <br>data class [Result](-result/index.md)(**topic**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), **partition**: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), **offset**: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html), **date**: [Instant](https://docs.oracle.com/javase/8/docs/api/java/time/Instant.html), **key**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), **value**: [Accessor](../tech.whence.echo.container.accessor/-accessor/index.md))  <br><br><br>

