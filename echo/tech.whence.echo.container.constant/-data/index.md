---
title: Data -
---
//[echo](../../index.md)/[tech.whence.echo.container.constant](../index.md)/[Data](index.md)



# Data  
 [jvm] 

常量的值与本身的映射

class [Data](index.md)<[V](index.md) : [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html), [C](index.md) : [Const](../-const/index.md)<[V](index.md)>>(**declarer**: [KClass](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-class/index.html)<[C](index.md)>) : [Container](../../tech.whence.echo.container/-container/index.md)   


## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| C| <br><br>常量<br><br>
| V| <br><br>Any 常量值类型<br><br>
  


## Constructors  
  
|  Name|  Summary| 
|---|---|
| [Data](-data.md)|  [jvm] <br><br>Any 常量值类型<br><br>fun <[C](index.md) : [Const](../-const/index.md)<[V](index.md)>> [Data](-data.md)(declarer: [KClass](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-class/index.html)<[C](index.md)>)   <br>


## Types  
  
|  Name|  Summary| 
|---|---|
| [Companion](-companion/index.md)| [jvm]  <br>Content  <br>object [Companion](-companion/index.md)  <br><br><br>


## Functions  
  
|  Name|  Summary| 
|---|---|
| [describe](describe.md)| [jvm]  <br>Brief description  <br><br><br>生成描述器<br><br>  <br>Content  <br>fun [describe](describe.md)(): [Descriptor](../-descriptor/index.md)  <br><br><br>
| [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)| [jvm]  <br>Content  <br>open operator override fun [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [get](get.md)| [jvm]  <br>Brief description  <br><br><br>根据源值取目标常量<br><br>  <br>Content  <br>operator fun [get](get.md)(value: [V](index.md)?): [C](index.md)?  <br><br><br>
| [guess](guess.md)| [jvm]  <br>Brief description  <br><br><br>根据指定值推断常量 先转换为常量所需值 再根据该值寻找 若找不到且指定搜索模式且值是一个字符串则再当做常量名称去寻找<br><br>  <br>Content  <br>fun [guess](guess.md)(value: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html), search: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)): [C](index.md)?  <br><br><br>
| [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [map](map.md)| [jvm]  <br>Brief description  <br><br><br>根据常量生成映射<br><br>  <br>Content  <br>fun <[K](map.md), [R](map.md)> [map](map.md)(keySelector: ([C](index.md)) -> [K](map.md), valueTransform: ([C](index.md)) -> [R](map.md), filter: [Predicate](../../tech.whence.echo.function/-predicate/index.md)<[C](index.md)>?): [Map](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)<[K](map.md), [R](map.md)>  <br><br><br>
| [search](search.md)| [jvm]  <br>Brief description  <br><br><br>根据指定名称推算常量 用常量名称的大写格式与之比较 不忽略指定名称的大小写<br><br>  <br>Content  <br>fun [search](search.md)(name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): [C](index.md)?  <br><br><br>
| [sequence](sequence.md)| [jvm]  <br>Brief description  <br><br><br>序列化<br><br>  <br>Content  <br>fun [sequence](sequence.md)(): [Sequence](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.sequences/-sequence/index.html)<[C](index.md)>  <br><br><br>
| [set](set.md)| [jvm]  <br>Brief description  <br><br><br>设置<br><br>  <br>Content  <br>operator fun [set](set.md)(name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), const: [C](index.md)): [Data](index.md)<[V](index.md), [C](index.md)>  <br><br><br>
| [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>
| [transfer](transfer.md)| [jvm]  <br>Brief description  <br><br><br>将常量的多个值映射到另一常量<br><br>  <br>Content  <br>inline fun <[TC](transfer.md) : [Enum](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-enum/index.html)<[TC](transfer.md)>, [Const](../-const/index.md)<[V](index.md)>> [transfer](transfer.md)(vararg sources: [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<out [C](index.md)>): [Data](index.md)<[V](index.md), [TC](transfer.md)>  <br><br><br>[jvm]  <br>Brief description  <br><br><br>根据回调将常量的值映射到另一常量<br><br>  <br>Content  <br>inline fun <[TC](transfer.md) : [Enum](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-enum/index.html)<[TC](transfer.md)>, [Const](../-const/index.md)<[V](index.md)>> [transfer](transfer.md)(predicate: [Predicate](../../tech.whence.echo.function/-predicate/index.md)<[V](index.md)>?): [Data](index.md)<[V](index.md), [TC](transfer.md)>  <br><br><br>


## Properties  
  
|  Name|  Summary| 
|---|---|
| [data](index.md#tech.whence.echo.container.constant/Data/data/#/PointingToDeclaration/)|  [jvm] <br><br>MutableMap<V, Pair<String, C>> 映射存放<br><br>val [data](index.md#tech.whence.echo.container.constant/Data/data/#/PointingToDeclaration/): [MutableMap](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-map/index.html)<[V](index.md), [Pair](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-pair/index.html)<[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), [C](index.md)>>   <br>
| [empty](index.md#tech.whence.echo.container.constant/Data/empty/#/PointingToDeclaration/)|  [jvm] <br><br>Boolean 当前容器是否为空<br><br>open override val [empty](index.md#tech.whence.echo.container.constant/Data/empty/#/PointingToDeclaration/): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)   <br>
| [size](index.md#tech.whence.echo.container.constant/Data/size/#/PointingToDeclaration/)|  [jvm] <br><br>UInt 当前容器总数据量<br><br>open override val [size](index.md#tech.whence.echo.container.constant/Data/size/#/PointingToDeclaration/): [UInt](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-u-int/index.html)   <br>

