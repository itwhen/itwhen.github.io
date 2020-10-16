---
title: access -
---
//[echo](../../index.md)/[tech.whence.echo.dal.entity](../index.md)/[Entity](index.md)/[access](access.md)



# access  
[jvm]  
Brief description  


转换



#### Return  


Accessor

  
Content  
open override fun [access](access.md)(): [Accessor](../../tech.whence.echo.container.accessor/-accessor/index.md)  


[jvm]  
Brief description  


使用多个策略将实体转换为字段键值映射 获取实体中实际字段数据及附加数据 再针对字段值的不同类型分别处理 再应用策略处理



#### Return  


Accessor



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| strategist| <br><br>Strategist 转换策略<br><br>
  
  
Content  
open fun [access](access.md)(strategist: [Strategist](../../tech.whence.echo.strategy/-strategist/index.md)): [Accessor](../../tech.whence.echo.container.accessor/-accessor/index.md)  



