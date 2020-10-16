---
title: DefaultEventChannel -
---
//[echo](../../index.md)/[tech.whence.echo.event](../index.md)/[DefaultEventChannel](index.md)



# DefaultEventChannel  
 [jvm] 

默认事件频道

class [DefaultEventChannel](index.md)(**eventBus**: EventBus, **address**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)) : [EventChannel](../-event-channel/index.md)   


## Constructors  
  
|  Name|  Summary| 
|---|---|
| [DefaultEventChannel](-default-event-channel.md)|  [jvm] fun [DefaultEventChannel](-default-event-channel.md)(eventBus: EventBus, address: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html))   <br>


## Functions  
  
|  Name|  Summary| 
|---|---|
| [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)| [jvm]  <br>Content  <br>open operator override fun [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [post](post.md)| [jvm]  <br>Brief description  <br><br><br>发布事件<br><br>  <br>Content  <br>open suspend override fun <[E](post.md) : [Event](../-event/index.md)> [post](post.md)(event: [E](post.md))  <br><br><br>[jvm]  <br>Brief description  <br><br><br>投递多个事件<br><br>  <br>Content  <br>open suspend override fun <E : [Event](../-event/index.md)> [post](../-event-channel/post.md)(events: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<E>)  <br><br><br>[jvm]  <br>Brief description  <br><br><br>投递事件序列 先投递序列开始事件 再执行成功回调 接着投递序列结束事件 若异常则执行失败回调<br><br>  <br>Content  <br>open suspend override fun <E : [Event](../-event/index.md), R> [post](../-event-channel/post.md)(sequence: [EventSequence](../-event-sequence/index.md)<E>, poster: [Poster](../-poster/index.md)<R>): R?  <br><br><br>
| [register](../-event-channel/register.md)| [jvm]  <br>Brief description  <br><br><br>注册订阅者 遍历订阅者所有方法 寻找含 [Subscribe](../-subscribe/index.md) 注解且只有一个参数的方法 按 [SubscribeAt](../-subscribe-at/index.md) 优先级排序<br><br>  <br>Content  <br>open override fun [register](../-event-channel/register.md)(subscriber: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html))  <br><br><br>[jvm]  <br>Brief description  <br><br><br>注册事件<br><br>  <br>Content  <br>open override fun <[E](register.md) : [Event](../-event/index.md)> [register](register.md)(subscriber: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html), subject: [KClass](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-class/index.html)<[E](register.md)>, subscription: [Subscription](../-subscription/index.md)<[Event](../-event/index.md)>)  <br><br><br>
| [registered](registered.md)| [jvm]  <br>Brief description  <br><br><br>判断是否已注册<br><br>  <br>Content  <br>open override fun [registered](registered.md)(subscriber: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>
| [unregister](unregister.md)| [jvm]  <br>Brief description  <br><br><br>取消注册事件<br><br>  <br>Content  <br>open override fun [unregister](unregister.md)(subscriber: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html))  <br><br><br>

