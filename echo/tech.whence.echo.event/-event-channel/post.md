---
title: post -
---
//[echo](../../index.md)/[tech.whence.echo.event](../index.md)/[EventChannel](index.md)/[post](post.md)



# post  
[jvm]  
Brief description  


投递多个事件



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| events| <br><br>List<E> 事件<br><br>
  
  
Content  
open suspend fun <[E](post.md) : [Event](../-event/index.md)> [post](post.md)(events: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[E](post.md)>)  


[jvm]  
Brief description  


投递事件序列 先投递序列开始事件 再执行成功回调 接着投递序列结束事件 若异常则执行失败回调



#### Return  


R?



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| poster| <br><br>Poster<R> 回调<br><br>
| sequence| <br><br>EventSequence<E> 事件序列<br><br>
  
  
Content  
open suspend fun <[E](post.md) : [Event](../-event/index.md), [R](post.md)> [post](post.md)(sequence: [EventSequence](../-event-sequence/index.md)<[E](post.md)>, poster: [Poster](../-poster/index.md)<[R](post.md)>): [R](post.md)?  


[jvm]  
Brief description  


发布事件



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| event| <br><br>E 事件<br><br>
  
  
Content  
abstract suspend fun <[E](post.md) : [Event](../-event/index.md)> [post](post.md)(event: [E](post.md))  



