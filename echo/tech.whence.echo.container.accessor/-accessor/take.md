---
title: take -
---
//[echo](../../index.md)/[tech.whence.echo.container.accessor](../index.md)/[Accessor](index.md)/[take](take.md)



# take  
[jvm]  
Brief description  


根据指定条件调出数据 原数据将移除



#### Return  


Accessor 调出数据



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| predicate| <br><br>Predicate<Entry<String, Any?>> 指定条件<br><br>
  
  
Content  
fun [take](take.md)(predicate: [Predicate](../../tech.whence.echo.function/-predicate/index.md)<[Map.Entry](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/-entry/index.html)<[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?>>): [Accessor](index.md)  


[jvm]  
Brief description  


根据提供的键调出数据 原数据将移除



#### Return  


Accessor 调出数据



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| keys| <br><br>Array<out String> 指定键<br><br>
  
  
Content  
fun [take](take.md)(vararg keys: [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<out [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)>): [Accessor](index.md)  



