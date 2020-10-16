---
title: whereNotBetween -
---
//[echo](../../index.md)/[tech.whence.echo.support.jdbc.querier.component](../index.md)/[Criteria](index.md)/[whereNotBetween](where-not-between.md)



# whereNotBetween  
[jvm]  
Brief description  


判断指定字段是否不在指定值范围内



#### Return  


T



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| name| <br><br>String 指定字段<br><br>
| range| <br><br>Pair<V, V> 指定值范围<br><br>
  
  
Content  
open override fun <[V](where-not-between.md) : [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)> [whereNotBetween](where-not-between.md)(name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), range: [Pair](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-pair/index.html)<[V](where-not-between.md), [V](where-not-between.md)>): [T](index.md)  



