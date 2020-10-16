---
title: exclude -
---
//[echo](../../../index.md)/[tech.whence.echo.job.stream.subscription](../../index.md)/[Subscription](../index.md)/[Companion](index.md)/[exclude](exclude.md)



# exclude  
[jvm]  
Brief description  


构造



#### Return  


Subscription



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| pipelines| <br><br>Array<out String> 不包含的管道名称<br><br>
| subscriber| <br><br>Subscriber 订阅者<br><br>
  
  
Content  
@[JvmStatic](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-static/index.html)()  
  
fun [exclude](exclude.md)(subscriber: [Subscriber](../../-subscriber/index.md), vararg pipelines: [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<out [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)>): [Subscription](../index.md)  



