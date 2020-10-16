---
title: whereIn -
---
//[echo](../../index.md)/[tech.whence.echo.dal.filter](../index.md)/[Filter](index.md)/[whereIn](where-in.md)



# whereIn  
[jvm]  
Brief description  


判断指定字段是否在指定值内



#### Return  


T



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| name| <br><br>String 指定字段名<br><br>
| values| <br><br>Set<V> 指定值<br><br>
  
  
Content  
abstract fun <[V](where-in.md) : [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)> [whereIn](where-in.md)(name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), values: [Set](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-set/index.html)<[V](where-in.md)>): [T](index.md)  


[jvm]  
Brief description  


判断指定字段是否在指定值内



#### Return  


T



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| name| <br><br>String 指定字段名<br><br>
| values| <br><br>Array<out V> 指定值<br><br>
  
  
Content  
open fun <[V](where-in.md) : [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)> [whereIn](where-in.md)(name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), vararg values: [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<out [V](where-in.md)>): [T](index.md)  



