---
title: AbstractEvent -
---
//[echo](../../index.md)/[tech.whence.echo.event](../index.md)/[AbstractEvent](index.md)



# AbstractEvent  
 [jvm] 

事件抽象

abstract class [AbstractEvent](index.md)<[T](index.md) : [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)> : [Event](../-event/index.md)   


## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| T| <br><br>: Any 数据类型<br><br>
  


## Constructors  
  
|  Name|  Summary| 
|---|---|
| [AbstractEvent](-abstract-event.md)|  [jvm] fun <[T](index.md) : [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)> [AbstractEvent](-abstract-event.md)(data: [T](index.md))   <br>
| [AbstractEvent](-abstract-event.md)|  [jvm] fun <[T](index.md) : [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)> [AbstractEvent](-abstract-event.md)(type: [KClass](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-class/index.html)<out [T](index.md)>, supplier: [Producer](../../tech.whence.echo.function/-producer/index.md)<[T](index.md)>)   <br>


## Functions  
  
|  Name|  Summary| 
|---|---|
| [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)| [jvm]  <br>Content  <br>open operator override fun [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [preventDefault](prevent-default.md)| [jvm]  <br>Brief description  <br><br><br>取消默认行为<br><br>  <br>Content  <br>open override fun [preventDefault](prevent-default.md)()  <br><br><br>
| [stopPropagation](stop-propagation.md)| [jvm]  <br>Brief description  <br><br><br>阻止冒泡<br><br>  <br>Content  <br>open override fun [stopPropagation](stop-propagation.md)()  <br><br><br>
| [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>


## Properties  
  
|  Name|  Summary| 
|---|---|
| [isDefaultPrevented](index.md#tech.whence.echo.event/AbstractEvent/isDefaultPrevented/#/PointingToDeclaration/)|  [jvm] <br><br>Boolean 是否取消原生事件<br><br>open override var [isDefaultPrevented](index.md#tech.whence.echo.event/AbstractEvent/isDefaultPrevented/#/PointingToDeclaration/): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)   <br>
| [isPropagationStopped](index.md#tech.whence.echo.event/AbstractEvent/isPropagationStopped/#/PointingToDeclaration/)|  [jvm] <br><br>Boolean 是否禁止冒泡<br><br>open override var [isPropagationStopped](index.md#tech.whence.echo.event/AbstractEvent/isPropagationStopped/#/PointingToDeclaration/): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)   <br>
| [type](index.md#tech.whence.echo.event/AbstractEvent/type/#/PointingToDeclaration/)|  [jvm] <br><br>KClass<out T> 数据类<br><br>override var [type](index.md#tech.whence.echo.event/AbstractEvent/type/#/PointingToDeclaration/): [KClass](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-class/index.html)<out [T](index.md)>   <br>


## Inheritors  
  
|  Name| 
|---|
| [Event](../../tech.whence.echo.job.manager/-event/index.md)

