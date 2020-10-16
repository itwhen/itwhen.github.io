---
title: read -
---
//[echo](../../index.md)/[tech.whence.echo.dal.transfer.node](../index.md)/[BranchNode](index.md)/[read](read.md)



# read  
[jvm]  
Brief description  


读取数据



#### Return  


DEntities



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| batch| <br><br>Set<PK> 批次<br><br>
| direction| <br><br>Direction 方向<br><br>
  
  
Content  
abstract suspend fun [read](read.md)(direction: [Direction](../-direction/index.md), batch: [Set](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-set/index.html)<[PK](index.md)>): [Records](../../tech.whence.echo.dal.entity/index.md#tech.whence.echo.dal.entity/Records///PointingToDeclaration/)  



