---
title: readDescendantData -
---
//[echo](../../index.md)/[tech.whence.echo.dal.transfer.node](../index.md)/[ParentNode](index.md)/[readDescendantData](read-descendant-data.md)



# readDescendantData  
[jvm]  
Brief description  


取子节点数据



#### Return  


Map<String, Set<Record>>



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| data| <br><br>Set<Record> 指定数据<br><br>
| mode| <br><br>Mode 模式<br><br>
| nodes| <br><br>Nodes 指定节点<br><br>
  
  
Content  
abstract suspend fun [readDescendantData](read-descendant-data.md)(mode: [Mode](../../tech.whence.echo.dal.transfer/-mode/index.md), nodes: [Nodes](../-nodes/index.md), data: [Set](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-set/index.html)<[Record](../../tech.whence.echo.dal.entity/-record/index.md)>): [Map](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)<[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), [Set](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-set/index.html)<[Record](../../tech.whence.echo.dal.entity/-record/index.md)>>  



