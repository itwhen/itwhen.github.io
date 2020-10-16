---
title: Stratagem -
---
//[echo](../../index.md)/[tech.whence.echo.dal.entity.mapper](../index.md)/[Stratagem](index.md)



# Stratagem  
 [jvm] 

策略特征

interface [Stratagem](index.md)<[D](index.md) : [Dao](../../tech.whence.echo.dal.dao/-dao/index.md)<*, *, *>>   


## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| D| <br><br>: DAO<*, *, *> 指定数据访问对象类型<br><br>
  


## Functions  
  
|  Name|  Summary| 
|---|---|
| [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)| [jvm]  <br>Content  <br>open operator override fun [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>


## Properties  
  
|  Name|  Summary| 
|---|---|
| [strategize](index.md#tech.whence.echo.dal.entity.mapper/Stratagem/strategize/#/PointingToDeclaration/)|  [jvm] <br><br>Transformer<D, Strategy> 策略生成<br><br>abstract val [strategize](index.md#tech.whence.echo.dal.entity.mapper/Stratagem/strategize/#/PointingToDeclaration/): [Transformer](../../tech.whence.echo.function/-transformer/index.md)<[D](index.md), [Strategy](../../tech.whence.echo.strategy/-strategy/index.md)>   <br>

