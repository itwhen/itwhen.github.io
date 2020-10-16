---
title: set -
---
//[echo](../../index.md)/[tech.whence.echo.dal.entity](../index.md)/[EntityAccessor](index.md)/[set](set.md)



# set  
[jvm]  
Brief description  


设置字段值



#### Return  


Boolean



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| entity| <br><br>Entity 指定实体<br><br>
| name| <br><br>String 指定字段名<br><br>
| value| <br><br>Any? 指定值<br><br>
  
  
Content  
fun [set](set.md)(entity: [Entity](../-entity/index.md), name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), value: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  


[jvm]  
Brief description  


设置字段值 若设置失败将日志记录异常



#### Return  


Boolean



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| entity| <br><br>Entity 指定实体<br><br>
| from| <br><br>String? 来源名称<br><br>
| key| <br><br>Key 指定字段<br><br>
| value| <br><br>Any? 指定值<br><br>
  
  
Content  
fun [set](set.md)(entity: [Entity](../-entity/index.md), key: [Key](../../tech.whence.echo.dal.schema.key/-key/index.md), value: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?, from: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  



