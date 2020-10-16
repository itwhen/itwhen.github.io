---
title: decode -
---
//[echo](../../index.md)/[tech.whence.echo.codec.decoder](../index.md)/[StringDecoder](index.md)/[decode](decode.md)



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
open override fun [decode](decode.md)(value: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?  


[jvm]  
Brief description  


转换为字符串



#### Return  


String?



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| blankable| <br><br>Boolean 是否允许空字符串<br><br>
| trim| <br><br>Boolean 是否去除前后空格<br><br>
| value| <br><br>Any? 指定值<br><br>
  
  
Content  
fun [decode](decode.md)(value: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?, trim: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), blankable: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?  



