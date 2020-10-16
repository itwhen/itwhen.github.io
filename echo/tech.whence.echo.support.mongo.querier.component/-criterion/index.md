---
title: Criterion -
---
//[echo](../../index.md)/[tech.whence.echo.support.mongo.querier.component](../index.md)/[Criterion](index.md)



# Criterion  
 [jvm] 

操作

abstract class [Criterion](index.md)<[T](index.md)>(**name**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, **value**: [T](index.md), **template**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)) : [Criterion](../../tech.whence.echo.dal.querier.component/-criterion/index.md)<[T](index.md), [Column](../-column/index.md), JsonObject>    


## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| T| <br><br>子类型<br><br>
  


## Constructors  
  
|  Name|  Summary| 
|---|---|
| [Criterion](-criterion.md)|  [jvm] <br><br><br><br>fun <[T](index.md)> [Criterion](-criterion.md)(name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, value: [T](index.md), template: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html))   <br>


## Functions  
  
|  Name|  Summary| 
|---|---|
| [describe](describe.md)| [jvm]  <br>Brief description  <br><br><br>描述当前操作字段及其值<br><br>  <br>Content  <br>open override fun [describe](describe.md)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>
| [equals](equals.md)| [jvm]  <br>Content  <br>open operator override fun [equals](equals.md)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [hashCode](hash-code.md)| [jvm]  <br>Content  <br>open override fun [hashCode](hash-code.md)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [prepare](../../tech.whence.echo.dal.querier.component/-criterion/prepare.md)| [jvm]  <br>Brief description  <br><br><br>准备预备查询字符串及其赋值<br><br>  <br>Content  <br>abstract override fun [prepare](../../tech.whence.echo.dal.querier.component/-criterion/prepare.md)(): JsonObject  <br><br><br>
| [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>


## Properties  
  
|  Name|  Summary| 
|---|---|
| [index](index.md#tech.whence.echo.support.mongo.querier.component/Criterion/index/#/PointingToDeclaration/)|  [jvm] <br><br>序号<br><br>override var [index](index.md#tech.whence.echo.support.mongo.querier.component/Criterion/index/#/PointingToDeclaration/): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)   <br>
| [name](index.md#tech.whence.echo.support.mongo.querier.component/Criterion/name/#/PointingToDeclaration/)|  [jvm] <br><br>String? 字段名<br><br>open override val [name](index.md#tech.whence.echo.support.mongo.querier.component/Criterion/name/#/PointingToDeclaration/): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?   <br>
| [template](index.md#tech.whence.echo.support.mongo.querier.component/Criterion/template/#/PointingToDeclaration/)|  [jvm] <br><br>String 格式化模板<br><br>val [template](index.md#tech.whence.echo.support.mongo.querier.component/Criterion/template/#/PointingToDeclaration/): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)   <br>
| [value](index.md#tech.whence.echo.support.mongo.querier.component/Criterion/value/#/PointingToDeclaration/)|  [jvm] <br><br>T 相关值<br><br>open override val [value](index.md#tech.whence.echo.support.mongo.querier.component/Criterion/value/#/PointingToDeclaration/): [T](index.md)   <br>


## Inheritors  
  
|  Name| 
|---|
| [Between](../../tech.whence.echo.support.mongo.querier.criterion/-between/index.md)
| [Equal](../../tech.whence.echo.support.mongo.querier.criterion/-equal/index.md)
| [GreaterThan](../../tech.whence.echo.support.mongo.querier.criterion/-greater-than/index.md)
| [GreaterThanOrEqual](../../tech.whence.echo.support.mongo.querier.criterion/-greater-than-or-equal/index.md)
| [In](../../tech.whence.echo.support.mongo.querier.criterion/-in/index.md)
| [IsNotNull](../../tech.whence.echo.support.mongo.querier.criterion/-is-not-null/index.md)
| [IsNull](../../tech.whence.echo.support.mongo.querier.criterion/-is-null/index.md)
| [LessThan](../../tech.whence.echo.support.mongo.querier.criterion/-less-than/index.md)
| [LessThanOrEqual](../../tech.whence.echo.support.mongo.querier.criterion/-less-than-or-equal/index.md)
| [Match](../../tech.whence.echo.support.mongo.querier.criterion/-match/index.md)
| [NotBetween](../../tech.whence.echo.support.mongo.querier.criterion/-not-between/index.md)
| [NotEqual](../../tech.whence.echo.support.mongo.querier.criterion/-not-equal/index.md)
| [NotIn](../../tech.whence.echo.support.mongo.querier.criterion/-not-in/index.md)
| [NotMatch](../../tech.whence.echo.support.mongo.querier.criterion/-not-match/index.md)
| [Raw](../../tech.whence.echo.support.mongo.querier.criterion/-raw/index.md)
| [Sub](../../tech.whence.echo.support.mongo.querier.criterion/-sub/index.md)

