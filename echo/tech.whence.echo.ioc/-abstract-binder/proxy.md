---
title: proxy -
---
//[echo](../../index.md)/[tech.whence.echo.ioc](../index.md)/[AbstractBinder](index.md)/[proxy](proxy.md)



# proxy  
[jvm]  
Brief description  


创建门面代理



#### Return  


T



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| address| <br><br>String? 指定地址<br><br>
| contractor| <br><br>KClass<T> 指定门面<br><br>
| vertx| <br><br>Vertx<br><br>
  
  
Content  
fun <[T](proxy.md) : [Contractor](../../tech.whence.echo.rpc/-contractor/index.md)> [proxy](proxy.md)(vertx: Vertx, contractor: [KClass](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-class/index.html)<[T](proxy.md)>, address: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?): [T](proxy.md)  



