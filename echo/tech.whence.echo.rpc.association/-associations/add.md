---
title: add -
---
//[echo](../../index.md)/[tech.whence.echo.rpc.association](../index.md)/[Associations](index.md)/[add](add.md)



# add  
[jvm]  
Brief description  


添加关联



#### Return  


Associations<E, R>



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| externalize| <br><br>Function2<R, FR, Unit> 当前响应纠正<br><br>
| facade| <br><br>Function0<F> 门面提供<br><br>
| inhere| <br><br>Function1<E, String?> 门面编号提取<br><br>
  
  
Content  
inline fun <[F](add.md) : [ItemFacade](../../tech.whence.echo.rpc.sample.item/-item-facade/index.md)<*, *, *, [FR](add.md)>, [FR](add.md) : [ItemData](../../tech.whence.echo.rpc.sample.item/-item-data/index.md)> [add](add.md)(noinline facade: () -> [F](add.md), noinline inhere: ([E](index.md)) -> [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, noinline externalize: ([R](index.md), [FR](add.md)) -> [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)): [Associations](index.md)<[E](index.md), [R](index.md)>  



