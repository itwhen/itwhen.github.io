---
title: write -
---
//[echo](../../index.md)/[tech.whence.echo.dal.transfer.node](../index.md)/[Node](index.md)/[write](write.md)



# write  
[jvm]  
Brief description  


写数据



#### Return  


Boolean



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| data| <br><br>DEntity 实体<br><br>
| direction| <br><br>Direction 方向<br><br>
| update| <br><br>Boolean 是否是更新<br><br>
  
  
Content  
abstract suspend fun [write](write.md)(direction: [Direction](../-direction/index.md), data: [Record](../../tech.whence.echo.dal.entity/-record/index.md), update: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  


[jvm]  
Brief description  


写数据



#### Return  


Boolean



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| data| <br><br>Set<DEntity> 实体<br><br>
| direction| <br><br>Direction 方向<br><br>
  
  
Content  
abstract suspend fun [write](write.md)(direction: [Direction](../-direction/index.md), data: [Set](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-set/index.html)<[Record](../../tech.whence.echo.dal.entity/-record/index.md)>): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  



