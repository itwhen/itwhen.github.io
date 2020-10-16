---
title: tech.whence.echo.rpc.association -
---
//[echo](../index.md)/[tech.whence.echo.rpc.association](index.md)



# Package tech.whence.echo.rpc.association  


## Types  
  
|  Name|  Summary| 
|---|---|
| [Associate](-associate/index.md)| [jvm]  <br>Brief description  <br><br><br>关联身份<br><br>  <br>Content  <br>data class [Associate](-associate/index.md)<[F](-associate/index.md) : [Facade](../tech.whence.echo.rpc/-facade/index.md), [R](-associate/index.md) : [ItemData](../tech.whence.echo.rpc.sample.item/-item-data/index.md)>(**definition**: [Definition](../tech.whence.echo.definition/-definition/index.md), **create**: () -> [F](-associate/index.md), **response**: [KClass](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-class/index.html)<[R](-associate/index.md)>)  <br><br><br>
| [Association](-association/index.md)| [jvm]  <br>Brief description  <br><br><br>关联<br><br>  <br>Content  <br>data class [Association](-association/index.md)<[F](-association/index.md) : [ItemFacade](../tech.whence.echo.rpc.sample.item/-item-facade/index.md)<*, *, *, [FR](-association/index.md)>, [FR](-association/index.md) : [ItemData](../tech.whence.echo.rpc.sample.item/-item-data/index.md), [E](-association/index.md) : [Resource](../tech.whence.echo.rpc.sample.resource/-resource/index.md), [ER](-association/index.md) : [ResourceData](../tech.whence.echo.rpc.sample.resource/-resource-data/index.md)>(**associate**: [Associate](-associate/index.md)<[F](-association/index.md), [FR](-association/index.md)>, **inhere**: ([E](-association/index.md)) -> [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, **externalize**: ([ER](-association/index.md), [FR](-association/index.md)) -> [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html))  <br><br><br>
| [Associations](-associations/index.md)| [jvm]  <br>Brief description  <br><br><br>关联集合<br><br>  <br>Content  <br>class [Associations](-associations/index.md)<[E](-associations/index.md) : [Resource](../tech.whence.echo.rpc.sample.resource/-resource/index.md), [R](-associations/index.md) : [ResourceData](../tech.whence.echo.rpc.sample.resource/-resource-data/index.md)>  <br><br><br>
| [Result](-result/index.md)| [jvm]  <br>Brief description  <br><br><br>关联结果<br><br>  <br>Content  <br>interface [Result](-result/index.md)<[S](-result/index.md) : [Result](-result/index.md)<[S](-result/index.md), [E](-result/index.md), [R](-result/index.md)>, [E](-result/index.md) : [Resource](../tech.whence.echo.rpc.sample.resource/-resource/index.md), [R](-result/index.md) : [ResourceData](../tech.whence.echo.rpc.sample.resource/-resource-data/index.md)> : [Decorator](../tech.whence.echo.rpc.response/-decorator/index.md)<[R](-result/index.md), [E](-result/index.md)>   <br><br><br>

