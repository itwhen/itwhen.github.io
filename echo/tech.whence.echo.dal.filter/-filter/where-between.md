---
title: whereBetween -
---
//[echo](../../index.md)/[tech.whence.echo.dal.filter](../index.md)/[Filter](index.md)/[whereBetween](where-between.md)



# whereBetween  
[jvm]  
Brief description  


判断指定字段是否在指定值范围内



#### Return  


T



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| maxValue| <br><br>V 指定最大值<br><br>
| minValue| <br><br>V 指定最小值<br><br>
| name| <br><br>String 指定字段<br><br>
  
  
Content  
open fun <[V](where-between.md) : [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)> [whereBetween](where-between.md)(name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), minValue: [V](where-between.md), maxValue: [V](where-between.md)): [T](index.md)  


[jvm]  
Brief description  


判断指定字段是否在指定值范围内



#### Return  


T



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| name| <br><br>String 指定字段<br><br>
| range| <br><br>Pair<V, V> 指定值范围<br><br>
  
  
Content  
abstract fun <[V](where-between.md) : [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)> [whereBetween](where-between.md)(name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), range: [Pair](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-pair/index.html)<[V](where-between.md), [V](where-between.md)>): [T](index.md)  



