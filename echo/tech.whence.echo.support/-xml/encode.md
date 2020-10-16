---
title: encode -
---
//[echo](../../index.md)/[tech.whence.echo.support](../index.md)/[Xml](index.md)/[encode](encode.md)



# encode  
[jvm]  
Brief description  


将键值对编码



#### Return  


List<Element>



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| data| <br><br>Pair<String, Any?> 指定键值队<br><br>
  
  
Content  
@[JvmStatic](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-static/index.html)()  
  
fun [encode](encode.md)(data: [Pair](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-pair/index.html)<[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?>): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<Element>  


[jvm]  
Brief description  


转换为字符串



#### Return  


String?



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| charset| <br><br>Charset 字符集 默认UTF*<br><br>
| data| <br><br>Map<String, Any?> 指定值<br><br>
| pretty| <br><br>Boolean 是否格式化<br><br>
| root| <br><br>String 根名称<br><br>
  
  
Content  
@[JvmStatic](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-static/index.html)()  
@[JvmOverloads](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-overloads/index.html)()  
  
fun [encode](encode.md)(data: [Map](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)<[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?>, root: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), charset: [Charset](https://docs.oracle.com/javase/8/docs/api/java/nio/charset/Charset.html), pretty: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?  



