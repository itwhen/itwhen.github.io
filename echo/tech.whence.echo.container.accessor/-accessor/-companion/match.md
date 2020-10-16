---
title: match -
---
//[echo](../../../index.md)/[tech.whence.echo.container.accessor](../../index.md)/[Accessor](../index.md)/[Companion](index.md)/[match](match.md)



# match  
[jvm]  
Brief description  


基于正则匹配构造 指定分组为键 匹配部分为值



#### Return  


Accessor



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| content| <br><br>String 待匹配内容<br><br>
| groups| <br><br>Array<out String> 分组<br><br>
| pattern| <br><br>Pattern 指定正则<br><br>
  
  
Content  
@[JvmStatic](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-static/index.html)()  
  
fun [match](match.md)(pattern: [Pattern](https://docs.oracle.com/javase/8/docs/api/java/util/regex/Pattern.html), content: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), vararg groups: [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<out [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)>): [Accessor](../index.md)  


[jvm]  
Brief description  


基于正则匹配构造 指定分组为键 匹配部分为值



#### Return  


Accessor



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| content| <br><br>String 待匹配内容<br><br>
| groups| <br><br>Array<out String> 分组<br><br>
| regex| <br><br>Regex 指定正则<br><br>
  
  
Content  
@[JvmStatic](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-static/index.html)()  
  
fun [match](match.md)(regex: [Regex](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.text/-regex/index.html), content: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), vararg groups: [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<out [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)>): [Accessor](../index.md)  



