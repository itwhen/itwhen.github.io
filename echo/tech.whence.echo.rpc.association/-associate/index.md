---
title: Associate -
---
//[echo](../../index.md)/[tech.whence.echo.rpc.association](../index.md)/[Associate](index.md)



# Associate  
 [jvm] 

关联身份

data class [Associate](index.md)<[F](index.md) : [Facade](../../tech.whence.echo.rpc/-facade/index.md), [R](index.md) : [ItemData](../../tech.whence.echo.rpc.sample.item/-item-data/index.md)>(**definition**: [Definition](../../tech.whence.echo.definition/-definition/index.md), **create**: () -> [F](index.md), **response**: [KClass](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-class/index.html)<[R](index.md)>)   


## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| F| <br><br>: Facade 门面<br><br>
| R| <br><br>: ItemData 响应<br><br>
  


## Constructors  
  
|  Name|  Summary| 
|---|---|
| [Associate](-associate.md)|  [jvm] <br><br><br><br>fun <[F](index.md) : [Facade](../../tech.whence.echo.rpc/-facade/index.md), [R](index.md) : [ItemData](../../tech.whence.echo.rpc.sample.item/-item-data/index.md)> [Associate](-associate.md)(definition: [Definition](../../tech.whence.echo.definition/-definition/index.md), create: () -> [F](index.md), response: [KClass](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-class/index.html)<[R](index.md)>)   <br>


## Functions  
  
|  Name|  Summary| 
|---|---|
| [component1](component1.md)| [jvm]  <br>Content  <br>operator fun [component1](component1.md)(): [Definition](../../tech.whence.echo.definition/-definition/index.md)  <br><br><br>
| [component2](component2.md)| [jvm]  <br>Content  <br>operator fun [component2](component2.md)(): () -> [F](index.md)  <br><br><br>
| [component3](component3.md)| [jvm]  <br>Content  <br>operator fun [component3](component3.md)(): [KClass](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-class/index.html)<[R](index.md)>  <br><br><br>
| [copy](copy.md)| [jvm]  <br>Content  <br>fun [copy](copy.md)(definition: [Definition](../../tech.whence.echo.definition/-definition/index.md), create: () -> [F](index.md), response: [KClass](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-class/index.html)<[R](index.md)>): [Associate](index.md)<[F](index.md), [R](index.md)>  <br><br><br>
| [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)| [jvm]  <br>Content  <br>open operator override fun [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>


## Properties  
  
|  Name|  Summary| 
|---|---|
| [create](index.md#tech.whence.echo.rpc.association/Associate/create/#/PointingToDeclaration/)|  [jvm] <br><br>Function0<F> 门面生成<br><br>val [create](index.md#tech.whence.echo.rpc.association/Associate/create/#/PointingToDeclaration/): () -> [F](index.md)   <br>
| [definition](index.md#tech.whence.echo.rpc.association/Associate/definition/#/PointingToDeclaration/)|  [jvm] <br><br>Definition 门面定义<br><br>val [definition](index.md#tech.whence.echo.rpc.association/Associate/definition/#/PointingToDeclaration/): [Definition](../../tech.whence.echo.definition/-definition/index.md)   <br>
| [response](index.md#tech.whence.echo.rpc.association/Associate/response/#/PointingToDeclaration/)|  [jvm] <br><br>KClass<R> 响应类<br><br>val [response](index.md#tech.whence.echo.rpc.association/Associate/response/#/PointingToDeclaration/): [KClass](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-class/index.html)<[R](index.md)>   <br>

