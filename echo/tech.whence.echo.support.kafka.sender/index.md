---
title: tech.whence.echo.support.kafka.sender -
---
//[echo](../index.md)/[tech.whence.echo.support.kafka.sender](index.md)



# Package tech.whence.echo.support.kafka.sender  


## Types  
  
|  Name|  Summary| 
|---|---|
| [DataSource](-data-source/index.md)| [jvm]  <br>Brief description  <br><br><br>数据源<br><br>  <br>Content  <br>class [DataSource](-data-source/index.md) : [AbstractDataSource](../tech.whence.echo.support.kafka/-abstract-data-source/index.md)  <br><br><br>
| [LimitablePartitioner](-limitable-partitioner/index.md)| [jvm]  <br>Brief description  <br><br><br>可限制分区器<br><br>  <br>Content  <br>class [LimitablePartitioner](-limitable-partitioner/index.md) : Partitioner  <br><br><br>
| [Result](-result/index.md)| [jvm]  <br>Brief description  <br><br><br>结果<br><br>  <br>Content  <br>data class [Result](-result/index.md)(**topic**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, **offset**: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)?, **date**: [Instant](https://docs.oracle.com/javase/8/docs/api/java/time/Instant.html)?, **partition**: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)?, **exception**: [Exception](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-exception/index.html)?)  <br><br><br>
| [Sender](-sender/index.md)| [jvm]  <br>Brief description  <br><br><br>发送器<br><br>  <br>Content  <br>class [Sender](-sender/index.md)(**vertx**: Vertx, **source**: [DataSource](-data-source/index.md), **subscription**: [Subscription](../tech.whence.echo.job.stream.subscription/-subscription/index.md)) : [Sender](../tech.whence.echo.job.stream.sender/-sender/index.md)<[Result](-result/index.md)>   <br><br><br>

