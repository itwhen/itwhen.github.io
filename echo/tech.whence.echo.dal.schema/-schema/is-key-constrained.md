---
title: isKeyConstrained -
---
//[echo](../../index.md)/[tech.whence.echo.dal.schema](../index.md)/[Schema](index.md)/[isKeyConstrained](is-key-constrained.md)



# isKeyConstrained  
[jvm]  
Brief description  


判断在指定操作下指定字段有没有受到指定限制



#### Return  


Boolean



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| constraint| <br><br>Constraint 指定约束<br><br>
| key| <br><br>Key 指定字段<br><br>
| operation| <br><br>EntityOperation 指定操作<br><br>
  
  
Content  
fun [isKeyConstrained](is-key-constrained.md)(operation: [Operation](../../tech.whence.echo.dal.dao/-operation/index.md), key: [Key](../../tech.whence.echo.dal.schema.key/-key/index.md), constraint: [Constraint](../../tech.whence.echo.dal.schema.key/-constraint/index.md)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  



