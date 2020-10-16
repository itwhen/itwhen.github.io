---
title: predicateIf -
---
//[echo](../index.md)/[tech.whence.echo.function](index.md)/[predicateIf](predicate-if.md)



# predicateIf  
[jvm]  
Brief description  


若前置条件为空返回真 若自身为空且前置条件为真时返回真 否则返回假



#### Return  


Boolean



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| <receiver>| <br><br>T?<br><br>
| predicate| <br><br>@kotlin.ExtensionFunctionType Function1<T, Boolean>?<br><br>
  
  
Content  
fun <[T](predicate-if.md) : [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)> [T](predicate-if.md)?.[predicateIf](predicate-if.md)(predicate: [T](predicate-if.md).() -> [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  



