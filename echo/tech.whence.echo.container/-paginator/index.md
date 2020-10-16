---
title: Paginator -
---
//[echo](../../index.md)/[tech.whence.echo.container](../index.md)/[Paginator](index.md)



# Paginator  
 [jvm] 

数据分页器

class [Paginator](index.md)<[E](index.md) : [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>(**limit**: [UInt](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-u-int/index.html), **page**: [UInt](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-u-int/index.html)) : [Reference](../../tech.whence.echo.type/-reference/index.md)<[E](index.md)> , [Serializable](https://docs.oracle.com/javase/8/docs/api/java/io/Serializable.html), [Container](../-container/index.md)   


## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| E| <br><br>存放数据类型<br><br>
  


## Constructors  
  
|  Name|  Summary| 
|---|---|
| [Paginator](-paginator.md)|  [jvm] <br><br><br><br>fun [Paginator](-paginator.md)(limit: [UInt](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-u-int/index.html), page: [UInt](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-u-int/index.html))   <br>


## Types  
  
|  Name|  Summary| 
|---|---|
| [Companion](-companion/index.md)| [jvm]  <br>Content  <br>object [Companion](-companion/index.md)  <br><br><br>


## Functions  
  
|  Name|  Summary| 
|---|---|
| [equals](equals.md)| [jvm]  <br>Content  <br>open operator override fun [equals](equals.md)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [extract](extract.md)| [jvm]  <br>Brief description  <br><br><br>取出特定字段<br><br>  <br>Content  <br>fun <[R](extract.md) : [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)> [extract](extract.md)(block: ([E](index.md)) -> [R](extract.md)?): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[R](extract.md)>  <br><br><br>
| [hashCode](hash-code.md)| [jvm]  <br>Content  <br>open override fun [hashCode](hash-code.md)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [map](map.md)| [jvm]  <br>Brief description  <br><br><br>降级输出<br><br>  <br>Content  <br>@[JvmOverloads](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-overloads/index.html)()  <br>  <br>fun <[T](map.md) : [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)> [map](map.md)(declarer: [KClass](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-class/index.html)<[T](map.md)>, fixer: ([T](map.md), [E](index.md)) -> [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)?): [Paginator](index.md)<[T](map.md)>  <br><br><br>
| [toString](to-string.md)| [jvm]  <br>Content  <br>open override fun [toString](to-string.md)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>


## Properties  
  
|  Name|  Summary| 
|---|---|
| [data](index.md#tech.whence.echo.container/Paginator/data/#/PointingToDeclaration/)|  [jvm] <br><br>MutableList<E> 当前数据<br><br>var [data](index.md#tech.whence.echo.container/Paginator/data/#/PointingToDeclaration/): [MutableList](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-list/index.html)<[E](index.md)>   <br>
| [empty](index.md#tech.whence.echo.container/Paginator/empty/#/PointingToDeclaration/)|  [jvm] <br><br>Boolean 当前容器是否为空<br><br>open override val [empty](index.md#tech.whence.echo.container/Paginator/empty/#/PointingToDeclaration/): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)   <br>
| [end](index.md#tech.whence.echo.container/Paginator/end/#/PointingToDeclaration/)|  [jvm] <br><br>UInt 当前数据结束序号<br><br>var [end](index.md#tech.whence.echo.container/Paginator/end/#/PointingToDeclaration/): [UInt](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-u-int/index.html)   <br>
| [limit](index.md#tech.whence.echo.container/Paginator/limit/#/PointingToDeclaration/)|  [jvm] <br><br>UInt 每页容量<br><br>val [limit](index.md#tech.whence.echo.container/Paginator/limit/#/PointingToDeclaration/): [UInt](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-u-int/index.html)   <br>
| [page](index.md#tech.whence.echo.container/Paginator/page/#/PointingToDeclaration/)|  [jvm] <br><br>UInt 当前页码<br><br>val [page](index.md#tech.whence.echo.container/Paginator/page/#/PointingToDeclaration/): [UInt](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-u-int/index.html)   <br>
| [pages](index.md#tech.whence.echo.container/Paginator/pages/#/PointingToDeclaration/)|  [jvm] <br><br>UInt 总页数<br><br>var [pages](index.md#tech.whence.echo.container/Paginator/pages/#/PointingToDeclaration/): [UInt](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-u-int/index.html)   <br>
| [size](index.md#tech.whence.echo.container/Paginator/size/#/PointingToDeclaration/)|  [jvm] <br><br>UInt 当前容器总数据量<br><br>open override val [size](index.md#tech.whence.echo.container/Paginator/size/#/PointingToDeclaration/): [UInt](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-u-int/index.html)   <br>
| [start](index.md#tech.whence.echo.container/Paginator/start/#/PointingToDeclaration/)|  [jvm] <br><br>UInt 当前数据开始序号<br><br>var [start](index.md#tech.whence.echo.container/Paginator/start/#/PointingToDeclaration/): [UInt](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-u-int/index.html)   <br>
| [total](index.md#tech.whence.echo.container/Paginator/total/#/PointingToDeclaration/)|  [jvm] <br><br>UInt 总数据量<br><br>var [total](index.md#tech.whence.echo.container/Paginator/total/#/PointingToDeclaration/): [UInt](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-u-int/index.html)   <br>

