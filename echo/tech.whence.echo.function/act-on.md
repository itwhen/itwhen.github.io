---
title: actOn -
---
//[echo](../index.md)/[tech.whence.echo.function](index.md)/[actOn](act-on.md)



# actOn  
[jvm]  
Brief description  


若强转存在执行指定强转返回结果 否则强转自身为指定类型



#### Return  


R?



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| <receiver>| <br><br>T?<br><br>
| act| <br><br>@kotlin.ExtensionFunctionType Function1<T, R?>? 强转<br><br>
  
  
Content  
inline fun <[T](act-on.md) : [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html), [R](act-on.md) : [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)> [T](act-on.md)?.[actOn](act-on.md)(noinline act: [T](act-on.md).() -> [R](act-on.md)??): [R](act-on.md)?  



