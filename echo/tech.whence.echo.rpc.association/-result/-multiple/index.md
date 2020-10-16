---
title: Multiple -
---
//[echo](../../../index.md)/[tech.whence.echo.rpc.association](../../index.md)/[Result](../index.md)/[Multiple](index.md)



# Multiple  
 [jvm] 

批量关联

class [Multiple](index.md)<[E](index.md) : [Resource](../../../tech.whence.echo.rpc.sample.resource/-resource/index.md), [R](index.md) : [ResourceData](../../../tech.whence.echo.rpc.sample.resource/-resource-data/index.md)>(**data**: [Map](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)<[Association](../../-association/index.md)<*, *, [E](index.md), [R](index.md)>, [Map](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)<[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), [ItemData](../../../tech.whence.echo.rpc.sample.item/-item-data/index.md)>>) : [Result](../index.md)<[Result.Multiple](index.md)<[E](index.md), [R](index.md)>, [E](index.md), [R](index.md)>    


## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| E| <br><br>: Resource<br><br>
| R| <br><br>: ResourceData<br><br>
  


## Constructors  
  
|  Name|  Summary| 
|---|---|
| [Multiple](-multiple.md)|  [jvm] <br><br><br><br>fun <[E](index.md) : [Resource](../../../tech.whence.echo.rpc.sample.resource/-resource/index.md), [R](index.md) : [ResourceData](../../../tech.whence.echo.rpc.sample.resource/-resource-data/index.md)> [Multiple](-multiple.md)(data: [Map](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)<[Association](../../-association/index.md)<*, *, [E](index.md), [R](index.md)>, [Map](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)<[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), [ItemData](../../../tech.whence.echo.rpc.sample.item/-item-data/index.md)>>)   <br>


## Functions  
  
|  Name|  Summary| 
|---|---|
| [decorate](decorate.md)| [jvm]  <br>Brief description  <br><br><br>修饰<br><br>  <br>Content  <br>open override fun [decorate](decorate.md)(payload: [R](index.md), data: [E](index.md))  <br><br><br>
| [equals](../../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)| [jvm]  <br>Content  <br>open operator override fun [equals](../../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [get](get.md)| [jvm]  <br>Brief description  <br><br><br>取关联响应<br><br>  <br>Content  <br>inline fun <[FR](get.md)> [get](get.md)(id: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): [FR](get.md)?  <br><br><br>
| [hashCode](../../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [hashCode](../../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [plus](index.md#tech.whence.echo.rpc.response/Decorator/plus/#tech.whence.echo.rpc.response.Decorator[TypeParam(bounds=[tech.whence.echo.rpc.sample.resource.ResourceData]),TypeParam(bounds=[tech.whence.echo.rpc.sample.resource.Resource])]/PointingToDeclaration/)| [jvm]  <br>Brief description  <br><br><br>合并<br><br>  <br>Content  <br>open operator override fun [plus](index.md#tech.whence.echo.rpc.response/Decorator/plus/#tech.whence.echo.rpc.response.Decorator[TypeParam(bounds=[tech.whence.echo.rpc.sample.resource.ResourceData]),TypeParam(bounds=[tech.whence.echo.rpc.sample.resource.Resource])]/PointingToDeclaration/)(decorator: [Decorator](../../../tech.whence.echo.rpc.response/-decorator/index.md)<[R](index.md), [E](index.md)>): [Decorator](../../../tech.whence.echo.rpc.response/-decorator/index.md)<[R](index.md), [E](index.md)>  <br><br><br>
| [toString](../../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [toString](../../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>
| [valid](valid.md)| [jvm]  <br>Brief description  <br><br><br>校验<br><br>  <br>Content  <br>open override fun [valid](valid.md)(): [Result.Multiple](index.md)<[E](index.md), [R](index.md)>  <br><br><br>


## Properties  
  
|  Name|  Summary| 
|---|---|
| [data](index.md#tech.whence.echo.rpc.association/Result.Multiple/data/#/PointingToDeclaration/)|  [jvm] <br><br>Map<Association<*, *, E, R>, Map<String, ItemData>><br><br>val [data](index.md#tech.whence.echo.rpc.association/Result.Multiple/data/#/PointingToDeclaration/): [Map](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)<[Association](../../-association/index.md)<*, *, [E](index.md), [R](index.md)>, [Map](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)<[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), [ItemData](../../../tech.whence.echo.rpc.sample.item/-item-data/index.md)>>   <br>

