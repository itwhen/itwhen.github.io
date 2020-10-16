---
title: invoke -
---
//[echo](../../../index.md)/[tech.whence.echo.container.accessor](../../index.md)/[Accessor](../index.md)/[Companion](index.md)/[invoke](invoke.md)



# invoke  
[jvm]  
Brief description  


基于 Accessor {} 构建



#### Return  


Accessor



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| block| <br><br>@kotlin.ExtensionFunctionType Function1<Accessor, Unit> 调用<br><br>
  
  
Content  
@[JvmStatic](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-static/index.html)()  
  
operator fun [invoke](invoke.md)(block: [Accessor](../index.md).() -> [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)): [Accessor](../index.md)  


[jvm]  
Brief description  


基于多个key-value键值对构造 Accessor(key to value ...)



#### Return  


Accessor



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| entries| <br><br>Array<out Pair<String, Any?>> 数据<br><br>
  
  
Content  
@[JvmStatic](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-static/index.html)()  
  
operator fun [invoke](invoke.md)(vararg entries: [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<out [Pair](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-pair/index.html)<[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?>>): [Accessor](../index.md)  



