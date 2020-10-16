---
title: extract -
---
//[echo](../index.md)/[tech.whence.echo.container](index.md)/[extract](extract.md)



# extract  
[jvm]  
Brief description  


将一个列表子项里的某项抽取出来



#### Return  


List<R>



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| <receiver>| <br><br>List<Map<K, V?>> 指定列表<br><br>
| cast| <br><br>Function1<V, R?>? 转换<br><br>
| key| <br><br>K 指定键<br><br>
  
  
Content  
inline fun <[K](extract.md), [V](extract.md) : [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html), [R](extract.md) : [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)> [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[Map](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)<[K](extract.md), [V](extract.md)?>>.[extract](extract.md)(key: [K](extract.md), noinline cast: ([V](extract.md)) -> [R](extract.md)??): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[R](extract.md)>  



