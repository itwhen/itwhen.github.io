---
title: primary -
---
//[echo](../../index.md)/[tech.whence.echo.dal.schema](../index.md)/[Builder](index.md)/[primary](primary.md)



# primary  
[jvm]  
Brief description  


设置主键



#### Return  


TableBuilder<T>



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| generate| <br><br>Boolean 是否是自动创建的<br><br>
| key| <br><br>String 指定字段名称<br><br>
| proxy| <br><br>String? 指定代理字段 一般是编码格式唯一字段用来呈现给前台<br><br>
| type| <br><br>KClass<*>? 指定类型<br><br>
  
  
Content  
@[JvmOverloads](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-overloads/index.html)()  
  
fun [primary](primary.md)(key: [CharSequence](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-char-sequence/index.html), type: [KClass](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-class/index.html)<*>?, generate: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), proxy: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?): [Builder](index.md)<[T](index.md)>  


[jvm]  
Brief description  


设置主键



#### Return  


TableBuilder<T>



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| generate| <br><br>Boolean 是否是自动创建的<br><br>
| key| <br><br>String 指定字段名称<br><br>
| proxy| <br><br>String? 指定代理字段 一般是编码格式唯一字段用来呈现给前台<br><br>
| type| <br><br>Class<*>? 指定类型<br><br>
  
  
Content  
@[JvmOverloads](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-overloads/index.html)()  
  
fun [primary](primary.md)(key: [CharSequence](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-char-sequence/index.html), type: [Class](https://docs.oracle.com/javase/8/docs/api/java/lang/Class.html)<*>, generate: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), proxy: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?): [Builder](index.md)<[T](index.md)>  



