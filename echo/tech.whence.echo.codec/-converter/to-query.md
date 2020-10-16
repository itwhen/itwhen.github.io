---
title: toQuery -
---
//[echo](../../index.md)/[tech.whence.echo.codec](../index.md)/[Converter](index.md)/[toQuery](to-query.md)



# toQuery  
[jvm]  
Brief description  


转换指定值为查询数据



#### Return  


StringQueryData?



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| assignment| <br><br>String 赋值符<br><br>
| fixer| <br><br>Transformer<String, String>? 纠正器<br><br>
| separator| <br><br>String 分隔符<br><br>
| value| <br><br>Any? 指定值<br><br>
  
  
Content  
@[JvmStatic](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-static/index.html)()  
@[JvmOverloads](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-overloads/index.html)()  
  
fun [toQuery](to-query.md)(value: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?, separator: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), assignment: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), fixer: [Fixer](../../tech.whence.echo.function/-fixer/index.md)<[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)>?): [Map](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)<[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?>?  



