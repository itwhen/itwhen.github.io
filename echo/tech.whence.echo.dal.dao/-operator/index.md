---
title: Operator -
---
//[echo](../../index.md)/[tech.whence.echo.dal.dao](../index.md)/[Operator](index.md)



# Operator  
 [jvm] 

操作策略管理

class [Operator](index.md)<[E](index.md) : [Entity](../../tech.whence.echo.dal.entity/-entity/index.md)>   


## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| E| <br><br>: Entity 实体类型<br><br>
  


## Constructors  
  
|  Name|  Summary| 
|---|---|
| [Operator](-operator.md)|  [jvm] <br><br>: Entity 实体类型<br><br>fun [Operator](-operator.md)()   <br>


## Functions  
  
|  Name|  Summary| 
|---|---|
| [add](add.md)| [jvm]  <br>Brief description  <br><br><br>增加操作支持的策略<br><br>  <br>Content  <br>fun [add](add.md)(operation: [Operation](../-operation/index.md), strategy: [Strategy](../../tech.whence.echo.strategy/-strategy/index.md)): [Strategist](../../tech.whence.echo.strategy/-strategist/index.md)  <br><br><br>
| [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)| [jvm]  <br>Content  <br>open operator override fun [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [get](get.md)| [jvm]  <br>Brief description  <br><br><br>取指定操作下的策略管理器<br><br>  <br>Content  <br>fun [get](get.md)(operation: [Operation](../-operation/index.md)): [Strategist](../../tech.whence.echo.strategy/-strategist/index.md)  <br><br><br>
| [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [initialize](initialize.md)| [jvm]  <br>Brief description  <br><br><br>初始化<br><br>  <br>Content  <br>fun [initialize](initialize.md)(schema: [Schema](../../tech.whence.echo.dal.schema/-schema/index.md)<[E](index.md)>, constraint: [Constraint](../../tech.whence.echo.dal.schema.key/-constraint/index.md), vararg operations: [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<out [Operation](../-operation/index.md)>)  <br><br><br>
| [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>

