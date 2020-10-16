---
title: require -
---
//[echo](../../index.md)/[tech.whence.echo.container](../index.md)/[Accessibility](index.md)/[require](require.md)



# require  
[jvm]  
Brief description  


根据指定类型取值 若找不到明确可识别的则强制转换



#### Return  


Result<T>



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| declarer| <br><br>KClass<T> 指定类型<br><br>
| key| <br><br>K 指定键<br><br>
  
  
Content  
open fun <[T](require.md) : [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)> [require](require.md)(key: [K](index.md), declarer: [KClass](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-class/index.html)<[T](require.md)>): [Reply](../-reply/index.md)<[T](require.md)>  



