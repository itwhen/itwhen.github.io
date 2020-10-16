---
title: declarer -
---
//[echo](../../index.md)/[tech.whence.echo.dal.schema](../index.md)/[Builder](index.md)/[declarer](declarer.md)



# declarer  
[jvm]  
Brief description  


设置实体类型及其字段集合 将生成静态实体



#### Return  


TableBuilder<T>



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| declarer| <br><br>KClass<T> 指定类型<br><br>
  
  
Content  
fun [declarer](declarer.md)(declarer: [KClass](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-class/index.html)<[T](index.md)>): [Builder](index.md)<[T](index.md)>  


[jvm]  
Brief description  


根据字段名及类型设置实体类型及其字段集合 将生成动态实体



#### Return  


TableBuilder<T>



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| keys| <br><br>Map<String, KClass<*>> 指定字段信息<br><br>
  
  
Content  
fun [declarer](declarer.md)(keys: [Map](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)<[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), [KClass](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-class/index.html)<*>>): [Builder](index.md)<[T](index.md)>  


[jvm]  
Brief description  


根据数据表描述器设置实体类型及其字段 将生成动态实体



#### Return  


TableBuilder<T>



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| describer| <br><br>Describer 描述器<br><br>
  
  
Content  
fun [declarer](declarer.md)(describer: [Describer](../-describer/index.md)): [Builder](index.md)<[T](index.md)>  


[jvm]  
Brief description  


根据字段集合设置实体类型及其字段 将生成动态实体



#### Return  


TableBuilder<T>



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| keys| <br><br>Keys 指定字段集合<br><br>
  
  
Content  
fun [declarer](declarer.md)(keys: [Keys](../../tech.whence.echo.dal.schema.key/-keys/index.md)): [Builder](index.md)<[T](index.md)>  


[jvm]  
Brief description  


设置实体类型及其字段 将生成动态实体



#### Return  


TableBuilder<T>

  
Content  
fun [declarer](declarer.md)(): [Builder](index.md)<[T](index.md)>  



