---
title: fixWriteableData -
---
//[echo](../../index.md)/[tech.whence.echo.dal.transfer.node](../index.md)/[AbstractParentNode](index.md)/[fixWriteableData](fix-writeable-data.md)



# fixWriteableData  
[jvm]  
Brief description  


修正可写数据



#### Return  


Set<DEntity>



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| callback| <br><br>Consumer<Record>? 回调<br><br>
| data| <br><br>Set<DEntity> 数据<br><br>
| direction| <br><br>Direction 方向<br><br>
  
  
Content  
open suspend override fun [fixWriteableData](fix-writeable-data.md)(direction: [Direction](../-direction/index.md), data: [Set](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-set/index.html)<[Record](../../tech.whence.echo.dal.entity/-record/index.md)>, callback: [Consumer](../../tech.whence.echo.function/-consumer/index.md)<[Record](../../tech.whence.echo.dal.entity/-record/index.md)>?): [Map](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)<[PK](index.md), [Record](../../tech.whence.echo.dal.entity/-record/index.md)>  



