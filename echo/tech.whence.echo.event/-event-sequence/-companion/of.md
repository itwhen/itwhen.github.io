---
title: of -
---
//[echo](../../../index.md)/[tech.whence.echo.event](../../index.md)/[EventSequence](../index.md)/[Companion](index.md)/[of](of.md)



# of  
[jvm]  
Brief description  


生产



#### Return  


EventSequence<E>



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| start| <br><br>Producer<List<E>?><br><br>
| stop| <br><br>Producer<List<E>?><br><br>
  
  
Content  
fun <[E](of.md) : [Event](../../-event/index.md)> [of](of.md)(start: [Producer](../../../tech.whence.echo.function/-producer/index.md)<[List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[E](of.md)>?>, stop: [Producer](../../../tech.whence.echo.function/-producer/index.md)<[List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[E](of.md)>?>): [EventSequence](../index.md)<[E](of.md)>  


[jvm]  
Brief description  


转换



#### Return  


EventSequence<E>



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| data| <br><br>T<br><br>
| start| <br><br>Transformer<T, List<E>?><br><br>
| stop| <br><br>Transformer<T, List<E>?><br><br>
  
  
Content  
fun <[E](of.md) : [Event](../../-event/index.md), [T](of.md)> [of](of.md)(start: [Transformer](../../../tech.whence.echo.function/-transformer/index.md)<[T](of.md), [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[E](of.md)>?>, stop: [Transformer](../../../tech.whence.echo.function/-transformer/index.md)<[T](of.md), [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[E](of.md)>?>, data: [T](of.md)): [EventSequence](../index.md)<[E](of.md)>  



