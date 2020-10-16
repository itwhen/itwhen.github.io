---
title: letIf -
---
//[echo](../index.md)/[tech.whence.echo.function](index.md)/[letIf](let-if.md)



# letIf  
[jvm]  
Brief description  


执行指定回调 若前置条件为真时执行回调并返回结果 否则返回空



#### Return  


R?



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| <receiver>| <br><br>T<br><br>
| block| <br><br>Function1<T, R?> 回调<br><br>
| predicate| <br><br>Boolean 前置条件<br><br>
  
  
Content  
inline fun <[T](let-if.md) : [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html), [R](let-if.md)> [T](let-if.md).[letIf](let-if.md)(predicate: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), block: ([T](let-if.md)) -> [R](let-if.md)?): [R](let-if.md)?  



