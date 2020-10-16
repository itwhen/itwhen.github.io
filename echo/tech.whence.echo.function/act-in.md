---
title: actIn -
---
//[echo](../index.md)/[tech.whence.echo.function](index.md)/[actIn](act-in.md)



# actIn  
[jvm]  
Brief description  


安全强制转换类型 若类型[P](act-in.md)是类型[T](act-in.md)的子类或是后者的类型擦除产物 若自身是[P](act-in.md)则强转为[T](act-in.md) 否则返回空



#### Return  


R?



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| <receiver>| <br><br>Any<br><br>
| block| <br><br>@kotlin.ExtensionFunctionType Function1<T, R?> 回调<br><br>
  
  
Content  
inline fun <[P](act-in.md) : [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html), [T](act-in.md) : [P](act-in.md), [R](act-in.md)> [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html).[actIn](act-in.md)(block: [T](act-in.md).() -> [R](act-in.md)?): [R](act-in.md)?  



