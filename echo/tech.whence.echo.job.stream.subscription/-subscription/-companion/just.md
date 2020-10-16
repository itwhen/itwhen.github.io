---
title: just -
---
//[echo](../../../index.md)/[tech.whence.echo.job.stream.subscription](../../index.md)/[Subscription](../index.md)/[Companion](index.md)/[just](just.md)



# just  
[jvm]  
Brief description  


基于指定位置分区的构造



#### Return  


Subscription



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| location| <br><br>String 位置<br><br>
| partitions| <br><br>Partitions 分区<br><br>
  
  
Content  
@[JvmStatic](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-static/index.html)()  
@[JvmOverloads](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-overloads/index.html)()  
  
fun [just](just.md)(location: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), partitions: [Partitions](../../-partitions/index.md)): [Subscription](../index.md)  


[jvm]  
Brief description  


构造



#### Return  


Subscription



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| pipelines| <br><br>Array<out String> 指定管道名称<br><br>
| subscriber| <br><br>Subscriber 订阅者<br><br>
  
  
Content  
@[JvmStatic](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-static/index.html)()  
  
fun [just](just.md)(subscriber: [Subscriber](../../-subscriber/index.md), vararg pipelines: [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<out [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)>): [Subscription](../index.md)  



