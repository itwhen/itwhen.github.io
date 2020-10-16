---
title: fixIf -
---
//[echo](../index.md)/[tech.whence.echo.function](index.md)/[fixIf](fix-if.md)



# fixIf  
[jvm]  
Brief description  


执行指定回调纠正 若前置条件为真时执行回调 否则不执行并返回自身



#### Return  


T



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| <receiver>| <br><br>T<br><br>
| block| <br><br>Function1<T, T><br><br>
| predicate| <br><br>Boolean<br><br>
  
  
Content  
inline fun <[T](fix-if.md) : [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)> [T](fix-if.md).[fixIf](fix-if.md)(predicate: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), block: ([T](fix-if.md)) -> [T](fix-if.md)): [T](fix-if.md)  



