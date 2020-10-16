---
title: tech.whence.echo.job.stream.message -
---
//[echo](../index.md)/[tech.whence.echo.job.stream.message](index.md)



# Package tech.whence.echo.job.stream.message  


## Types  
  
|  Name|  Summary| 
|---|---|
| [AbstractMessage](-abstract-message/index.md)| [jvm]  <br>Brief description  <br><br><br>抽象消息<br><br>  <br>Content  <br>abstract class [AbstractMessage](-abstract-message/index.md)(**id**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), **key**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), **value**: [Accessor](../tech.whence.echo.container.accessor/-accessor/index.md), **source**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, **createdAt**: [Instant](https://docs.oracle.com/javase/8/docs/api/java/time/Instant.html)) : [Message](-message/index.md)  <br><br><br>
| [AbstractResponsiveMessage](-abstract-responsive-message/index.md)| [jvm]  <br>Brief description  <br><br><br>抽象响应式消息<br><br>  <br>Content  <br>abstract class [AbstractResponsiveMessage](-abstract-responsive-message/index.md)(**id**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), **key**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), **value**: [Accessor](../tech.whence.echo.container.accessor/-accessor/index.md), **source**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, **createdAt**: [Instant](https://docs.oracle.com/javase/8/docs/api/java/time/Instant.html), **responder**: [Responder](-responder/index.md)) : [AbstractMessage](-abstract-message/index.md), [Responsive](-responsive/index.md)  <br><br><br>
| [Death](-death/index.md)| [jvm]  <br>Brief description  <br><br><br>失效方式<br><br>  <br>Content  <br>enum [Death](-death/index.md) : [Enum](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-enum/index.html)<[Death](-death/index.md)>   <br><br><br>
| [Message](-message/index.md)| [jvm]  <br>Brief description  <br><br><br>消息<br><br>  <br>Content  <br>interface [Message](-message/index.md) : [Traceable](../tech.whence.echo.job/-traceable/index.md)  <br><br><br>
| [Receiver](-receiver/index.md)| [jvm]  <br>Brief description  <br><br><br>消息接收器<br><br>  <br>Content  <br>interface [Receiver](-receiver/index.md)  <br><br><br>
| [Responder](-responder/index.md)| [jvm]  <br>Brief description  <br><br><br>消息响应器<br><br>  <br>Content  <br>fun fun interface [Responder](-responder/index.md)  <br><br><br>
| [ResponseTiming](-response-timing/index.md)| [jvm]  <br>Brief description  <br><br><br>消息响应时机<br><br>  <br>Content  <br>enum [ResponseTiming](-response-timing/index.md) : [Enum](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-enum/index.html)<[ResponseTiming](-response-timing/index.md)>   <br><br><br>
| [Responsive](-responsive/index.md)| [jvm]  <br>Brief description  <br><br><br>可响应<br><br>  <br>Content  <br>interface [Responsive](-responsive/index.md)  <br><br><br>

