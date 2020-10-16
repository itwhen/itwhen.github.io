---
title: transact -
---
//[echo](../../index.md)/[tech.whence.echo.support.mongo](../index.md)/[MongoClient](index.md)/[transact](transact.md)



# transact  
[jvm]  
Brief description  


在事务中执行指定回调



#### Return  


R



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| block| <br><br>@kotlin.ExtensionFunctionType SuspendFunction1<C, R> 回调<br><br>
  
  
Content  
open suspend override fun <[R](transact.md)> [transact](transact.md)(block: [SuspendFunction1](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.coroutines/-suspend-function1/index.html)<MongoClient, [R](transact.md)>): [R](transact.md)  



