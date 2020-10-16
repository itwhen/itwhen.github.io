---
title: Event -
---
//[echo](../../index.md)/[tech.whence.echo.job.manager](../index.md)/[Event](index.md)



# Event  
 [jvm] 

事件

sealed class [Event](index.md) : [AbstractEvent](../../tech.whence.echo.event/-abstract-event/index.md)<[State](../../tech.whence.echo.job.manager.state/-state/index.md)>    


## Types  
  
|  Name|  Summary| 
|---|---|
| [Resumed](-resumed/index.md)| [jvm]  <br>Brief description  <br><br><br>已恢复的<br><br>  <br>Content  <br>class [Resumed](-resumed/index.md)(**data**: [State](../../tech.whence.echo.job.manager.state/-state/index.md)) : [Event](index.md)  <br><br><br>
| [Resuming](-resuming/index.md)| [jvm]  <br>Brief description  <br><br><br>恢复中的<br><br>  <br>Content  <br>class [Resuming](-resuming/index.md)(**data**: [State](../../tech.whence.echo.job.manager.state/-state/index.md)) : [Event](index.md)  <br><br><br>
| [Started](-started/index.md)| [jvm]  <br>Brief description  <br><br><br>已启动的<br><br>  <br>Content  <br>class [Started](-started/index.md)(**data**: [State](../../tech.whence.echo.job.manager.state/-state/index.md)) : [Event](index.md)  <br><br><br>
| [Starting](-starting/index.md)| [jvm]  <br>Brief description  <br><br><br>启动中的<br><br>  <br>Content  <br>class [Starting](-starting/index.md)(**data**: [State](../../tech.whence.echo.job.manager.state/-state/index.md)) : [Event](index.md)  <br><br><br>
| [Stopped](-stopped/index.md)| [jvm]  <br>Brief description  <br><br><br>已停止的<br><br>  <br>Content  <br>class [Stopped](-stopped/index.md)(**data**: [State](../../tech.whence.echo.job.manager.state/-state/index.md)) : [Event](index.md)  <br><br><br>
| [Stopping](-stopping/index.md)| [jvm]  <br>Brief description  <br><br><br>停止中的<br><br>  <br>Content  <br>class [Stopping](-stopping/index.md)(**data**: [State](../../tech.whence.echo.job.manager.state/-state/index.md)) : [Event](index.md)  <br><br><br>
| [Suspended](-suspended/index.md)| [jvm]  <br>Brief description  <br><br><br>已挂起的<br><br>  <br>Content  <br>class [Suspended](-suspended/index.md)(**data**: [State](../../tech.whence.echo.job.manager.state/-state/index.md)) : [Event](index.md)  <br><br><br>
| [Suspending](-suspending/index.md)| [jvm]  <br>Brief description  <br><br><br>挂起中的<br><br>  <br>Content  <br>class [Suspending](-suspending/index.md)(**data**: [State](../../tech.whence.echo.job.manager.state/-state/index.md)) : [Event](index.md)  <br><br><br>


## Functions  
  
|  Name|  Summary| 
|---|---|
| [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)| [jvm]  <br>Content  <br>open operator override fun [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [preventDefault](../../tech.whence.echo.event/-abstract-event/prevent-default.md)| [jvm]  <br>Brief description  <br><br><br>取消默认行为<br><br>  <br>Content  <br>open override fun [preventDefault](../../tech.whence.echo.event/-abstract-event/prevent-default.md)()  <br><br><br>
| [stopPropagation](../../tech.whence.echo.event/-abstract-event/stop-propagation.md)| [jvm]  <br>Brief description  <br><br><br>阻止冒泡<br><br>  <br>Content  <br>open override fun [stopPropagation](../../tech.whence.echo.event/-abstract-event/stop-propagation.md)()  <br><br><br>
| [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>
| [transfer](transfer.md)| [jvm]  <br>Brief description  <br><br><br>转换指定状态到目标状态<br><br>  <br>Content  <br>fun [transfer](transfer.md)(state: [AtomicReference](https://docs.oracle.com/javase/8/docs/api/java/util/concurrent/atomic/AtomicReference.html)<[State](../../tech.whence.echo.job.manager.state/-state/index.md)>): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>


## Properties  
  
|  Name|  Summary| 
|---|---|
| [isDefaultPrevented](index.md#tech.whence.echo.job.manager/Event/isDefaultPrevented/#/PointingToDeclaration/)|  [jvm] <br><br>Boolean 是否取消原生事件<br><br>open override var [isDefaultPrevented](index.md#tech.whence.echo.job.manager/Event/isDefaultPrevented/#/PointingToDeclaration/): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)   <br>
| [isPropagationStopped](index.md#tech.whence.echo.job.manager/Event/isPropagationStopped/#/PointingToDeclaration/)|  [jvm] <br><br>Boolean 是否禁止冒泡<br><br>open override var [isPropagationStopped](index.md#tech.whence.echo.job.manager/Event/isPropagationStopped/#/PointingToDeclaration/): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)   <br>
| [produced](index.md#tech.whence.echo.job.manager/Event/produced/#/PointingToDeclaration/)|  [jvm] <br><br>Boolean 数据是否已生成<br><br>override var [produced](index.md#tech.whence.echo.job.manager/Event/produced/#/PointingToDeclaration/): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)   <br>
| [producer](index.md#tech.whence.echo.job.manager/Event/producer/#/PointingToDeclaration/)|  [jvm] <br><br>Producer<T>? 数据生成<br><br>override val [producer](index.md#tech.whence.echo.job.manager/Event/producer/#/PointingToDeclaration/): [Producer](../../tech.whence.echo.function/-producer/index.md)<[State](../../tech.whence.echo.job.manager.state/-state/index.md)>?   <br>
| [sources](index.md#tech.whence.echo.job.manager/Event/sources/#/PointingToDeclaration/)|  [jvm] <br><br>EnumSet<State> 来源状态<br><br>val [sources](index.md#tech.whence.echo.job.manager/Event/sources/#/PointingToDeclaration/): [EnumSet](https://docs.oracle.com/javase/8/docs/api/java/util/EnumSet.html)<[State](../../tech.whence.echo.job.manager.state/-state/index.md)>   <br>
| [target](index.md#tech.whence.echo.job.manager/Event/target/#/PointingToDeclaration/)|  [jvm] <br><br>State 目标状态<br><br>val [target](index.md#tech.whence.echo.job.manager/Event/target/#/PointingToDeclaration/): [State](../../tech.whence.echo.job.manager.state/-state/index.md)   <br>
| [type](index.md#tech.whence.echo.job.manager/Event/type/#/PointingToDeclaration/)|  [jvm] <br><br>KClass<out T> 数据类<br><br>override var [type](index.md#tech.whence.echo.job.manager/Event/type/#/PointingToDeclaration/): [KClass](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-class/index.html)<out [State](../../tech.whence.echo.job.manager.state/-state/index.md)>   <br>


## Inheritors  
  
|  Name| 
|---|
| [Event](-starting/index.md)
| [Event](-started/index.md)
| [Event](-suspending/index.md)
| [Event](-suspended/index.md)
| [Event](-resuming/index.md)
| [Event](-resumed/index.md)
| [Event](-stopping/index.md)
| [Event](-stopped/index.md)

