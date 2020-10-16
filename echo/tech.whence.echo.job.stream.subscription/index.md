---
title: tech.whence.echo.job.stream.subscription -
---
//[echo](../index.md)/[tech.whence.echo.job.stream.subscription](index.md)



# Package tech.whence.echo.job.stream.subscription  


## Types  
  
|  Name|  Summary| 
|---|---|
| [AbstractSubscription](-abstract-subscription/index.md)| [jvm]  <br>Brief description  <br><br><br>抽象订阅<br><br>  <br>Content  <br>abstract class [AbstractSubscription](-abstract-subscription/index.md)(**name**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)) : [Subscription](-subscription/index.md)  <br><br><br>
| [DefaultSubscription](-default-subscription/index.md)| [jvm]  <br>Brief description  <br><br><br>默认订阅<br><br>  <br>Content  <br>class [DefaultSubscription](-default-subscription/index.md)(**channel**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), **pipelines**: [Pipelines](-pipelines/index.md)) : [AbstractSubscription](-abstract-subscription/index.md)  <br><br><br>
| [Partitions](-partitions/index.md)| [jvm]  <br>Brief description  <br><br><br>分区设置<br><br>  <br>Content  <br>data class [Partitions](-partitions/index.md)(**data**: [Set](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-set/index.html)<[Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)>) : [Container](../tech.whence.echo.container/-container/index.md)  <br><br><br>
| [PatternizedSubscription](-patternized-subscription/index.md)| [jvm]  <br>Brief description  <br><br><br>正则型订阅<br><br>  <br>Content  <br>class [PatternizedSubscription](-patternized-subscription/index.md)(**name**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), **pattern**: [Pattern](https://docs.oracle.com/javase/8/docs/api/java/util/regex/Pattern.html)) : [AbstractSubscription](-abstract-subscription/index.md)  <br><br><br>
| [Pipeline](-pipeline/index.md)| [jvm]  <br>Brief description  <br><br><br>消息管道<br><br>  <br>Content  <br>data class [Pipeline](-pipeline/index.md)(**name**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), **location**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), **partitions**: [Partitions](-partitions/index.md))  <br><br><br>
| [Pipelines](-pipelines/index.md)| [jvm]  <br>Brief description  <br><br><br>消息管道集合<br><br>  <br>Content  <br>class [Pipelines](-pipelines/index.md)(**data**: [Map](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)<[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), [Pipeline](-pipeline/index.md)>, **modes**: [EnumSet](https://docs.oracle.com/javase/8/docs/api/java/util/EnumSet.html)<[Pipelines.Mode](-pipelines/-mode/index.md)>)  <br><br><br>
| [Repartitioner](-repartitioner/index.md)| [jvm]  <br>Brief description  <br><br><br>重分区器<br><br>  <br>Content  <br>fun fun interface [Repartitioner](-repartitioner/index.md)  <br><br><br>
| [SingleSubscription](-single-subscription/index.md)| [jvm]  <br>Brief description  <br><br><br>单主题订阅<br><br>  <br>Content  <br>class [SingleSubscription](-single-subscription/index.md)(**name**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), **partitions**: [Partitions](-partitions/index.md)) : [AbstractSubscription](-abstract-subscription/index.md)  <br><br><br>
| [Subscriber](-subscriber/index.md)| [jvm]  <br>Brief description  <br><br><br>订阅者<br><br>  <br>Content  <br>fun fun interface [Subscriber](-subscriber/index.md)  <br><br><br>
| [Subscription](-subscription/index.md)| [jvm]  <br>Brief description  <br><br><br>消息订阅<br><br>  <br>Content  <br>interface [Subscription](-subscription/index.md)  <br><br><br>

