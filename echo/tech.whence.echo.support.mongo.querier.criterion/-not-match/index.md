---
title: NotMatch -
---
//[echo](../../index.md)/[tech.whence.echo.support.mongo.querier.criterion](../index.md)/[NotMatch](index.md)



# NotMatch  
 [jvm] 

匹配

open class [NotMatch](index.md)(**name**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), **value**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)) : [Criterion](../../tech.whence.echo.support.mongo.querier.component/-criterion/index.md)<[Serializable](https://docs.oracle.com/javase/8/docs/api/java/io/Serializable.html)>    


## Constructors  
  
|  Name|  Summary| 
|---|---|
| [NotMatch](-not-match.md)|  [jvm] <br><br><br><br>fun [NotMatch](-not-match.md)(name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), value: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html))   <br>


## Functions  
  
|  Name|  Summary| 
|---|---|
| [describe](../../tech.whence.echo.support.mongo.querier.component/-criterion/describe.md)| [jvm]  <br>Brief description  <br><br><br>描述当前操作字段及其值<br><br>  <br>Content  <br>open override fun [describe](../../tech.whence.echo.support.mongo.querier.component/-criterion/describe.md)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>
| [equals](../../tech.whence.echo.support.mongo.querier.component/-criterion/equals.md)| [jvm]  <br>Content  <br>open operator override fun [equals](../../tech.whence.echo.support.mongo.querier.component/-criterion/equals.md)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [hashCode](../../tech.whence.echo.support.mongo.querier.component/-criterion/hash-code.md)| [jvm]  <br>Content  <br>open override fun [hashCode](../../tech.whence.echo.support.mongo.querier.component/-criterion/hash-code.md)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [prepare](prepare.md)| [jvm]  <br>Brief description  <br><br><br>准备预备查询字符串及其赋值<br><br>  <br>Content  <br>open override fun [prepare](prepare.md)(): JsonObject  <br><br><br>
| [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>


## Properties  
  
|  Name|  Summary| 
|---|---|
| [index](index.md#tech.whence.echo.support.mongo.querier.criterion/NotMatch/index/#/PointingToDeclaration/)|  [jvm] <br><br>序号<br><br>override var [index](index.md#tech.whence.echo.support.mongo.querier.criterion/NotMatch/index/#/PointingToDeclaration/): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)   <br>
| [name](index.md#tech.whence.echo.support.mongo.querier.criterion/NotMatch/name/#/PointingToDeclaration/)|  [jvm] <br><br>String? 字段名<br><br>open override val [name](index.md#tech.whence.echo.support.mongo.querier.criterion/NotMatch/name/#/PointingToDeclaration/): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?   <br>
| [template](index.md#tech.whence.echo.support.mongo.querier.criterion/NotMatch/template/#/PointingToDeclaration/)|  [jvm] <br><br>String 格式化模板<br><br>override val [template](index.md#tech.whence.echo.support.mongo.querier.criterion/NotMatch/template/#/PointingToDeclaration/): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)   <br>
| [value](index.md#tech.whence.echo.support.mongo.querier.criterion/NotMatch/value/#/PointingToDeclaration/)|  [jvm] <br><br>T 相关值<br><br>open override val [value](index.md#tech.whence.echo.support.mongo.querier.criterion/NotMatch/value/#/PointingToDeclaration/): [Serializable](https://docs.oracle.com/javase/8/docs/api/java/io/Serializable.html)   <br>


## Inheritors  
  
|  Name| 
|---|
| [NotLike](../-not-like/index.md)

