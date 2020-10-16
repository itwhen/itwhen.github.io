---
title: Strategist -
---
//[echo](../../index.md)/[tech.whence.echo.strategy](../index.md)/[Strategist](index.md)



# Strategist  
 [jvm] 

策略管理器 用于存储/访问各种策略

class [Strategist](index.md)(**readonly**: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)) : [Container](../../tech.whence.echo.container/-container/index.md)   


## Constructors  
  
|  Name|  Summary| 
|---|---|
| [Strategist](-strategist.md)|  [jvm] fun [Strategist](-strategist.md)()   <br>
| [Strategist](-strategist.md)|  [jvm] fun [Strategist](-strategist.md)(data: [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<out [Strategy](../-strategy/index.md)>, readonly: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html))   <br>
| [Strategist](-strategist.md)|  [jvm] <br><br><br><br>fun [Strategist](-strategist.md)(readonly: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html))   <br>


## Types  
  
|  Name|  Summary| 
|---|---|
| [Companion](-companion/index.md)| [jvm]  <br>Content  <br>object [Companion](-companion/index.md)  <br><br><br>


## Functions  
  
|  Name|  Summary| 
|---|---|
| [add](add.md)| [jvm]  <br>Brief description  <br><br><br>新增策略<br><br>  <br>Content  <br>fun <[T](add.md) : [Strategy](../-strategy/index.md)> [add](add.md)(strategy: [T](add.md)): [Strategist](index.md)  <br><br><br>
| [clear](clear.md)| [jvm]  <br>Brief description  <br><br><br>清理策略<br><br>  <br>Content  <br>fun [clear](clear.md)(): [Strategist](index.md)  <br><br><br>
| [each](each.md)| [jvm]  <br>Brief description  <br><br><br>找到指定类型策略执行指定回调<br><br>  <br>Content  <br>inline fun <[T](each.md) : [Strategy](../-strategy/index.md)> [each](each.md)(consumer: [Consumer](../../tech.whence.echo.function/-consumer/index.md)<[T](each.md)>)  <br><br><br>
| [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)| [jvm]  <br>Content  <br>open operator override fun [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [has](has.md)| [jvm]  <br>Brief description  <br><br><br>判断指定策略类型是否存在<br><br>  <br>Content  <br>fun <[T](has.md) : [Strategy](../-strategy/index.md)> [has](has.md)(strategy: [KClass](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-class/index.html)<[T](has.md)>): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>[jvm]  <br>Brief description  <br><br><br>判断指定策略是否存在<br><br>  <br>Content  <br>fun <[T](has.md) : [Strategy](../-strategy/index.md)> [has](has.md)(strategy: [Strategy](../-strategy/index.md)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [remove](remove.md)| [jvm]  <br>Brief description  <br><br><br>移除指定策略<br><br>  <br>Content  <br>fun <[T](remove.md) : [Strategy](../-strategy/index.md)> [remove](remove.md)(strategy: [T](remove.md)): [Strategist](index.md)  <br><br><br>
| [sequence](sequence.md)| [jvm]  <br>Brief description  <br><br><br>序列化<br><br>  <br>Content  <br>fun [sequence](sequence.md)(): [Sequence](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.sequences/-sequence/index.html)<[Strategy](../-strategy/index.md)>  <br><br><br>
| [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>


## Properties  
  
|  Name|  Summary| 
|---|---|
| [empty](index.md#tech.whence.echo.strategy/Strategist/empty/#/PointingToDeclaration/)|  [jvm] <br><br>Boolean 当前容器是否为空<br><br>open override val [empty](index.md#tech.whence.echo.strategy/Strategist/empty/#/PointingToDeclaration/): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)   <br>
| [readonly](index.md#tech.whence.echo.strategy/Strategist/readonly/#/PointingToDeclaration/)|  [jvm] <br><br>Boolean 是否只读<br><br>val [readonly](index.md#tech.whence.echo.strategy/Strategist/readonly/#/PointingToDeclaration/): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)   <br>
| [size](index.md#tech.whence.echo.strategy/Strategist/size/#/PointingToDeclaration/)|  [jvm] <br><br>UInt 当前容器总数据量<br><br>open override val [size](index.md#tech.whence.echo.strategy/Strategist/size/#/PointingToDeclaration/): [UInt](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-u-int/index.html)   <br>

