---
title: assemble -
---
//[echo](../../index.md)/[tech.whence.echo.support.mongo](../index.md)/[MongoEntityAssembler](index.md)/[assemble](assemble.md)



# assemble  
[jvm]  
Brief description  


编码实体到目标数据 先找到需要分拆的字段 再将每个字段及其值编译compile 再将每个字段数据封装[pack](pack.md)成目标数据可用类型 再整体编码为目标数据



#### Return  


T?



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| entity| <br><br>E 指定实体<br><br>
| strategist| <br><br>Strategist 策略<br><br>
  
  
Content  
open override fun <[E](assemble.md) : [Entity](../../tech.whence.echo.dal.entity/-entity/index.md)> [assemble](assemble.md)(entity: [E](assemble.md), strategist: [Strategist](../../tech.whence.echo.strategy/-strategist/index.md)): [Set](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-set/index.html)<[Column](../../tech.whence.echo.support.mongo.querier.component/-column/index.md)>?  



