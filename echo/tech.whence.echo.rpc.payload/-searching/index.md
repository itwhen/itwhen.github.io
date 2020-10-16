---
title: Searching -
---
//[echo](../../index.md)/[tech.whence.echo.rpc.payload](../index.md)/[Searching](index.md)



# Searching  
 [jvm] 

搜索

class [Searching](index.md)<[T](index.md) : [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)> : [Payload](../-payload/index.md)   


## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| T| <br><br>: Any 搜索条件类型<br><br>
  


## Constructors  
  
|  Name|  Summary| 
|---|---|
| [Searching](-searching.md)|  [jvm] fun [Searching](-searching.md)()   <br>
| [Searching](-searching.md)|  [jvm] fun <[T](index.md) : [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)> [Searching](-searching.md)(limit: [UInt](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-u-int/index.html), page: [UInt](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-u-int/index.html), data: [T](index.md))   <br>


## Functions  
  
|  Name|  Summary| 
|---|---|
| [blueprint](blueprint.md)| [jvm]  <br>Brief description  <br><br><br>生成查询条件<br><br>  <br>Content  <br>@[JvmOverloads](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-overloads/index.html)()  <br>  <br>fun [blueprint](blueprint.md)(keys: [Keys](../../tech.whence.echo.dal.schema.key/-keys/index.md), defaultLimit: [UInt](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-u-int/index.html), defaultPage: [UInt](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-u-int/index.html), fixer: [Consumer](../../tech.whence.echo.function/-consumer/index.md)<[Criteria](../../tech.whence.echo.dal.filter/-criteria/index.md)>?): [Criteria](../../tech.whence.echo.dal.filter/-criteria/index.md)  <br><br><br>
| [check](check.md)| [jvm]  <br>Brief description  <br><br><br>检查参数是否超出限制<br><br>  <br>Content  <br>fun [check](check.md)(): [Searching](index.md)<[T](index.md)>  <br><br><br>
| [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)| [jvm]  <br>Content  <br>open operator override fun [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [toString](to-string.md)| [jvm]  <br>Content  <br>open override fun [toString](to-string.md)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>


## Properties  
  
|  Name|  Summary| 
|---|---|
| [filter](index.md#tech.whence.echo.rpc.payload/Searching/filter/#/PointingToDeclaration/)|  [jvm] <br><br>T? 指定搜索条件<br><br>val [filter](index.md#tech.whence.echo.rpc.payload/Searching/filter/#/PointingToDeclaration/): [T](index.md)?   <br>
| [limit](index.md#tech.whence.echo.rpc.payload/Searching/limit/#/PointingToDeclaration/)|  [jvm] <br><br>UInt? 每页负载<br><br>val [limit](index.md#tech.whence.echo.rpc.payload/Searching/limit/#/PointingToDeclaration/): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)   <br>
| [page](index.md#tech.whence.echo.rpc.payload/Searching/page/#/PointingToDeclaration/)|  [jvm] <br><br>UInt? 指定页码<br><br>val [page](index.md#tech.whence.echo.rpc.payload/Searching/page/#/PointingToDeclaration/): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)   <br>

