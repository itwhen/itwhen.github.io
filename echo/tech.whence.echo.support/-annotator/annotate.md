---
title: annotate -
---
//[echo](../../index.md)/[tech.whence.echo.support](../index.md)/[Annotator](index.md)/[annotate](annotate.md)



# annotate  
[jvm]  
Brief description  


取属性注解



#### Return  


List<Annotation>?



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| ascending| <br><br>Boolean 是否向父类追溯<br><br>
| declarer| <br><br>KClass<*> 类<br><br>
| name| <br><br>String 属性名<br><br>
  
  
Content  
fun [annotate](annotate.md)(declarer: [KClass](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-class/index.html)<*>, name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), ascending: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[Annotation](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-annotation/index.html)>?  



