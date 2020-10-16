---
title: arr -
---
//[echo](../../index.md)/[tech.whence.echo.container.accessor](../index.md)/[Factory](index.md)/[arr](arr.md)



# arr  
[jvm]  
Brief description  


创建列表



#### Return  


ArrayData<Any?>



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| args| <br><br>List<Any?> 指定值<br><br>
  
  
Content  
open fun [arr](arr.md)(args: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?>): [Factory.ArrayData](-array-data/index.md)<[Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?>  


[jvm]  
Brief description  


创建列表



#### Return  


ArrayData<Any?>



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| args| <br><br>Array<out Any?> 指定值<br><br>
  
  
Content  
open fun [arr](arr.md)(vararg args: [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?>): [Factory.ArrayData](-array-data/index.md)<[Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?>  


[jvm]  
Brief description  


创建子列表



#### Return  


ArrayData<S>



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| sub| <br><br>S 指定值<br><br>
  
  
Content  
open fun <[T](arr.md), [S](arr.md) : [Factory.ArrayData](-array-data/index.md)<[T](arr.md)>> [arr](arr.md)(sub: [S](arr.md)): [Factory.ArrayData](-array-data/index.md)<[S](arr.md)>  



