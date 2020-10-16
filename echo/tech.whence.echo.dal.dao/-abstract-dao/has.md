---
title: has -
---
//[echo](../../index.md)/[tech.whence.echo.dal.dao](../index.md)/[AbstractDao](index.md)/[has](has.md)



# has  
[jvm]  
Brief description  


判断实体是否存在



#### Return  


Boolean



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| entity| <br><br>E 指定实体<br><br>
  
  
Content  
open suspend override fun [has](has.md)(entity: [E](index.md)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  


[jvm]  
Brief description  


判断是否存在



#### Return  


Boolean



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| id| <br><br>Serializable 指定主键值<br><br>
  
  
Content  
open suspend override fun [has](has.md)(id: [PK](index.md)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  



