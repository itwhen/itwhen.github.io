---
title: DefaultMonitor -
---
//[echo](../../index.md)/[tech.whence.echo.job.stream.monitor](../index.md)/[DefaultMonitor](index.md)



# DefaultMonitor  
 [jvm] 

默认监听器

class [DefaultMonitor](index.md)(**logger**: KLogger) : [Monitor](../-monitor/index.md)   


## Constructors  
  
|  Name|  Summary| 
|---|---|
| [DefaultMonitor](-default-monitor.md)|  [jvm] <br><br><br><br>fun [DefaultMonitor](-default-monitor.md)(logger: KLogger)   <br>


## Functions  
  
|  Name|  Summary| 
|---|---|
| [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)| [jvm]  <br>Content  <br>open operator override fun [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [mock](../-monitor/mock.md)| [jvm]  <br>Brief description  <br><br><br>模拟<br><br>  <br>Content  <br>open override fun [mock](../-monitor/mock.md)(queue: [Queue](https://docs.oracle.com/javase/8/docs/api/java/util/Queue.html)<[Message](../../tech.whence.echo.job.stream.message/-message/index.md)>): [Monitor](../-monitor/index.md)  <br>open override fun [mock](../-monitor/mock.md)(collection: [Collection](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-collection/index.html)<[Message](../../tech.whence.echo.job.stream.message/-message/index.md)>): [Monitor](../-monitor/index.md)  <br>open override fun [mock](../-monitor/mock.md)(mocker: [Producer](../../tech.whence.echo.function/-producer/index.md)<[Message](../../tech.whence.echo.job.stream.message/-message/index.md)>): [Monitor](../-monitor/index.md)  <br>open override fun [mock](../-monitor/mock.md)(data: [Message](../../tech.whence.echo.job.stream.message/-message/index.md)): [Monitor](../-monitor/index.md)  <br><br><br>
| [on](on.md)| [jvm]  <br>Brief description  <br><br><br>事件触发时<br><br>  <br>Content  <br>open override fun [on](on.md)(event: [Event](../../tech.whence.echo.job.manager/-event/index.md))  <br><br><br>
| [onBlocked](on-blocked.md)| [jvm]  <br>Brief description  <br><br><br>阻塞时<br><br>  <br>Content  <br>open override fun [onBlocked](on-blocked.md)(degrader: [Degrader](../../tech.whence.echo.job.stream.degrader/-degrader/index.md)?)  <br><br><br>
| [onCycleEnd](on-cycle-end.md)| [jvm]  <br>Brief description  <br><br><br>主循环停止时<br><br>  <br>Content  <br>open override fun [onCycleEnd](on-cycle-end.md)()  <br><br><br>
| [onCycleStart](on-cycle-start.md)| [jvm]  <br>Brief description  <br><br><br>主循环开始时<br><br>  <br>Content  <br>open override fun [onCycleStart](on-cycle-start.md)()  <br><br><br>
| [onDegraded](on-degraded.md)| [jvm]  <br>Brief description  <br><br><br>降级时<br><br>  <br>Content  <br>open override fun [onDegraded](on-degraded.md)(count: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), degrader: [Degrader](../../tech.whence.echo.job.stream.degrader/-degrader/index.md))  <br><br><br>
| [onExceptionally](on-exceptionally.md)| [jvm]  <br>Brief description  <br><br><br>异常时<br><br>  <br>Content  <br>open override fun [onExceptionally](on-exceptionally.md)(cause: [Exception](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-exception/index.html))  <br><br><br>
| [onMeasure](on-measure.md)| [jvm]  <br>Brief description  <br><br><br>测量时<br><br>  <br>Content  <br>open override fun [onMeasure](on-measure.md)(measurer: [Measurer](../../tech.whence.echo.job.stream.work/-measurer/index.md))  <br><br><br>
| [onMessageCollected](on-message-collected.md)| [jvm]  <br>Brief description  <br><br><br>消息已收集时<br><br>  <br>Content  <br>open override fun [onMessageCollected](on-message-collected.md)(provider: [Provider](../../tech.whence.echo.job.stream.provider/-provider/index.md), message: [Message](../../tech.whence.echo.job.stream.message/-message/index.md))  <br><br><br>
| [onMessageCollecting](on-message-collecting.md)| [jvm]  <br>Brief description  <br><br><br>消息收集时<br><br>  <br>Content  <br>open override fun [onMessageCollecting](on-message-collecting.md)(provider: [Provider](../../tech.whence.echo.job.stream.provider/-provider/index.md), message: [Message](../../tech.whence.echo.job.stream.message/-message/index.md)): [MessageStrategy](../-message-strategy/index.md)  <br><br><br>
| [onMessageDead](on-message-dead.md)| [jvm]  <br>Brief description  <br><br><br>消息作废时<br><br>  <br>Content  <br>open override fun [onMessageDead](on-message-dead.md)(provider: [Provider](../../tech.whence.echo.job.stream.provider/-provider/index.md), message: [Message](../../tech.whence.echo.job.stream.message/-message/index.md))  <br><br><br>
| [onMessageLosing](on-message-losing.md)| [jvm]  <br>Brief description  <br><br><br>消息丢弃时<br><br>  <br>Content  <br>open override fun [onMessageLosing](on-message-losing.md)(provider: [Provider](../../tech.whence.echo.job.stream.provider/-provider/index.md), message: [Message](../../tech.whence.echo.job.stream.message/-message/index.md)): [MessageStrategy](../-message-strategy/index.md)  <br><br><br>
| [onMessageNull](on-message-null.md)| [jvm]  <br>Brief description  <br><br><br>消息为空时<br><br>  <br>Content  <br>open override fun [onMessageNull](on-message-null.md)(provider: [Provider](../../tech.whence.echo.job.stream.provider/-provider/index.md)): [ProviderCycleStrategy](../-provider-cycle-strategy/index.md)  <br><br><br>
| [onMessageProduced](on-message-produced.md)| [jvm]  <br>Brief description  <br><br><br>消息生产时<br><br>  <br>Content  <br>open override fun <[M](on-message-produced.md) : [Message](../../tech.whence.echo.job.stream.message/-message/index.md)> [onMessageProduced](on-message-produced.md)(provider: [Provider](../../tech.whence.echo.job.stream.provider/-provider/index.md), producer: [Producer](../../tech.whence.echo.function/-producer/index.md)<[M](on-message-produced.md)?>): [M](on-message-produced.md)?  <br><br><br>
| [onMessageReduplicative](on-message-reduplicative.md)| [jvm]  <br>Brief description  <br><br><br>消息重复时<br><br>  <br>Content  <br>open override fun [onMessageReduplicative](on-message-reduplicative.md)(new: [Message](../../tech.whence.echo.job.stream.message/-message/index.md), old: [Message](../../tech.whence.echo.job.stream.message/-message/index.md)): [MessageStrategy](../-message-strategy/index.md)  <br><br><br>
| [onMessageRescuing](on-message-rescuing.md)| [jvm]  <br>Brief description  <br><br><br>消息恢复时<br><br>  <br>Content  <br>open override fun [onMessageRescuing](on-message-rescuing.md)(provider: [Provider](../../tech.whence.echo.job.stream.provider/-provider/index.md), message: [Message](../../tech.whence.echo.job.stream.message/-message/index.md), cause: [Exception](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-exception/index.html)): [MessageStrategy](../-message-strategy/index.md)  <br><br><br>
| [onProviderCycleEnd](on-provider-cycle-end.md)| [jvm]  <br>Brief description  <br><br><br>消息提供者循环停止时<br><br>  <br>Content  <br>open override fun [onProviderCycleEnd](on-provider-cycle-end.md)(provider: [Provider](../../tech.whence.echo.job.stream.provider/-provider/index.md), provided: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), blockingAt: [Instant](https://docs.oracle.com/javase/8/docs/api/java/time/Instant.html))  <br><br><br>
| [onProviderCycleStart](on-provider-cycle-start.md)| [jvm]  <br>Brief description  <br><br><br>消息提供者循环开始时<br><br>  <br>Content  <br>open override fun [onProviderCycleStart](on-provider-cycle-start.md)(provider: [Provider](../../tech.whence.echo.job.stream.provider/-provider/index.md))  <br><br><br>
| [onShutdown](on-shutdown.md)| [jvm]  <br>Brief description  <br><br><br>关闭时<br><br>  <br>Content  <br>open override fun [onShutdown](on-shutdown.md)(provider: [Provider](../../tech.whence.echo.job.stream.provider/-provider/index.md)): [MessageStrategy](../-message-strategy/index.md)  <br><br><br>
| [onTimeout](on-timeout.md)| [jvm]  <br>Brief description  <br><br><br>超时时<br><br>  <br>Content  <br>open override fun [onTimeout](on-timeout.md)(life: [Duration](https://docs.oracle.com/javase/8/docs/api/java/time/Duration.html))  <br><br><br>
| [onUncaught](on-uncaught.md)| [jvm]  <br>Brief description  <br><br><br>未知异常被捕获时<br><br>  <br>Content  <br>open override fun [onUncaught](on-uncaught.md)(thread: [Thread](https://docs.oracle.com/javase/8/docs/api/java/lang/Thread.html), cause: [Throwable](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-throwable/index.html))  <br><br><br>
| [onUpgrading](on-upgrading.md)| [jvm]  <br>Brief description  <br><br><br>恢复时<br><br>  <br>Content  <br>open override fun [onUpgrading](on-upgrading.md)(degrader: [Degrader](../../tech.whence.echo.job.stream.degrader/-degrader/index.md))  <br><br><br>
| [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>

