---
title: split -
---
//[echo](../../index.md)/[tech.whence.echo.codec.decoder](../index.md)/[StringDecoder](index.md)/[split](split.md)



# split  
[jvm]  
Brief description  


分割字符串



#### Return  


Array<out T>?



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| caster| <br><br>Transformer<String, T> 类型转换方法<br><br>
| splitter| <br><br>Transformer<String, StringArray> 分割方法<br><br>
| value| <br><br>Any? 指定值<br><br>
  
  
Content  
inline fun <[T](split.md) : [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)> [split](split.md)(value: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?, splitter: [Transformer](../../tech.whence.echo.function/-transformer/index.md)<[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<out [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)>>, caster: [Transformer](../../tech.whence.echo.function/-transformer/index.md)<[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), [T](split.md)>): [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<out [T](split.md)>?  


[jvm]  
Brief description  


使用正则分割字符串



#### Return  


Array<out T>?



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| caster| <br><br>Transformer<String, T> 类型转换方法<br><br>
| delimiter| <br><br>Regex? 分隔正则<br><br>
| value| <br><br>Any? 指定值<br><br>
  
  
Content  
inline fun <[T](split.md) : [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)> [split](split.md)(value: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?, delimiter: [Regex](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.text/-regex/index.html)?, caster: [Transformer](../../tech.whence.echo.function/-transformer/index.md)<[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), [T](split.md)>): [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<out [T](split.md)>?  



