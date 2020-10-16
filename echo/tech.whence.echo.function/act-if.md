---
title: actIf -
---
//[echo](../index.md)/[tech.whence.echo.function](index.md)/[actIf](act-if.md)



# actIf  
[jvm]  
Brief description  


若前置条件为真时执行指定转换返回结果 否则强转自身为指定类型



#### Return  


R?



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| <receiver>| <br><br>T<br><br>
| convert| <br><br>@kotlin.ExtensionFunctionType Function1<T, R?> 转换<br><br>
| predicate| <br><br>Boolean<br><br>
  
  
Content  
inline fun <[T](act-if.md) : [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html), [R](act-if.md) : [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)> [T](act-if.md).[actIf](act-if.md)(predicate: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), convert: [T](act-if.md).() -> [R](act-if.md)?): [R](act-if.md)?  



