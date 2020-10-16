---
title: Sender -
---
//[echo](../../index.md)/[tech.whence.echo.support.kafka.sender](../index.md)/[Sender](index.md)



# Sender  
 [jvm] 

发送器

class [Sender](index.md)(**vertx**: Vertx, **source**: [DataSource](../-data-source/index.md), **subscription**: [Subscription](../../tech.whence.echo.job.stream.subscription/-subscription/index.md)) : [Sender](../../tech.whence.echo.job.stream.sender/-sender/index.md)<[Result](../-result/index.md)>    


## Constructors  
  
|  Name|  Summary| 
|---|---|
| [Sender](-sender.md)|  [jvm] <br><br><br><br>fun [Sender](-sender.md)(vertx: Vertx, source: [DataSource](../-data-source/index.md), subscription: [Subscription](../../tech.whence.echo.job.stream.subscription/-subscription/index.md))   <br>


## Functions  
  
|  Name|  Summary| 
|---|---|
| [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)| [jvm]  <br>Content  <br>open operator override fun [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [partition](partition.md)| [jvm]  <br>Brief description  <br><br><br>查找管道分区<br><br>  <br>Content  <br>fun [partition](partition.md)(pipeline: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): [Partitions](../../tech.whence.echo.job.stream.subscription/-partitions/index.md)  <br><br><br>
| [send](send.md)| [jvm]  <br>Brief description  <br><br><br>发送<br><br>  <br>Content  <br>open suspend override fun [send](send.md)(topic: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), partition: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)?, key: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), value: [Accessor](../../tech.whence.echo.container.accessor/-accessor/index.md)): [Reply](../../tech.whence.echo.container/-reply/index.md)<[Result](../-result/index.md)>  <br><br><br>
| [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>

