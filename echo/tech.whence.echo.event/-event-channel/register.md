---
title: register -
---
//[echo](../../index.md)/[tech.whence.echo.event](../index.md)/[EventChannel](index.md)/[register](register.md)



# register  
[jvm]  
Brief description  


注册订阅者 遍历订阅者所有方法 寻找含 [Subscribe](../-subscribe/index.md) 注解且只有一个参数的方法 按 [SubscribeAt](../-subscribe-at/index.md) 优先级排序



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| subscriber| <br><br>Any<br><br>
  
  
Content  
open fun [register](register.md)(subscriber: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html))  


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
abstract fun <[E](register.md) : [Event](../-event/index.md)> [register](register.md)(subscriber: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html), subject: [KClass](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-class/index.html)<[E](register.md)>, subscription: [Subscription](../-subscription/index.md)<[Event](../-event/index.md)>)  



