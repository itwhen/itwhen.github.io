---
title: of -
---
//[echo](../../../index.md)/[tech.whence.echo.dal.entity](../../index.md)/[Record](../index.md)/[Companion](index.md)/[of](of.md)



# of  
[jvm]  
Brief description  


基于字段及其类型构造



#### Return  


DynamicEntity



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| data| <br><br>Accessor 数据<br><br>
| fillable| <br><br>Boolean 是否将指定数据填充为原始数据<br><br>
| keys| <br><br>Map<String, KClass<*>> 字段及其类型映射<br><br>
| name| <br><br>String 名称<br><br>
  
  
Content  
@[JvmStatic](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-static/index.html)()  
  
fun [of](of.md)(name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), keys: [Map](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)<[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), [KClass](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-class/index.html)<*>>, data: [Accessor](../../../tech.whence.echo.container.accessor/-accessor/index.md), fillable: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)): [Record](../index.md)  


[jvm]  
Brief description  


基于字段集合构建



#### Return  


DynamicEntity



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| data| <br><br>Accessor 数据<br><br>
| fillable| <br><br>Boolean 是否将指定数据填充为原始数据<br><br>
| keys| <br><br>Keys 字段集合<br><br>
| name| <br><br>String 名称<br><br>
  
  
Content  
@[JvmStatic](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-static/index.html)()  
  
fun [of](of.md)(name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), keys: [Keys](../../../tech.whence.echo.dal.schema.key/-keys/index.md), data: [Accessor](../../../tech.whence.echo.container.accessor/-accessor/index.md), fillable: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)): [Record](../index.md)  



