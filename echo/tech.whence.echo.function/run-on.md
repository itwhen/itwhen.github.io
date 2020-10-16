---
title: runOn -
---
//[echo](../index.md)/[tech.whence.echo.function](index.md)/[runOn](run-on.md)



# runOn  
[jvm]  
Brief description  


执行指定回调 若回调为空返回空 否则执行并返回结果



#### Return  


R?



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| <receiver>| <br><br>T<br><br>
| block| <br><br>@kotlin.ExtensionFunctionType Function1<T, R?>? 回调<br><br>
  
  
Content  
fun <[T](run-on.md) : [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html), [R](run-on.md)> [T](run-on.md).[runOn](run-on.md)(block: [T](run-on.md).() -> [R](run-on.md)??): [R](run-on.md)?  



