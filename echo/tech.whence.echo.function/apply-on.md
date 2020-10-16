---
title: applyOn -
---
//[echo](../index.md)/[tech.whence.echo.function](index.md)/[applyOn](apply-on.md)



# applyOn  
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
| block| <br><br>@kotlin.ExtensionFunctionType Function1<T, Unit>? 回调<br><br>
  
  
Content  
fun <[T](apply-on.md) : [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)> [T](apply-on.md).[applyOn](apply-on.md)(block: [T](apply-on.md).() -> [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)?): [T](apply-on.md)  



