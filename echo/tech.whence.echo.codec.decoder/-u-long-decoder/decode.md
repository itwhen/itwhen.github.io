---
title: decode -
---
//[echo](../../index.md)/[tech.whence.echo.codec.decoder](../index.md)/[ULongDecoder](index.md)/[decode](decode.md)



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
open override fun [decode](decode.md)(value: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [ULong](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-u-long/index.html)?  


[jvm]  
Brief description  


转换字符串



#### Return  


ULong?



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| radix| <br><br>Int?<br><br>
| value| <br><br>CharSequence 指定值<br><br>
  
  
Content  
@[JvmOverloads](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-overloads/index.html)()  
  
fun [decode](decode.md)(value: [CharSequence](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-char-sequence/index.html), radix: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)?): [ULong](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-u-long/index.html)?  



