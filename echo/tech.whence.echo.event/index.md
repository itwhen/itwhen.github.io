---
title: tech.whence.echo.event -
---
//[echo](../index.md)/[tech.whence.echo.event](index.md)



# Package tech.whence.echo.event  


## Types  
  
|  Name|  Summary| 
|---|---|
| [AbstractEvent](-abstract-event/index.md)| [jvm]  <br>Brief description  <br><br><br>事件抽象<br><br>  <br>Content  <br>abstract class [AbstractEvent](-abstract-event/index.md)<[T](-abstract-event/index.md) : [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)> : [Event](-event/index.md)  <br><br><br>
| [DefaultEventChannel](-default-event-channel/index.md)| [jvm]  <br>Brief description  <br><br><br>默认事件频道<br><br>  <br>Content  <br>class [DefaultEventChannel](-default-event-channel/index.md)(**eventBus**: EventBus, **address**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)) : [EventChannel](-event-channel/index.md)  <br><br><br>
| [Event](-event/index.md)| [jvm]  <br>Brief description  <br><br><br>事件<br><br>  <br>Content  <br>interface [Event](-event/index.md)  <br><br><br>
| [EventChannel](-event-channel/index.md)| [jvm]  <br>Brief description  <br><br><br>事件频道<br><br>  <br>Content  <br>interface [EventChannel](-event-channel/index.md)  <br><br><br>
| [EventPriority](-event-priority/index.md)| [jvm]  <br>Brief description  <br><br><br>优先级<br><br>  <br>Content  <br>enum [EventPriority](-event-priority/index.md) : [Enum](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-enum/index.html)<[EventPriority](-event-priority/index.md)>   <br><br><br>
| [EventSequence](-event-sequence/index.md)| [jvm]  <br>Brief description  <br><br><br>事件序列<br><br>  <br>Content  <br>interface [EventSequence](-event-sequence/index.md)<[E](-event-sequence/index.md) : [Event](-event/index.md)>  <br><br><br>
| [EventUnpostedException](-event-unposted-exception/index.md)| [jvm]  <br>Brief description  <br><br><br>事件无法投递<br><br>  <br>Content  <br>class [EventUnpostedException](-event-unposted-exception/index.md)(**event**: [Event](-event/index.md), **cause**: [Throwable](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-throwable/index.html)?) : [RuntimeException](https://docs.oracle.com/javase/8/docs/api/java/lang/RuntimeException.html)  <br><br><br>
| [EventUnregisterableException](-event-unregisterable-exception/index.md)| [jvm]  <br>Brief description  <br><br><br>事件无法注册<br><br>  <br>Content  <br>class [EventUnregisterableException](-event-unregisterable-exception/index.md)(**method**: [KFunction](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-function/index.html)<*>, **subject**: [KClass](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-class/index.html)<out [Event](-event/index.md)>, **found**: [KClass](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-class/index.html)<out [Event](-event/index.md)>) : [RuntimeException](https://docs.oracle.com/javase/8/docs/api/java/lang/RuntimeException.html)  <br><br><br>
| [Poster](-poster/index.md)| [jvm]  <br>Brief description  <br><br><br>投递人<br><br>  <br>Content  <br>interface [Poster](-poster/index.md)<[R](-poster/index.md)>  <br><br><br>
| [Subscribe](-subscribe/index.md)| [jvm]  <br>Brief description  <br><br><br>订阅事件<br><br>  <br>Content  <br>@[Target](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.annotation/-target/index.html)(allowedTargets = [[AnnotationTarget.FUNCTION](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.annotation/-annotation-target/-f-u-n-c-t-i-o-n/index.html)])  <br>  <br>annotation class [Subscribe](-subscribe/index.md)(**value**: [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<out [KClass](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-class/index.html)<out [Event](-event/index.md)>>)  <br><br><br>
| [SubscribeAt](-subscribe-at/index.md)| [jvm]  <br>Brief description  <br><br><br>订阅优先级<br><br>  <br>Content  <br>@[Target](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.annotation/-target/index.html)(allowedTargets = [[AnnotationTarget.FUNCTION](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.annotation/-annotation-target/-f-u-n-c-t-i-o-n/index.html)])  <br>  <br>annotation class [SubscribeAt](-subscribe-at/index.md)(**value**: [EventPriority](-event-priority/index.md))  <br><br><br>
| [Subscriber](-subscriber/index.md)| [jvm]  <br>Brief description  <br><br><br>订阅者<br><br>  <br>Content  <br>data class [Subscriber](-subscriber/index.md)(**location**: [KFunction](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-function/index.html)<*>, **subject**: [KClass](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-class/index.html)<out [Event](-event/index.md)>?, **priority**: [EventPriority](-event-priority/index.md))  <br><br><br>
| [Subscription](-subscription/index.md)| [jvm]  <br>Brief description  <br><br><br>订阅<br><br>  <br>Content  <br>interface [Subscription](-subscription/index.md)<[E](-subscription/index.md) : [Event](-event/index.md)> : [Namer](../tech.whence.echo.definition/-namer/index.md)  <br><br><br>

