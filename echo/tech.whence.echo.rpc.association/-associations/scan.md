---
title: scan -
---
//[echo](../../index.md)/[tech.whence.echo.rpc.association](../index.md)/[Associations](index.md)/[scan](scan.md)



# scan  
[jvm]  
Brief description  


收集实体相关门面数据



#### Return  


Single<E, R>



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| data| <br><br>E<br><br>
  
  
Content  
suspend fun [scan](scan.md)(data: [E](index.md)): [Result.Single](../-result/-single/index.md)<[E](index.md), [R](index.md)>  


[jvm]  
Brief description  


收集分页实体内相关门面数据



#### Return  


Multiple<E, R>



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| data| <br><br>Paginator<E><br><br>
  
  
Content  
suspend fun [scan](scan.md)(data: [Paginator](../../tech.whence.echo.container/-paginator/index.md)<[E](index.md)>): [Result.Multiple](../-result/-multiple/index.md)<[E](index.md), [R](index.md)>  
suspend fun [scan](scan.md)(data: [Entities](../../tech.whence.echo.dal.entity/-entities/index.md)<[E](index.md)>): [Result.Multiple](../-result/-multiple/index.md)<[E](index.md), [R](index.md)>  



