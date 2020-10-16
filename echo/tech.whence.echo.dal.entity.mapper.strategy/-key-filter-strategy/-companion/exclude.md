---
title: exclude -
---
//[echo](../../../index.md)/[tech.whence.echo.dal.entity.mapper.strategy](../../index.md)/[KeyFilterStrategy](../index.md)/[Companion](index.md)/[exclude](exclude.md)



# exclude  
[jvm]  
Brief description  


排除指定字段



#### Return  


KeyFilterStrategy



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| names| <br><br>Array<out String> 指定字段名<br><br>
  
  
Content  
@[JvmStatic](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-static/index.html)()  
  
fun [exclude](exclude.md)(vararg names: [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<out [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)>): [KeyFilterStrategy](../index.md)  


[jvm]  
Brief description  


排除指定字段



#### Return  


KeyFilterStrategy



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| creator| <br><br>Creator<Set<String>> 字段提供<br><br>
  
  
Content  
@[JvmStatic](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-static/index.html)()  
  
fun [exclude](exclude.md)(creator: [Producer](../../../tech.whence.echo.function/-producer/index.md)<[Set](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-set/index.html)<[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)>>): [KeyFilterStrategy](../index.md)  



