---
title: getConstrainedKeys -
---
//[echo](../../index.md)/[tech.whence.echo.dal.schema](../index.md)/[Schema](index.md)/[getConstrainedKeys](get-constrained-keys.md)



# getConstrainedKeys  
[jvm]  
Brief description  


取指定操作下受约束的字段名集合



#### Return  


Set<String>



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| constraint| <br><br>Constraint 约束<br><br>
| operation| <br><br>EntityOperation 指定操作<br><br>
  
  
Content  
fun [getConstrainedKeys](get-constrained-keys.md)(operation: [Operation](../../tech.whence.echo.dal.dao/-operation/index.md), constraint: [Constraint](../../tech.whence.echo.dal.schema.key/-constraint/index.md)): [Set](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-set/index.html)<[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)>  



