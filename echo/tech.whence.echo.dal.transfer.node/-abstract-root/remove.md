---
title: remove -
---
//[echo](../../index.md)/[tech.whence.echo.dal.transfer.node](../index.md)/[AbstractRoot](index.md)/[remove](remove.md)



# remove  
[jvm]  
Brief description  


删除数据



#### Return  


Int



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| batch| <br><br>Set<PK> 批次<br><br>
| direction| <br><br>Direction 方向<br><br>
  
  
Content  
open suspend override fun [remove](remove.md)(direction: [Direction](../-direction/index.md), batch: [Set](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-set/index.html)<[PK](index.md)>): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  


[jvm]  
Brief description  


删除数据



#### Return  


Int



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| direction| <br><br>Direction 方向<br><br>
| key| <br><br>String 字段<br><br>
| values| <br><br>Set<Serializable> 值<br><br>
  
  
Content  
open suspend override fun [remove](remove.md)(direction: [Direction](../-direction/index.md), key: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), values: [Set](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-set/index.html)<[Serializable](https://docs.oracle.com/javase/8/docs/api/java/io/Serializable.html)>): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  



