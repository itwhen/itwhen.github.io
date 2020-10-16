---
title: constraint -
---
//[echo](../../index.md)/[tech.whence.echo.dal.schema](../index.md)/[Builder](index.md)/[constraint](constraint.md)



# constraint  
[jvm]  
Brief description  


设置字段约束



#### Return  


TableBuilder<T>



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| constraint| <br><br>Constraint 指定约束<br><br>
| keys| <br><br>Array<out CharSequence> 指定字段名称<br><br>
| operation| <br><br>EntityOperation 实体操作<br><br>
  
  
Content  
fun [constraint](constraint.md)(operation: [Operation](../../tech.whence.echo.dal.dao/-operation/index.md), constraint: [Constraint](../../tech.whence.echo.dal.schema.key/-constraint/index.md), vararg keys: [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<out [CharSequence](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-char-sequence/index.html)>): [Builder](index.md)<[T](index.md)>  



