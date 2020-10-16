---
title: errorIf -
---
//[echo](../index.md)/[tech.whence.echo.function](index.md)/[errorIf](error-if.md)



# errorIf  
[jvm]  
Brief description  


若满足条件抛出异常



#### Return  


Unit



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| <receiver>| <br><br>T<br><br>
| message| <br><br>@kotlin.ExtensionFunctionType Function1<T, String> 消息提供<br><br>
| predicate| <br><br>@kotlin.ExtensionFunctionType Function1<T, Boolean> 判断<br><br>
  
  
Content  
fun <[T](error-if.md) : [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)> [T](error-if.md).[errorIf](error-if.md)(predicate: [T](error-if.md).() -> [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), message: [T](error-if.md).() -> [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): [T](error-if.md)  



