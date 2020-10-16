---
title: filterWriteableDescendantData -
---
//[echo](../../index.md)/[tech.whence.echo.dal.transfer.node](../index.md)/[ParentNode](index.md)/[filterWriteableDescendantData](filter-writeable-descendant-data.md)



# filterWriteableDescendantData  
[jvm]  
Brief description  


过滤可保存子节点数据



#### Return  


Map<Node<out Serializable>, Set<Record>>



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| data| <br><br>Map<String, Set<Record>> 数据<br><br>
| mode| <br><br>Mode 模式<br><br>
| nodes| <br><br>Nodes 指定节点<br><br>
  
  
Content  
abstract suspend fun [filterWriteableDescendantData](filter-writeable-descendant-data.md)(mode: [Mode](../../tech.whence.echo.dal.transfer/-mode/index.md), nodes: [Nodes](../-nodes/index.md), data: [Map](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)<[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), [Set](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-set/index.html)<[Record](../../tech.whence.echo.dal.entity/-record/index.md)>>): [Map](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)<[Node](../-node/index.md)<out [Serializable](https://docs.oracle.com/javase/8/docs/api/java/io/Serializable.html)>, [Set](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-set/index.html)<[Record](../../tech.whence.echo.dal.entity/-record/index.md)>>  



