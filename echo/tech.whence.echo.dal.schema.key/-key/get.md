---
title: get -
---
//[echo](../../index.md)/[tech.whence.echo.dal.schema.key](../index.md)/[Key](index.md)/[get](get.md)



# get  
[jvm]  
Brief description  


从指定实体中获取当前字段的值 若当前取值器[watcher](index.md#tech.whence.echo.dal.schema.key/Key/watcher/#/PointingToDeclaration/)有效则直接转换(可用作mock) 若raw为真时获取原始数据 若当前是静态实体字段且相关字段属性存在则获取实体中值 若当前是动态实体字段获取原始数据后根据指定字段类型再进行转换



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| entity| <br><br>实体<br><br>
| raw| <br><br>设置为真时获取原始值不做任何加工<br><br>
  
  
Content  
fun <[E](get.md) : [Entity](../../tech.whence.echo.dal.entity/-entity/index.md)> [get](get.md)(entity: [E](get.md), raw: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)): [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?  



