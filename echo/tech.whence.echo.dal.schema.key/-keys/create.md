---
title: create -
---
//[echo](../../index.md)/[tech.whence.echo.dal.schema.key](../index.md)/[Keys](index.md)/[create](create.md)



# create  
[jvm]  
Brief description  


根据当前字段集合创建字段



#### Return  


Key



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| existence| <br><br>Existence 存在方式<br><br>
| name| <br><br>String 指定字段名<br><br>
| type| <br><br>KClass<*> 指定字段类型<br><br>
  
  
Content  
fun [create](create.md)(name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), type: [KClass](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-class/index.html)<*>, existence: [Existence](../-existence/index.md)): [Key](../-key/index.md)  



