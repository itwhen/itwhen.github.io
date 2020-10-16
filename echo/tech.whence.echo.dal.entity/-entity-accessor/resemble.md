---
title: resemble -
---
//[echo](../../index.md)/[tech.whence.echo.dal.entity](../index.md)/[EntityAccessor](index.md)/[resemble](resemble.md)



# resemble  
[jvm]  
Brief description  


判断指定实体是否同类 先判断指定实体是否指定实体类型 若是动态实体是否名称与指定名称一致 若静态实体是否跟类名简称一致



#### Return  


Boolean



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| declarer| <br><br>KClass<out Entity> 实体类型<br><br>
| entity| <br><br>Entity 指定实体<br><br>
| name| <br><br>String 名称<br><br>
  
  
Content  
fun [resemble](resemble.md)(entity: [Entity](../-entity/index.md), declarer: [KClass](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-class/index.html)<out [Entity](../-entity/index.md)>, name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  



