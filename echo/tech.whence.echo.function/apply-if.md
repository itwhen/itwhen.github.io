---
title: applyIf -
---
//[echo](../index.md)/[tech.whence.echo.function](index.md)/[applyIf](apply-if.md)



# applyIf  
[jvm]  
Brief description  


执行指定回调 若前置条件为真时执行回调 否则不执行



#### Return  


T



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| <receiver>| <br><br>T<br><br>
| block| <br><br>@kotlin.ExtensionFunctionType Function1<T, Unit> 回调<br><br>
| predicate| <br><br>Boolean 前置条件<br><br>
  
  
Content  
inline fun <[T](apply-if.md) : [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)> [T](apply-if.md).[applyIf](apply-if.md)(predicate: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), block: [T](apply-if.md).() -> [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)): [T](apply-if.md)  



