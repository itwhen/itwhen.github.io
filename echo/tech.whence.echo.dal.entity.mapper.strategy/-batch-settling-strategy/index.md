---
title: BatchSettlingStrategy -
---
//[echo](../../index.md)/[tech.whence.echo.dal.entity.mapper.strategy](../index.md)/[BatchSettlingStrategy](index.md)



# BatchSettlingStrategy  
 [jvm] 

批量结算策略

abstract class [BatchSettlingStrategy](index.md)<[E](index.md) : [Entity](../../tech.whence.echo.dal.entity/-entity/index.md), [K](index.md), [V](index.md)> : [SettlingStrategy](../-settling-strategy/index.md)<[E](index.md)>    


## Constructors  
  
|  Name|  Summary| 
|---|---|
| [BatchSettlingStrategy](-batch-settling-strategy.md)|  [jvm] fun [BatchSettlingStrategy](-batch-settling-strategy.md)()   <br>


## Types  
  
|  Name|  Summary| 
|---|---|
| [Companion](-companion/index.md)| [jvm]  <br>Content  <br>object [Companion](-companion/index.md)  <br><br><br>


## Functions  
  
|  Name|  Summary| 
|---|---|
| [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)| [jvm]  <br>Content  <br>open operator override fun [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [settle](settle.md)| [jvm]  <br>Brief description  <br><br><br>结算<br><br>  <br>Content  <br>open override fun [settle](settle.md)(batcher: [Batcher](../../tech.whence.echo.dal.entity.mapper/-batcher/index.md)<[E](index.md)>)  <br><br><br>
| [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>

