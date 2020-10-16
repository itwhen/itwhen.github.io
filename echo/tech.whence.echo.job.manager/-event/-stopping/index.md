---
title: Stopping -
---
//[echo](../../../index.md)/[tech.whence.echo.job.manager](../../index.md)/[Event](../index.md)/[Stopping](index.md)



# Stopping  
 [jvm] 

停止中的

class [Stopping](index.md)(**data**: [State](../../../tech.whence.echo.job.manager.state/-state/index.md)) : [Event](../index.md)   


## Constructors  
  
|  Name|  Summary| 
|---|---|
| [Stopping](-stopping.md)|  [jvm] <br><br><br><br>fun [Stopping](-stopping.md)(data: [State](../../../tech.whence.echo.job.manager.state/-state/index.md))   <br>


## Functions  
  
|  Name|  Summary| 
|---|---|
| [equals](../../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)| [jvm]  <br>Content  <br>open operator override fun [equals](../../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [hashCode](../../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [hashCode](../../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [preventDefault](../../../tech.whence.echo.event/-abstract-event/prevent-default.md)| [jvm]  <br>Brief description  <br><br><br>取消默认行为<br><br>  <br>Content  <br>open override fun [preventDefault](../../../tech.whence.echo.event/-abstract-event/prevent-default.md)()  <br><br><br>
| [stopPropagation](../../../tech.whence.echo.event/-abstract-event/stop-propagation.md)| [jvm]  <br>Brief description  <br><br><br>阻止冒泡<br><br>  <br>Content  <br>open override fun [stopPropagation](../../../tech.whence.echo.event/-abstract-event/stop-propagation.md)()  <br><br><br>
| [toString](../../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [toString](../../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>
| [transfer](../transfer.md)| [jvm]  <br>Brief description  <br><br><br>转换指定状态到目标状态<br><br>  <br>Content  <br>override fun [transfer](../transfer.md)(state: [AtomicReference](https://docs.oracle.com/javase/8/docs/api/java/util/concurrent/atomic/AtomicReference.html)<[State](../../../tech.whence.echo.job.manager.state/-state/index.md)>): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>


## Properties  
  
|  Name|  Summary| 
|---|---|
| [isDefaultPrevented](index.md#tech.whence.echo.job.manager/Event.Stopping/isDefaultPrevented/#/PointingToDeclaration/)|  [jvm] <br><br>Boolean 是否取消原生事件<br><br>open override var [isDefaultPrevented](index.md#tech.whence.echo.job.manager/Event.Stopping/isDefaultPrevented/#/PointingToDeclaration/): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)   <br>
| [isPropagationStopped](index.md#tech.whence.echo.job.manager/Event.Stopping/isPropagationStopped/#/PointingToDeclaration/)|  [jvm] <br><br>Boolean 是否禁止冒泡<br><br>open override var [isPropagationStopped](index.md#tech.whence.echo.job.manager/Event.Stopping/isPropagationStopped/#/PointingToDeclaration/): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)   <br>
| [produced](index.md#tech.whence.echo.job.manager/Event.Stopping/produced/#/PointingToDeclaration/)|  [jvm] <br><br>Boolean 数据是否已生成<br><br>override var [produced](index.md#tech.whence.echo.job.manager/Event.Stopping/produced/#/PointingToDeclaration/): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)   <br>
| [producer](index.md#tech.whence.echo.job.manager/Event.Stopping/producer/#/PointingToDeclaration/)|  [jvm] <br><br>Producer<T>? 数据生成<br><br>override val [producer](index.md#tech.whence.echo.job.manager/Event.Stopping/producer/#/PointingToDeclaration/): [Producer](../../../tech.whence.echo.function/-producer/index.md)<[State](../../../tech.whence.echo.job.manager.state/-state/index.md)>?   <br>
| [sources](index.md#tech.whence.echo.job.manager/Event.Stopping/sources/#/PointingToDeclaration/)|  [jvm] <br><br>EnumSet<State> 来源状态<br><br>override val [sources](index.md#tech.whence.echo.job.manager/Event.Stopping/sources/#/PointingToDeclaration/): [EnumSet](https://docs.oracle.com/javase/8/docs/api/java/util/EnumSet.html)<[State](../../../tech.whence.echo.job.manager.state/-state/index.md)>   <br>
| [target](index.md#tech.whence.echo.job.manager/Event.Stopping/target/#/PointingToDeclaration/)|  [jvm] <br><br>State 目标状态<br><br>override val [target](index.md#tech.whence.echo.job.manager/Event.Stopping/target/#/PointingToDeclaration/): [State](../../../tech.whence.echo.job.manager.state/-state/index.md)   <br>
| [type](index.md#tech.whence.echo.job.manager/Event.Stopping/type/#/PointingToDeclaration/)|  [jvm] <br><br>KClass<out T> 数据类<br><br>override var [type](index.md#tech.whence.echo.job.manager/Event.Stopping/type/#/PointingToDeclaration/): [KClass](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-class/index.html)<out [State](../../../tech.whence.echo.job.manager.state/-state/index.md)>   <br>

