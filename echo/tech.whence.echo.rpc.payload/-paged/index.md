---
title: Paged -
---
//[echo](../../index.md)/[tech.whence.echo.rpc.payload](../index.md)/[Paged](index.md)



# Paged  
 [jvm] 

分页型负载

data class [Paged](index.md)<[T](index.md) : [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>(**pages**: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), **page**: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), **limit**: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), **total**: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), **data**: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[T](index.md)>) : [Payload](../-payload/index.md)   


## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| T| <br><br>: Any 数据类型<br><br>
  


## Constructors  
  
|  Name|  Summary| 
|---|---|
| [Paged](-paged.md)|  [jvm] <br><br>: Any 数据类型<br><br>fun <[T](index.md) : [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)> [Paged](-paged.md)(pages: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), page: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), limit: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), total: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), data: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[T](index.md)>)   <br>


## Types  
  
|  Name|  Summary| 
|---|---|
| [Companion](-companion/index.md)| [jvm]  <br>Content  <br>object [Companion](-companion/index.md)  <br><br><br>


## Functions  
  
|  Name|  Summary| 
|---|---|
| [associate](associate.md)| [jvm]  <br>Brief description  <br><br><br>遍历<br><br>  <br>Content  <br>fun <[K](associate.md), [V](associate.md)> [associate](associate.md)(transformer: [Transformer](../../tech.whence.echo.function/-transformer/index.md)<[T](index.md), [Pair](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-pair/index.html)<[K](associate.md), [V](associate.md)>>): [Map](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)<[K](associate.md), [V](associate.md)>  <br><br><br>
| [component1](component1.md)| [jvm]  <br>Content  <br>operator fun [component1](component1.md)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [component2](component2.md)| [jvm]  <br>Content  <br>operator fun [component2](component2.md)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [component3](component3.md)| [jvm]  <br>Content  <br>operator fun [component3](component3.md)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [component4](component4.md)| [jvm]  <br>Content  <br>operator fun [component4](component4.md)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [component5](component5.md)| [jvm]  <br>Content  <br>operator fun [component5](component5.md)(): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[T](index.md)>  <br><br><br>
| [copy](copy.md)| [jvm]  <br>Content  <br>fun [copy](copy.md)(pages: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), page: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), limit: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), total: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), data: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[T](index.md)>): [Paged](index.md)<[T](index.md)>  <br><br><br>
| [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)| [jvm]  <br>Content  <br>open operator override fun [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [map](map.md)| [jvm]  <br>Brief description  <br><br><br>遍历<br><br>  <br>Content  <br>fun <[R](map.md)> [map](map.md)(transformer: [Transformer](../../tech.whence.echo.function/-transformer/index.md)<[T](index.md), [R](map.md)>): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[R](map.md)>  <br><br><br>
| [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>


## Properties  
  
|  Name|  Summary| 
|---|---|
| [data](index.md#tech.whence.echo.rpc.payload/Paged/data/#/PointingToDeclaration/)|  [jvm] <br><br>List<T>? 数据<br><br>val [data](index.md#tech.whence.echo.rpc.payload/Paged/data/#/PointingToDeclaration/): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[T](index.md)>   <br>
| [limit](index.md#tech.whence.echo.rpc.payload/Paged/limit/#/PointingToDeclaration/)|  [jvm] <br><br>Int? 每页负载<br><br>val [limit](index.md#tech.whence.echo.rpc.payload/Paged/limit/#/PointingToDeclaration/): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)   <br>
| [page](index.md#tech.whence.echo.rpc.payload/Paged/page/#/PointingToDeclaration/)|  [jvm] <br><br>Int? 当前页数<br><br>val [page](index.md#tech.whence.echo.rpc.payload/Paged/page/#/PointingToDeclaration/): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)   <br>
| [pages](index.md#tech.whence.echo.rpc.payload/Paged/pages/#/PointingToDeclaration/)|  [jvm] <br><br>Int? 总页数<br><br>val [pages](index.md#tech.whence.echo.rpc.payload/Paged/pages/#/PointingToDeclaration/): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)   <br>
| [total](index.md#tech.whence.echo.rpc.payload/Paged/total/#/PointingToDeclaration/)|  [jvm] <br><br>Int? 总数量<br><br>val [total](index.md#tech.whence.echo.rpc.payload/Paged/total/#/PointingToDeclaration/): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)   <br>

