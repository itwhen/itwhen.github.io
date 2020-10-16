---
title: transact -
---
//[echo](../../index.md)/[tech.whence.echo.dal.dao](../index.md)/[Dao](index.md)/[transact](transact.md)



# transact  
[jvm]  
Brief description  


在事务中调用回调 若不支持事务时将直接调用回调



#### Return  


R



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| block| <br><br>@kotlin.ExtensionFunctionType SuspendFunction1<C, R> 指定回调<br><br>
  
  
Content  
abstract suspend fun <[R](transact.md)> [transact](transact.md)(block: [SuspendFunction1](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.coroutines/-suspend-function1/index.html)<[C](index.md), [R](transact.md)>): [R](transact.md)  



