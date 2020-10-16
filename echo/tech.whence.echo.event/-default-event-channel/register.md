---
title: register -
---
//[echo](../../index.md)/[tech.whence.echo.event](../index.md)/[DefaultEventChannel](index.md)/[register](register.md)



# register  
[jvm]  
Brief description  


注册事件



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| subject| <br><br>KClass<E> 主题<br><br>
| subscriber| <br><br>Any 订阅者<br><br>
| subscription| <br><br>Subscription<Event> 订阅<br><br>
  
  
Content  
open override fun <[E](register.md) : [Event](../-event/index.md)> [register](register.md)(subscriber: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html), subject: [KClass](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-class/index.html)<[E](register.md)>, subscription: [Subscription](../-subscription/index.md)<[Event](../-event/index.md)>)  



