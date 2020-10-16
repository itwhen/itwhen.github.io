---
title: toStrings -
---
//[echo](../../index.md)/[tech.whence.echo.codec](../index.md)/[Converter](index.md)/[toStrings](to-strings.md)



# toStrings  
[jvm]  
Brief description  


转换指定值为字符串数组 支持前后去空及空判断



#### Return  


StringArray?



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| blankable| <br><br>Boolean 是否允许空字符串<br><br>
| trim| <br><br>Boolean 是否前后去除空格<br><br>
| value| <br><br>Any? 指定值<br><br>
  
  
Content  
@[JvmStatic](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-static/index.html)()  
@[JvmOverloads](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-overloads/index.html)()  
  
fun [toStrings](to-strings.md)(value: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?, trim: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), blankable: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)): [StringArray](../../tech.whence.echo.type/index.md#tech.whence.echo.type/StringArray///PointingToDeclaration/)?  


[jvm]  
Brief description  


根据正则转换指定值为多字符串



#### Return  


StringArray?



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| caster| <br><br>Transformer<String, String>? 解码器<br><br>
| delimiter| <br><br>Regex? 分隔正则<br><br>
| value| <br><br>Any? 指定值<br><br>
  
  
Content  
@[JvmStatic](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-static/index.html)()  
@[JvmOverloads](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-overloads/index.html)()  
  
fun [toStrings](to-strings.md)(value: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?, delimiter: [Regex](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.text/-regex/index.html)?, caster: [Transformer](../../tech.whence.echo.function/-transformer/index.md)<[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)>?): [StringArray](../../tech.whence.echo.type/index.md#tech.whence.echo.type/StringArray///PointingToDeclaration/)?  


[jvm]  
Brief description  


根据分割字符转换指定值为多字符串



#### Return  


StringArray?



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| caster| <br><br>Transformer<String, String>? 解码器<br><br>
| delimiter| <br><br>CharSequence 分割字符串<br><br>
| value| <br><br>Any? 指定值<br><br>
  
  
Content  
@[JvmStatic](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-static/index.html)()  
@[JvmOverloads](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-overloads/index.html)()  
  
fun [toStrings](to-strings.md)(value: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?, delimiter: [CharSequence](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-char-sequence/index.html), caster: [Transformer](../../tech.whence.echo.function/-transformer/index.md)<[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)>?): [StringArray](../../tech.whence.echo.type/index.md#tech.whence.echo.type/StringArray///PointingToDeclaration/)?  



