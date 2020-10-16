---
title: parse -
---
//[echo](../../index.md)/[tech.whence.echo.dal.schema](../index.md)/[Annotator](index.md)/[parse](parse.md)



# parse  
[jvm]  
Brief description  


解析类注解 表名定义及键名重命名注解



#### Return  


Annotator<T>



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| declarer| <br><br>KClass<T><br><br>
  
  
Content  
fun [parse](parse.md)(declarer: [KClass](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-class/index.html)<[T](index.md)>): [Annotator](index.md)<[T](index.md)>  


[jvm]  
Brief description  


解析字段集合注解 主键定义及其他注解



#### Return  


Annotator<T>



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| keys| <br><br>Keys<br><br>
  
  
Content  
fun [parse](parse.md)(keys: [Keys](../../tech.whence.echo.dal.schema.key/-keys/index.md)): [Annotator](index.md)<[T](index.md)>  


[jvm]  
Brief description  


解析指定字段注解



#### Return  


Annotator<T>



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| annotation| <br><br>Annotation 指定注解<br><br>
| key| <br><br>Key 指定字段<br><br>
  
  
Content  
fun [parse](parse.md)(key: [Key](../../tech.whence.echo.dal.schema.key/-key/index.md), annotation: [Annotation](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-annotation/index.html)): [Annotator](index.md)<[T](index.md)>  



