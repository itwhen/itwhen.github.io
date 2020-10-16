---
title: find -
---
//[echo](../../index.md)/[tech.whence.echo.support.mongo](../index.md)/[MongoDao](index.md)/[find](find.md)



# find  
[jvm]  
Brief description  


查找



#### Return  


Entities<E>



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| retriever| <br><br>QR 查找器<br><br>
  
  
Content  
open suspend override fun [find](find.md)(retriever: [Select](../../tech.whence.echo.support.mongo.querier/-select/index.md)): [Entities](../../tech.whence.echo.dal.entity/-entities/index.md)<[E](index.md)>  


[jvm]  
Brief description  


查找 若有数据则每次返回capably大小的列表供消费 回调返回真假来控制是否继续



#### Return  


Unit



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| capably| <br><br>UInt 处理能力<br><br>
| limit| <br><br>UInt 总数据量<br><br>
| predicate| <br><br>Predicate<Entities<E>> 回调<br><br>
| retriever| <br><br>QR 查找器<br><br>
  
  
Content  
open suspend override fun [find](find.md)(retriever: [Select](../../tech.whence.echo.support.mongo.querier/-select/index.md), limit: [UInt](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-u-int/index.html), capably: [UInt](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-u-int/index.html), predicate: [Predicate](../../tech.whence.echo.function/-predicate/index.md)<[Entities](../../tech.whence.echo.dal.entity/-entities/index.md)<[E](index.md)>>)  



