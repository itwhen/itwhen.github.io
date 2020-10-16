---
title: write -
---
//[echo](../../index.md)/[tech.whence.echo.dal.transfer.node](../index.md)/[Root](index.md)/[write](write.md)



# write  
[jvm]  
Brief description  


写入数据



#### Return  


Boolean



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| batch| <br><br>Set<PK> 批次<br><br>
| direction| <br><br>Direction 方向<br><br>
| key| <br><br>String 字段<br><br>
| value| <br><br>Serializable 值<br><br>
  
  
Content  
abstract suspend fun [write](write.md)(direction: [Direction](../-direction/index.md), batch: [Set](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-set/index.html)<[PK](index.md)>, key: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), value: [Serializable](https://docs.oracle.com/javase/8/docs/api/java/io/Serializable.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  



