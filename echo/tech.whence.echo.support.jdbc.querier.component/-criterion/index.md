---
title: Criterion -
---
//[echo](../../index.md)/[tech.whence.echo.support.jdbc.querier.component](../index.md)/[Criterion](index.md)



# Criterion  
 [jvm] 

操作

abstract class [Criterion](index.md)<[T](index.md)>(**name**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, **value**: [T](index.md), **template**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)) : [Criterion](../../tech.whence.echo.dal.querier.component/-criterion/index.md)<[T](index.md), [Column](../-column/index.md), [Criterion.Preparation](-preparation/index.md)<[Column](../-column/index.md)>> , [Namer](../../tech.whence.echo.definition/-namer/index.md)   


## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| T| <br><br>子类型<br><br>
  


## Constructors  
  
|  Name|  Summary| 
|---|---|
| [Criterion](-criterion.md)|  [jvm] <br><br><br><br>fun <[T](index.md)> [Criterion](-criterion.md)(name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, value: [T](index.md), template: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html))   <br>


## Types  
  
|  Name|  Summary| 
|---|---|
| [Position](-position/index.md)| [jvm]  <br>Brief description  <br><br><br>位置<br><br>  <br>Content  <br>class [Position](-position/index.md)(**row**: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), **col**: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html))  <br><br><br>
| [Preparation](-preparation/index.md)| [jvm]  <br>Brief description  <br><br><br>已预备结果<br><br>  <br>Content  <br>data class [Preparation](-preparation/index.md)<[A](-preparation/index.md) : [Assignment](../../tech.whence.echo.dal.querier.component/-assignment/index.md)>(**restriction**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, **assignments**: [LinkedHashSet](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-linked-hash-set/index.html)<[A](-preparation/index.md)>)  <br><br><br>


## Functions  
  
|  Name|  Summary| 
|---|---|
| [describe](describe.md)| [jvm]  <br>Brief description  <br><br><br>描述当前操作字段及其值<br><br>  <br>Content  <br>open override fun [describe](describe.md)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>
| [equals](equals.md)| [jvm]  <br>Content  <br>open operator override fun [equals](equals.md)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [hashCode](hash-code.md)| [jvm]  <br>Content  <br>open override fun [hashCode](hash-code.md)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [name](name.md)| [jvm]  <br>Brief description  <br><br><br>取字段名<br><br>  <br>Content  <br>open override fun [name](name.md)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>
| [prefix](prefix.md)| [jvm]  <br>Brief description  <br><br><br>生成前缀<br><br>  <br>Content  <br>open fun [prefix](prefix.md)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>
| [prepare](prepare.md)| [jvm]  <br>Brief description  <br><br><br>准备预备查询字符串及其赋值<br><br>  <br>Content  <br>open override fun [prepare](prepare.md)(): [Criterion.Preparation](-preparation/index.md)<[Column](../-column/index.md)>  <br><br><br>[jvm]  <br>Brief description  <br><br><br>准备当前位置下的预备查询字符串及其赋值<br><br>  <br>Content  <br>open fun [prepare](prepare.md)(position: [Criterion.Position](-position/index.md)): [Criterion.Preparation](-preparation/index.md)<[Column](../-column/index.md)>  <br><br><br>
| [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>


## Properties  
  
|  Name|  Summary| 
|---|---|
| [index](index.md#tech.whence.echo.support.jdbc.querier.component/Criterion/index/#/PointingToDeclaration/)|  [jvm] <br><br>序号<br><br>override var [index](index.md#tech.whence.echo.support.jdbc.querier.component/Criterion/index/#/PointingToDeclaration/): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)   <br>
| [name](name.md)|  [jvm] <br><br>String? 字段名<br><br>open override val [name](name.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?   <br>
| [template](index.md#tech.whence.echo.support.jdbc.querier.component/Criterion/template/#/PointingToDeclaration/)|  [jvm] <br><br>String 格式化模板<br><br>val [template](index.md#tech.whence.echo.support.jdbc.querier.component/Criterion/template/#/PointingToDeclaration/): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)   <br>
| [value](index.md#tech.whence.echo.support.jdbc.querier.component/Criterion/value/#/PointingToDeclaration/)|  [jvm] <br><br>T 相关值<br><br>open override val [value](index.md#tech.whence.echo.support.jdbc.querier.component/Criterion/value/#/PointingToDeclaration/): [T](index.md)   <br>


## Inheritors  
  
|  Name| 
|---|
| [Between](../../tech.whence.echo.support.jdbc.querier.criterion/-between/index.md)
| [Equal](../../tech.whence.echo.support.jdbc.querier.criterion/-equal/index.md)
| [FulltextMatch](../../tech.whence.echo.support.jdbc.querier.criterion/-fulltext-match/index.md)
| [GreaterThan](../../tech.whence.echo.support.jdbc.querier.criterion/-greater-than/index.md)
| [GreaterThanOrEqual](../../tech.whence.echo.support.jdbc.querier.criterion/-greater-than-or-equal/index.md)
| [In](../../tech.whence.echo.support.jdbc.querier.criterion/-in/index.md)
| [IsNotNull](../../tech.whence.echo.support.jdbc.querier.criterion/-is-not-null/index.md)
| [IsNull](../../tech.whence.echo.support.jdbc.querier.criterion/-is-null/index.md)
| [LessThan](../../tech.whence.echo.support.jdbc.querier.criterion/-less-than/index.md)
| [LessThanOrEqual](../../tech.whence.echo.support.jdbc.querier.criterion/-less-than-or-equal/index.md)
| [Like](../../tech.whence.echo.support.jdbc.querier.criterion/-like/index.md)
| [Match](../../tech.whence.echo.support.jdbc.querier.criterion/-match/index.md)
| [NotBetween](../../tech.whence.echo.support.jdbc.querier.criterion/-not-between/index.md)
| [NotEqual](../../tech.whence.echo.support.jdbc.querier.criterion/-not-equal/index.md)
| [NotIn](../../tech.whence.echo.support.jdbc.querier.criterion/-not-in/index.md)
| [NotLike](../../tech.whence.echo.support.jdbc.querier.criterion/-not-like/index.md)
| [NotMatch](../../tech.whence.echo.support.jdbc.querier.criterion/-not-match/index.md)
| [Raw](../../tech.whence.echo.support.jdbc.querier.criterion/-raw/index.md)
| [Sub](../../tech.whence.echo.support.jdbc.querier.criterion/-sub/index.md)

