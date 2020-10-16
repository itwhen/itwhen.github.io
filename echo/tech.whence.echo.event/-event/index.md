---
title: Event -
---
//[echo](../../index.md)/[tech.whence.echo.event](../index.md)/[Event](index.md)



# Event  
 [jvm] 

事件

interface [Event](index.md)   


## Functions  
  
|  Name|  Summary| 
|---|---|
| [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)| [jvm]  <br>Content  <br>open operator override fun [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [preventDefault](prevent-default.md)| [jvm]  <br>Brief description  <br><br><br>取消默认行为<br><br>  <br>Content  <br>abstract fun [preventDefault](prevent-default.md)()  <br><br><br>
| [stopPropagation](stop-propagation.md)| [jvm]  <br>Brief description  <br><br><br>阻止冒泡<br><br>  <br>Content  <br>abstract fun [stopPropagation](stop-propagation.md)()  <br><br><br>
| [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>


## Properties  
  
|  Name|  Summary| 
|---|---|
| [isDefaultPrevented](index.md#tech.whence.echo.event/Event/isDefaultPrevented/#/PointingToDeclaration/)|  [jvm] <br><br>Boolean 是否取消默认行为<br><br>abstract val [isDefaultPrevented](index.md#tech.whence.echo.event/Event/isDefaultPrevented/#/PointingToDeclaration/): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)   <br>
| [isPropagationStopped](index.md#tech.whence.echo.event/Event/isPropagationStopped/#/PointingToDeclaration/)|  [jvm] <br><br>Boolean 是否阻止冒泡<br><br>abstract val [isPropagationStopped](index.md#tech.whence.echo.event/Event/isPropagationStopped/#/PointingToDeclaration/): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)   <br>
| [type](index.md#tech.whence.echo.event/Event/type/#/PointingToDeclaration/)|  [jvm] <br><br>KClass<*> 类型<br><br>abstract val [type](index.md#tech.whence.echo.event/Event/type/#/PointingToDeclaration/): [KClass](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-class/index.html)<*>   <br>


## Inheritors  
  
|  Name| 
|---|
| [AbstractEvent](../-abstract-event/index.md)

