---
title: to -
---
//[echo](../../index.md)/[tech.whence.echo.dal.entity.mapper](../index.md)/[Mapper](index.md)/[to](to.md)



# to  
[jvm]  
Brief description  


使用策略将实体转换 获取实体中实际字段数据及附加数据 再针对字段值的不同类型分别处理 再应用策略处理



#### Return  


T



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| entity| <br><br>E 指定实体<br><br>
| strategist| <br><br>Strategist 转换策略<br><br>
  
  
Content  
abstract fun [to](to.md)(entity: [E](index.md), strategist: [Strategist](../../tech.whence.echo.strategy/-strategist/index.md)?): [T](index.md)  



