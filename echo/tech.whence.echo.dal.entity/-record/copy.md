---
title: copy -
---
//[echo](../../index.md)/[tech.whence.echo.dal.entity](../index.md)/[Record](index.md)/[copy](copy.md)



# copy  
[jvm]  
Brief description  


按指定条件复制



#### Return  


DynamicEntity



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| predicate| <br><br>Predicate<Key> 指定条件<br><br>
  
  
Content  
fun [copy](copy.md)(predicate: [Predicate](../../tech.whence.echo.function/-predicate/index.md)<[Key](../../tech.whence.echo.dal.schema.key/-key/index.md)>): [Record](index.md)  


[jvm]  
Brief description  


复制



#### Return  


DynamicEntity



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| name| <br><br>String 新名称<br><br>
  
  
Content  
fun [copy](copy.md)(name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): [Record](index.md)  


[jvm]  
Brief description  


赋值



#### Return  


DEntity



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| keys| <br><br>Keys 新字段集合<br><br>
| name| <br><br>String 新名称<br><br>
  
  
Content  
fun [copy](copy.md)(name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), keys: [Keys](../../tech.whence.echo.dal.schema.key/-keys/index.md)): [Record](index.md)  


[jvm]  
Content  
fun [copy](copy.md)(name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), keys: [Keys](../../tech.whence.echo.dal.schema.key/-keys/index.md), data: [Accessor](../../tech.whence.echo.container.accessor/-accessor/index.md), fillable: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)): [Record](index.md)  



