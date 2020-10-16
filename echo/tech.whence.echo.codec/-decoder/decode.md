---
title: decode -
---
//[echo](../../index.md)/[tech.whence.echo.codec](../index.md)/[Decoder](index.md)/[decode](decode.md)



# decode  
[jvm]  
Brief description  


转换指定值到指定类型



#### Return  


T? 无法处理时返回空



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| value| <br><br>Any? 指定值<br><br>
  
  
Content  
abstract fun [decode](decode.md)(value: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [T](index.md)?  


[jvm]  
Brief description  


转换指定值到指定类型后继续下一步骤



#### Return  


R?



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| next| <br><br>@kotlin.ExtensionFunctionType Function1<T, R?> 当转换成功后进行下一步处理<br><br>
| value| <br><br>Any? 指定值<br><br>
  
  
Content  
open fun <[R](decode.md)> [decode](decode.md)(value: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?, next: [T](index.md).() -> [R](decode.md)?): [R](decode.md)?  



