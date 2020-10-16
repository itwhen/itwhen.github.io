---
title: locate -
---
//[echo](../../../index.md)/[tech.whence.echo.event](../../index.md)/[Subscription](../index.md)/[Companion](index.md)/[locate](locate.md)



# locate  
[jvm]  
Brief description  


基于指定方法构造



#### Return  


Subscription<Event>



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| location| <br><br>KFunction<*> 所在位置<br><br>
| subscriber| <br><br>Any 订阅对象<br><br>
  
  
Content  
@[JvmStatic](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-static/index.html)()  
  
fun [locate](locate.md)(subscriber: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html), location: [KFunction](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-function/index.html)<*>): [Subscription](../index.md)<[Event](../../-event/index.md)>  



