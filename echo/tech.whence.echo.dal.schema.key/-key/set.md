---
title: set -
---
//[echo](../../index.md)/[tech.whence.echo.dal.schema.key](../index.md)/[Key](index.md)/[set](set.md)



# set  
[jvm]  
Brief description  


给指定实体设置当前字段的值 若指定实体是动态实体则直接设置 否则相关实体属性存在则也设置



#### Return  


Key



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| entity| <br><br>E 指定实体<br><br>
| process| <br><br>Boolean 是否自动根据当前字段类型转换指定值<br><br>
| value| <br><br>Any? 指定值<br><br>
  
  
Content  
fun <[E](set.md) : [Entity](../../tech.whence.echo.dal.entity/-entity/index.md)> [set](set.md)(entity: [E](set.md), value: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?, process: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)): [Key](index.md)  



