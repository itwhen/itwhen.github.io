---
title: valuate -
---
//[echo](../../index.md)/[tech.whence.echo.dal.entity.wrapper](../index.md)/[AbstractWrapper](index.md)/[valuate](valuate.md)



# valuate  
[jvm]  
Brief description  


取指定实体指定字段的值 先检查实体有效性 再过滤掉由包装器生成的字段



#### Return  


Any?



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| entity| <br><br>E 指定实体<br><br>
| key| <br><br>Key 指定字段<br><br>
  
  
Content  
fun <[E](valuate.md) : [Entity](../../tech.whence.echo.dal.entity/-entity/index.md)> [valuate](valuate.md)(entity: [E](valuate.md), key: [Key](../../tech.whence.echo.dal.schema.key/-key/index.md)): [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?  



