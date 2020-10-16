---
title: DefaultProcessor -
---
//[echo](../../index.md)/[tech.whence.echo.support.kafka.receiver.processor](../index.md)/[DefaultProcessor](index.md)



# DefaultProcessor  
 [jvm] 

默认处理器

class [DefaultProcessor](index.md)(**subject**: KafkaConsumer<[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), [Accessor](../../tech.whence.echo.container.accessor/-accessor/index.md)>, **work**: [Consumer](../../tech.whence.echo.function/-consumer/index.md)<[List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[Result](../../tech.whence.echo.support.kafka.receiver/-result/index.md)>>, **latency**: [Duration](https://docs.oracle.com/javase/8/docs/api/java/time/Duration.html)) : [AbstractProcessor](../-abstract-processor/index.md)   


## Constructors  
  
|  Name|  Summary| 
|---|---|
| [DefaultProcessor](-default-processor.md)|  [jvm] <br><br><br><br>fun [DefaultProcessor](-default-processor.md)(subject: KafkaConsumer<[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), [Accessor](../../tech.whence.echo.container.accessor/-accessor/index.md)>, work: [Consumer](../../tech.whence.echo.function/-consumer/index.md)<[List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[Result](../../tech.whence.echo.support.kafka.receiver/-result/index.md)>>, latency: [Duration](https://docs.oracle.com/javase/8/docs/api/java/time/Duration.html))   <br>


## Functions  
  
|  Name|  Summary| 
|---|---|
| [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)| [jvm]  <br>Content  <br>open operator override fun [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [initialize](../-processor/initialize.md)| [jvm]  <br>Brief description  <br><br><br>初始化<br><br>  <br>Content  <br>open override fun [initialize](../-processor/initialize.md)()  <br><br><br>
| [inspect](../-processor/inspect.md)| [jvm]  <br>Brief description  <br><br><br>查看状态<br><br>  <br>Content  <br>open override fun [inspect](../-processor/inspect.md)(): [State](../../tech.whence.echo.job.manager.state/-state/index.md)  <br><br><br>
| [name](../-abstract-processor/name.md)| [jvm]  <br>Brief description  <br><br><br>名称<br><br>  <br>Content  <br>open override fun [name](../-abstract-processor/name.md)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>
| [resume](../-processor/resume.md)| [jvm]  <br>Brief description  <br><br><br>恢复<br><br>  <br>Content  <br>open suspend override fun [resume](../-processor/resume.md)()  <br><br><br>
| [start](../-abstract-processor/start.md)| [jvm]  <br>Brief description  <br><br><br>启动<br><br>  <br>Content  <br>open suspend override fun [start](../-abstract-processor/start.md)()  <br><br><br>
| [stop](../-abstract-processor/stop.md)| [jvm]  <br>Brief description  <br><br><br>停止<br><br>  <br>Content  <br>open suspend override fun [stop](../-abstract-processor/stop.md)()  <br><br><br>
| [suspend](../-processor/suspend.md)| [jvm]  <br>Brief description  <br><br><br>挂起<br><br>  <br>Content  <br>open suspend override fun [suspend](../-processor/suspend.md)()  <br><br><br>
| [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>


## Properties  
  
|  Name|  Summary| 
|---|---|
| [stopped](index.md#tech.whence.echo.support.kafka.receiver.processor/DefaultProcessor/stopped/#/PointingToDeclaration/)|  [jvm] <br><br>AtomicBoolean 停止标记<br><br>override var [stopped](index.md#tech.whence.echo.support.kafka.receiver.processor/DefaultProcessor/stopped/#/PointingToDeclaration/): [AtomicBoolean](https://docs.oracle.com/javase/8/docs/api/java/util/concurrent/atomic/AtomicBoolean.html)   <br>

