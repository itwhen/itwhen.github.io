---
title: read -
---
//[echo](../../index.md)/[tech.whence.echo.dal.transfer.node](../index.md)/[LeafNode](index.md)/[read](read.md)



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
| direction| <br><br>Direction 方向<br><br>
| key| <br><br>String 字段<br><br>
| values| <br><br>Set<Serializable> 值<br><br>
  
  
Content  
abstract suspend fun [read](read.md)(direction: [Direction](../-direction/index.md), key: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), values: [Set](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-set/index.html)<[Serializable](https://docs.oracle.com/javase/8/docs/api/java/io/Serializable.html)>): [Records](../../tech.whence.echo.dal.entity/index.md#tech.whence.echo.dal.entity/Records///PointingToDeclaration/)  



