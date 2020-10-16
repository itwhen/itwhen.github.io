---
title: runIf -
---
//[echo](../index.md)/[tech.whence.echo.function](index.md)/[runIf](run-if.md)



# runIf  
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
| block| <br><br>@kotlin.ExtensionFunctionType Function1<T, R?> 回调<br><br>
| predicate| <br><br>Boolean 前置条件<br><br>
  
  
Content  
inline fun <[T](run-if.md) : [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html), [R](run-if.md)> [T](run-if.md).[runIf](run-if.md)(predicate: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), block: [T](run-if.md).() -> [R](run-if.md)?): [R](run-if.md)?  



