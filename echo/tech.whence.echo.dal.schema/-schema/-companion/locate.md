---
title: locate -
---
//[echo](../../../index.md)/[tech.whence.echo.dal.schema](../../index.md)/[Schema](../index.md)/[Companion](index.md)/[locate](locate.md)



# locate  
[jvm]  
Brief description  


基于实体类型构造 若指定表名为空将以指定实体类型名称为准



#### Return  


TableBuilder<T>



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| declarer| <br><br>KClass<T> 指定类型<br><br>
| schema| <br><br>String? 指定表名<br><br>
  
  
Content  
fun <[T](locate.md) : [Entity](../../../tech.whence.echo.dal.entity/-entity/index.md)> [locate](locate.md)(declarer: [KClass](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-class/index.html)<[T](locate.md)>, schema: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?): [Builder](../../-builder/index.md)<[T](locate.md)>  


[jvm]  
Brief description  


基于实体类型构造



#### Return  


TableBuilder<T>



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| schema| <br><br>String? 指定表名<br><br>
  
  
Content  
inline fun <[T](locate.md) : [Entity](../../../tech.whence.echo.dal.entity/-entity/index.md)> [locate](locate.md)(schema: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?): [Builder](../../-builder/index.md)<[T](locate.md)>  


[jvm]  
Brief description  


基于实体类型构造



#### Return  


TableBuilder<T>



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| declarer| <br><br>Class<T> 指定类型<br><br>
| schema| <br><br>String? 指定表名<br><br>
  
  
Content  
fun <[T](locate.md) : [Entity](../../../tech.whence.echo.dal.entity/-entity/index.md)> [locate](locate.md)(declarer: [Class](https://docs.oracle.com/javase/8/docs/api/java/lang/Class.html)<[T](locate.md)>, schema: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?): [Builder](../../-builder/index.md)<[T](locate.md)>  



