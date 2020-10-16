---
title: read -
---
//[echo](../../index.md)/[tech.whence.echo.container](../index.md)/[Accessibility](index.md)/[read](read.md)



# read  
[jvm]  
Brief description  


取值



#### Return  


Result<V>



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| key| <br><br>K 指定键<br><br>
  
  
Content  
abstract fun [read](read.md)(key: [K](index.md)): [Reply](../-reply/index.md)<[V](index.md)>  


[jvm]  
Brief description  


取值并执行下一步



#### Return  


Result<T>



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| key| <br><br>K 指定键<br><br>
| next| <br><br>Transformer<V, T?> 下一步操作<br><br>
  
  
Content  
open fun <[T](read.md) : [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)> [read](read.md)(key: [K](index.md), next: [Transformer](../../tech.whence.echo.function/-transformer/index.md)<[V](index.md), [T](read.md)?>): [Reply](../-reply/index.md)<[T](read.md)>  



