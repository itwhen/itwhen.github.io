---
title: otherwiseIf -
---
//[echo](../index.md)/[tech.whence.echo.function](index.md)/[otherwiseIf](otherwise-if.md)



# otherwiseIf  
[jvm]  
Brief description  


若自身为空且前置条件为真时执行回调返回结果



#### Return  


T?



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| <receiver>| <br><br>T?<br><br>
| create| <br><br>Function0<T?> 回调<br><br>
| predicate| <br><br>Boolean 前置条件<br><br>
  
  
Content  
fun <[T](otherwise-if.md) : [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)> [T](otherwise-if.md)?.[otherwiseIf](otherwise-if.md)(predicate: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), create: () -> [T](otherwise-if.md)?): [T](otherwise-if.md)?  



