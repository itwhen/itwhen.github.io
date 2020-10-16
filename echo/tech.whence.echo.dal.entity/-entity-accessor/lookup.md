---
title: lookup -
---
//[echo](../../index.md)/[tech.whence.echo.dal.entity](../index.md)/[EntityAccessor](index.md)/[lookup](lookup.md)



# lookup  
[jvm]  
Brief description  


查找字段值并执行指定行为 异常时记录



#### Return  


Unit



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| consumer| <br><br>Consumer<Any?> 指定行为<br><br>
| entity| <br><br>Entity 指定实体<br><br>
| key| <br><br>Key 指定字段<br><br>
| to| <br><br>String? 目标名称<br><br>
  
  
Content  
fun [lookup](lookup.md)(entity: [Entity](../-entity/index.md), key: [Key](../../tech.whence.echo.dal.schema.key/-key/index.md), to: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, consumer: [Consumer](../../tech.whence.echo.function/-consumer/index.md)<[Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?>)  



