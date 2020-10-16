---
title: get -
---
//[echo](../../index.md)/[tech.whence.echo.dal.entity](../index.md)/[EntityAccessor](index.md)/[get](get.md)



# get  
[jvm]  
Brief description  


取字段值



#### Return  


Any?



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| entity| <br><br>Entity 指定实体<br><br>
| name| <br><br>String 指定字段名<br><br>
  
  
Content  
fun [get](get.md)(entity: [Entity](../-entity/index.md), name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?  


[jvm]  
Brief description  


取字段值 若取原始数据则不做任何转换 失败时将日志记录异常



#### Return  


Any?



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| entity| <br><br>Entity 指定实体<br><br>
| key| <br><br>Key 指定字段<br><br>
| raw| <br><br>Boolean 是否取原始数据<br><br>
| to| <br><br>String? 目标名称<br><br>
  
  
Content  
fun [get](get.md)(entity: [Entity](../-entity/index.md), key: [Key](../../tech.whence.echo.dal.schema.key/-key/index.md), raw: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), to: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?): [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?  



