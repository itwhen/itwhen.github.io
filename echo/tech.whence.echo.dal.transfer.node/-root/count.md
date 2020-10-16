---
title: count -
---
//[echo](../../index.md)/[tech.whence.echo.dal.transfer.node](../index.md)/[Root](index.md)/[count](count.md)



# count  
[jvm]  
Brief description  


统计数量



#### Return  


Long



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| direction| <br><br>Direction 方向<br><br>
| endAt| <br><br>LocalDateTime 结束时间<br><br>
| startAt| <br><br>LocalDateTime 开始时间<br><br>
  
  
Content  
abstract suspend fun [count](count.md)(direction: [Direction](../-direction/index.md), startAt: [LocalDateTime](https://docs.oracle.com/javase/8/docs/api/java/time/LocalDateTime.html), endAt: [LocalDateTime](https://docs.oracle.com/javase/8/docs/api/java/time/LocalDateTime.html)): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  


[jvm]  
Brief description  


统计数量



#### Return  


Long



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| direction| <br><br>Direction 方向<br><br>
| key| <br><br>String 字段<br><br>
| value| <br><br>Serializable 值<br><br>
  
  
Content  
abstract suspend fun [count](count.md)(direction: [Direction](../-direction/index.md), key: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), value: [Serializable](https://docs.oracle.com/javase/8/docs/api/java/io/Serializable.html)): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  


[jvm]  
Brief description  


统计数量



#### Return  


Int



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| direction| <br><br>Direction 方向<br><br>
| key| <br><br>String 字段<br><br>
| max| <br><br>Serializable 最大值<br><br>
| min| <br><br>Serializable 最小值<br><br>
  
  
Content  
abstract suspend fun [count](count.md)(direction: [Direction](../-direction/index.md), key: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), min: [Serializable](https://docs.oracle.com/javase/8/docs/api/java/io/Serializable.html), max: [Serializable](https://docs.oracle.com/javase/8/docs/api/java/io/Serializable.html)): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  



