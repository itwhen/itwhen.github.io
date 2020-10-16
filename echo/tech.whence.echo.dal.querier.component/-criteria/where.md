---
title: where -
---
//[echo](../../index.md)/[tech.whence.echo.dal.querier.component](../index.md)/[Criteria](index.md)/[where](where.md)



# where  
[jvm]  
Brief description  


指定约束条件



#### Return  


T



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| criterion| <br><br>C 指定操作<br><br>
  
  
Content  
abstract fun [where](where.md)(criterion: [C](index.md)): [T](index.md)  


[jvm]  
Brief description  


设置子约束



#### Return  


T



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| sub| <br><br>S 子约束<br><br>
  
  
Content  
abstract fun [where](where.md)(sub: [S](index.md)): [T](index.md)  


[jvm]  
Brief description  


判断指定字段是否与指定值相等



#### Return  


T



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| name| <br><br>String 指定字段名<br><br>
| value| <br><br>Any 指定值<br><br>
  
  
Content  
open fun [where](where.md)(name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), value: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)): [T](index.md)  



