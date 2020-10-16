---
title: decode -
---
//[echo](../../index.md)/[tech.whence.echo.codec.decoder](../index.md)/[BigDecimalDecoder](index.md)/[decode](decode.md)



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
open override fun [decode](decode.md)(value: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [BigDecimal](https://docs.oracle.com/javase/8/docs/api/java/math/BigDecimal.html)?  


[jvm]  
Brief description  


转换字符串 为空时置零



#### Return  


BigDecimal



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| context| <br><br>MathContext? 计算上下文<br><br>
| value| <br><br>CharSequence 指定值<br><br>
  
  
Content  
@[JvmOverloads](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-overloads/index.html)()  
  
fun [decode](decode.md)(value: [CharSequence](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-char-sequence/index.html), context: [MathContext](https://docs.oracle.com/javase/8/docs/api/java/math/MathContext.html)?): [BigDecimal](https://docs.oracle.com/javase/8/docs/api/java/math/BigDecimal.html)  



