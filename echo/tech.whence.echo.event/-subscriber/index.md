---
title: Subscriber -
---
//[echo](../../index.md)/[tech.whence.echo.event](../index.md)/[Subscriber](index.md)



# Subscriber  
 [jvm] 

订阅者

data class [Subscriber](index.md)(**location**: [KFunction](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-function/index.html)<*>, **subject**: [KClass](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-class/index.html)<out [Event](../-event/index.md)>?, **priority**: [EventPriority](../-event-priority/index.md))   


## Constructors  
  
|  Name|  Summary| 
|---|---|
| [Subscriber](-subscriber.md)|  [jvm] <br><br><br><br>fun [Subscriber](-subscriber.md)(location: [KFunction](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-function/index.html)<*>, subject: [KClass](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-class/index.html)<out [Event](../-event/index.md)>?, priority: [EventPriority](../-event-priority/index.md))   <br>


## Functions  
  
|  Name|  Summary| 
|---|---|
| [component1](component1.md)| [jvm]  <br>Content  <br>operator fun [component1](component1.md)(): [KFunction](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-function/index.html)<*>  <br><br><br>
| [component2](component2.md)| [jvm]  <br>Content  <br>operator fun [component2](component2.md)(): [KClass](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-class/index.html)<out [Event](../-event/index.md)>?  <br><br><br>
| [component3](component3.md)| [jvm]  <br>Content  <br>operator fun [component3](component3.md)(): [EventPriority](../-event-priority/index.md)  <br><br><br>
| [copy](copy.md)| [jvm]  <br>Content  <br>fun [copy](copy.md)(location: [KFunction](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-function/index.html)<*>, subject: [KClass](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-class/index.html)<out [Event](../-event/index.md)>?, priority: [EventPriority](../-event-priority/index.md)): [Subscriber](index.md)  <br><br><br>
| [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)| [jvm]  <br>Content  <br>open operator override fun [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>


## Properties  
  
|  Name|  Summary| 
|---|---|
| [location](index.md#tech.whence.echo.event/Subscriber/location/#/PointingToDeclaration/)|  [jvm] <br><br>KFunction<*> 所在位置<br><br>var [location](index.md#tech.whence.echo.event/Subscriber/location/#/PointingToDeclaration/): [KFunction](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-function/index.html)<*>   <br>
| [priority](index.md#tech.whence.echo.event/Subscriber/priority/#/PointingToDeclaration/)|  [jvm] <br><br>EventPriority 优先级<br><br>var [priority](index.md#tech.whence.echo.event/Subscriber/priority/#/PointingToDeclaration/): [EventPriority](../-event-priority/index.md)   <br>
| [subject](index.md#tech.whence.echo.event/Subscriber/subject/#/PointingToDeclaration/)|  [jvm] <br><br>KClass<out Event>? 订阅主题<br><br>var [subject](index.md#tech.whence.echo.event/Subscriber/subject/#/PointingToDeclaration/): [KClass](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-class/index.html)<out [Event](../-event/index.md)>?   <br>

