---
title: toSequence -
---
//[echo](../../index.md)/[tech.whence.echo.codec](../index.md)/[Converter](index.md)/[toSequence](to-sequence.md)



# toSequence  
[jvm]  
Brief description  


转换指定值为一个序列 若指定值为不可迭代对象且 forcible 为真时将指定值包裹在数组中返回否则返回空序列



#### Return  


Sequence<T>?



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| forcible| <br><br>Boolean 是否强转<br><br>
| transformer| <br><br>Transformer<Any?, T?> 转换<br><br>
| value| <br><br>Any? 指定值<br><br>
  
  
Content  
@[JvmStatic](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-static/index.html)()  
  
fun <[T](to-sequence.md) : [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)> [toSequence](to-sequence.md)(value: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?, forcible: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), transformer: [Transformer](../../tech.whence.echo.function/-transformer/index.md)<[Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?, [T](to-sequence.md)?>): [Sequence](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.sequences/-sequence/index.html)<[T](to-sequence.md)>?  


[jvm]  
Brief description  


转换指定值为一个序列



#### Return  


Sequence<T>?



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| forcible| <br><br>Boolean 是否强转<br><br>
| value| <br><br>Any? 指定值<br><br>
  
  
Content  
@[JvmStatic](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-static/index.html)()  
@[JvmOverloads](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-overloads/index.html)()  
  
inline fun <[T](to-sequence.md) : [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)> [toSequence](to-sequence.md)(value: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?, forcible: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)): [Sequence](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.sequences/-sequence/index.html)<[T](to-sequence.md)>?  



