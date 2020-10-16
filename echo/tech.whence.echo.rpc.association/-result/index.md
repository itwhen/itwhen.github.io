---
title: Result -
---
//[echo](../../index.md)/[tech.whence.echo.rpc.association](../index.md)/[Result](index.md)



# Result  
 [jvm] 

关联结果

interface [Result](index.md)<[S](index.md) : [Result](index.md)<[S](index.md), [E](index.md), [R](index.md)>, [E](index.md) : [Resource](../../tech.whence.echo.rpc.sample.resource/-resource/index.md), [R](index.md) : [ResourceData](../../tech.whence.echo.rpc.sample.resource/-resource-data/index.md)> : [Decorator](../../tech.whence.echo.rpc.response/-decorator/index.md)<[R](index.md), [E](index.md)>    


## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| E| <br><br>: Resource<br><br>
| R| <br><br>: ResourceData<br><br>
| S| <br><br>: Result<S, E, R><br><br>
  


## Types  
  
|  Name|  Summary| 
|---|---|
| [Multiple](-multiple/index.md)| [jvm]  <br>Brief description  <br><br><br>批量关联<br><br>  <br>Content  <br>class [Multiple](-multiple/index.md)<[E](-multiple/index.md) : [Resource](../../tech.whence.echo.rpc.sample.resource/-resource/index.md), [R](-multiple/index.md) : [ResourceData](../../tech.whence.echo.rpc.sample.resource/-resource-data/index.md)>(**data**: [Map](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)<[Association](../-association/index.md)<*, *, [E](-multiple/index.md), [R](-multiple/index.md)>, [Map](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)<[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), [ItemData](../../tech.whence.echo.rpc.sample.item/-item-data/index.md)>>) : [Result](index.md)<[Result.Multiple](-multiple/index.md)<[E](-multiple/index.md), [R](-multiple/index.md)>, [E](-multiple/index.md), [R](-multiple/index.md)>   <br><br><br>
| [Single](-single/index.md)| [jvm]  <br>Brief description  <br><br><br>单关联<br><br>  <br>Content  <br>class [Single](-single/index.md)<[E](-single/index.md) : [Resource](../../tech.whence.echo.rpc.sample.resource/-resource/index.md), [R](-single/index.md) : [ResourceData](../../tech.whence.echo.rpc.sample.resource/-resource-data/index.md)>(**data**: [Map](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)<[Association](../-association/index.md)<*, *, [E](-single/index.md), [R](-single/index.md)>, [ItemData](../../tech.whence.echo.rpc.sample.item/-item-data/index.md)?>) : [Result](index.md)<[Result.Single](-single/index.md)<[E](-single/index.md), [R](-single/index.md)>, [E](-single/index.md), [R](-single/index.md)>   <br><br><br>


## Functions  
  
|  Name|  Summary| 
|---|---|
| [decorate](index.md#tech.whence.echo.rpc.response/Decorator/decorate/#TypeParam(bounds=[tech.whence.echo.rpc.sample.resource.ResourceData])#TypeParam(bounds=[tech.whence.echo.rpc.sample.resource.Resource])/PointingToDeclaration/)| [jvm]  <br>Brief description  <br><br><br>修饰<br><br>  <br>Content  <br>abstract override fun [decorate](index.md#tech.whence.echo.rpc.response/Decorator/decorate/#TypeParam(bounds=[tech.whence.echo.rpc.sample.resource.ResourceData])#TypeParam(bounds=[tech.whence.echo.rpc.sample.resource.Resource])/PointingToDeclaration/)(payload: [R](index.md), data: [E](index.md))  <br><br><br>
| [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)| [jvm]  <br>Content  <br>open operator override fun [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [plus](-multiple/index.md#tech.whence.echo.rpc.response/Decorator/plus/#tech.whence.echo.rpc.response.Decorator[TypeParam(bounds=[tech.whence.echo.rpc.sample.resource.ResourceData]),TypeParam(bounds=[tech.whence.echo.rpc.sample.resource.Resource])]/PointingToDeclaration/)| [jvm]  <br>Brief description  <br><br><br>合并<br><br>  <br>Content  <br>open operator override fun [plus](-multiple/index.md#tech.whence.echo.rpc.response/Decorator/plus/#tech.whence.echo.rpc.response.Decorator[TypeParam(bounds=[tech.whence.echo.rpc.sample.resource.ResourceData]),TypeParam(bounds=[tech.whence.echo.rpc.sample.resource.Resource])]/PointingToDeclaration/)(decorator: [Decorator](../../tech.whence.echo.rpc.response/-decorator/index.md)<[R](index.md), [E](index.md)>): [Decorator](../../tech.whence.echo.rpc.response/-decorator/index.md)<[R](index.md), [E](index.md)>  <br><br><br>
| [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>
| [valid](valid.md)| [jvm]  <br>Brief description  <br><br><br>校验<br><br>  <br>Content  <br>abstract fun [valid](valid.md)(): [S](index.md)  <br><br><br>


## Inheritors  
  
|  Name| 
|---|
| [Result](-single/index.md)
| [Result](-multiple/index.md)

