---
title: adapt -
---
//[echo](../../index.md)/[tech.whence.echo.rpc](../index.md)/[Server](index.md)/[adapt](adapt.md)



# adapt  
[jvm]  
Brief description  


注册服务及其自动适配接口



#### Return  


Server



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| producer| <br><br>Producer<F><br><br>
  
  
Content  
fun <[F](adapt.md) : [Facade](../-facade/index.md), [A](adapt.md) : [Api](../-api/index.md)<[F](adapt.md)>, [Contractor](../-contractor/index.md)> [adapt](adapt.md)(producer: [Producer](../../tech.whence.echo.function/-producer/index.md)<[F](adapt.md)>, adapter: [KClass](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-class/index.html)<[A](adapt.md)>): [Server](index.md)  


[jvm]  
Brief description  


注册服务及其自动适配接口



#### Return  


Server



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| adapter| <br><br>KClass<A><br><br>
| facade| <br><br>KClass<F><br><br>
  
  
Content  
fun <[F](adapt.md) : [Facade](../-facade/index.md), [A](adapt.md) : [Api](../-api/index.md)<[F](adapt.md)>, [Contractor](../-contractor/index.md)> [adapt](adapt.md)(facade: [KClass](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-class/index.html)<out [F](adapt.md)>, adapter: [KClass](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-class/index.html)<[A](adapt.md)>): [Server](index.md)  



