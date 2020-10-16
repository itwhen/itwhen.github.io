---
title: read -
---
//[echo](../../index.md)/[tech.whence.echo.dal.transfer.node](../index.md)/[AbstractRoot](index.md)/[read](read.md)



# read  
[jvm]  
Brief description  


读取数据



#### Return  


Records



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| direction| <br><br>Direction 方向<br><br>
| key| <br><br>String 字段<br><br>
| limit| <br><br>Int? 每页限制<br><br>
| page| <br><br>Int 当前页码<br><br>
| values| <br><br>Set<Serializable> 值<br><br>
  
  
Content  
open suspend override fun [read](read.md)(direction: [Direction](../-direction/index.md), key: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), values: [Set](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-set/index.html)<[Serializable](https://docs.oracle.com/javase/8/docs/api/java/io/Serializable.html)>, limit: [UInt](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-u-int/index.html), page: [UInt](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-u-int/index.html)): [Records](../../tech.whence.echo.dal.entity/index.md#tech.whence.echo.dal.entity/Records///PointingToDeclaration/)  


[jvm]  
Brief description  


读取数据



#### Return  


Records



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| direction| <br><br>Direction 方向<br><br>
| limit| <br><br>UInt 每页限制<br><br>
| page| <br><br>UInt 当前页码<br><br>
  
  
Content  
open suspend override fun [read](read.md)(direction: [Direction](../-direction/index.md), limit: [UInt](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-u-int/index.html), page: [UInt](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-u-int/index.html)): [Records](../../tech.whence.echo.dal.entity/index.md#tech.whence.echo.dal.entity/Records///PointingToDeclaration/)  


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
| endAt| <br><br>LocalDateTime 结束时间<br><br>
| limit| <br><br>UInt 每页限制<br><br>
| page| <br><br>UInt 当前页码<br><br>
| startAt| <br><br>LocalDateTime 开始时间<br><br>
  
  
Content  
open suspend override fun [read](read.md)(direction: [Direction](../-direction/index.md), startAt: [LocalDateTime](https://docs.oracle.com/javase/8/docs/api/java/time/LocalDateTime.html), endAt: [LocalDateTime](https://docs.oracle.com/javase/8/docs/api/java/time/LocalDateTime.html), limit: [UInt](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-u-int/index.html), page: [UInt](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-u-int/index.html)): [Records](../../tech.whence.echo.dal.entity/index.md#tech.whence.echo.dal.entity/Records///PointingToDeclaration/)  


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
| endAt| <br><br>LocalDateTime 结束时间<br><br>
| max| <br><br>PK 最大值<br><br>
| min| <br><br>PK 最小值<br><br>
| startAt| <br><br>LocalDateTime 开始时间<br><br>
  
  
Content  
open suspend override fun [read](read.md)(direction: [Direction](../-direction/index.md), startAt: [LocalDateTime](https://docs.oracle.com/javase/8/docs/api/java/time/LocalDateTime.html), endAt: [LocalDateTime](https://docs.oracle.com/javase/8/docs/api/java/time/LocalDateTime.html), min: [PK](index.md), max: [PK](index.md)): [Records](../../tech.whence.echo.dal.entity/index.md#tech.whence.echo.dal.entity/Records///PointingToDeclaration/)  


[jvm]  
Brief description  


读取数据



#### Return  


Records



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| direction| <br><br>Direction 方向<br><br>
| key| <br><br>String 字段<br><br>
| limit| <br><br>UInt 每页限制<br><br>
| max| <br><br>Serializable 最大值<br><br>
| min| <br><br>Serializable 最小值<br><br>
| page| <br><br>UInt 当前页码<br><br>
  
  
Content  
open suspend override fun [read](read.md)(direction: [Direction](../-direction/index.md), key: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), min: [Serializable](https://docs.oracle.com/javase/8/docs/api/java/io/Serializable.html), max: [Serializable](https://docs.oracle.com/javase/8/docs/api/java/io/Serializable.html), limit: [UInt](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-u-int/index.html), page: [UInt](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-u-int/index.html)): [Records](../../tech.whence.echo.dal.entity/index.md#tech.whence.echo.dal.entity/Records///PointingToDeclaration/)  



