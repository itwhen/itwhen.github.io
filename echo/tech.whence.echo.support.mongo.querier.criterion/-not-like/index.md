---
title: NotLike -
---
//[echo](../../index.md)/[tech.whence.echo.support.mongo.querier.criterion](../index.md)/[NotLike](index.md)



# NotLike  
 [jvm] 

不相似

open class [NotLike](index.md)(**name**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), **value**: [Serializable](https://docs.oracle.com/javase/8/docs/api/java/io/Serializable.html), **prefix**: [CharSequence](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-char-sequence/index.html), **postfix**: [CharSequence](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-char-sequence/index.html)) : [NotMatch](../-not-match/index.md)   


## Constructors  
  
|  Name|  Summary| 
|---|---|
| [NotLike](-not-like.md)|  [jvm] <br><br><br><br>fun [NotLike](-not-like.md)(name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), value: [Serializable](https://docs.oracle.com/javase/8/docs/api/java/io/Serializable.html), prefix: [CharSequence](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-char-sequence/index.html), postfix: [CharSequence](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-char-sequence/index.html))   <br>


## Functions  
  
|  Name|  Summary| 
|---|---|
| [describe](../../tech.whence.echo.support.mongo.querier.component/-criterion/describe.md)| [jvm]  <br>Brief description  <br><br><br>描述当前操作字段及其值<br><br>  <br>Content  <br>open override fun [describe](../../tech.whence.echo.support.mongo.querier.component/-criterion/describe.md)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>
| [equals](../../tech.whence.echo.support.mongo.querier.component/-criterion/equals.md)| [jvm]  <br>Content  <br>open operator override fun [equals](../../tech.whence.echo.support.mongo.querier.component/-criterion/equals.md)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [hashCode](../../tech.whence.echo.support.mongo.querier.component/-criterion/hash-code.md)| [jvm]  <br>Content  <br>open override fun [hashCode](../../tech.whence.echo.support.mongo.querier.component/-criterion/hash-code.md)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [prepare](../-not-match/prepare.md)| [jvm]  <br>Brief description  <br><br><br>准备预备查询字符串及其赋值<br><br>  <br>Content  <br>open override fun [prepare](../-not-match/prepare.md)(): JsonObject  <br><br><br>
| [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>


## Properties  
  
|  Name|  Summary| 
|---|---|
| [index](index.md#tech.whence.echo.support.mongo.querier.criterion/NotLike/index/#/PointingToDeclaration/)|  [jvm] <br><br>序号<br><br>override var [index](index.md#tech.whence.echo.support.mongo.querier.criterion/NotLike/index/#/PointingToDeclaration/): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)   <br>
| [name](index.md#tech.whence.echo.support.mongo.querier.criterion/NotLike/name/#/PointingToDeclaration/)|  [jvm] <br><br>String? 字段名<br><br>open override val [name](index.md#tech.whence.echo.support.mongo.querier.criterion/NotLike/name/#/PointingToDeclaration/): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?   <br>
| [template](index.md#tech.whence.echo.support.mongo.querier.criterion/NotLike/template/#/PointingToDeclaration/)|  [jvm] <br><br>String 格式化模板<br><br>override val [template](index.md#tech.whence.echo.support.mongo.querier.criterion/NotLike/template/#/PointingToDeclaration/): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)   <br>
| [value](index.md#tech.whence.echo.support.mongo.querier.criterion/NotLike/value/#/PointingToDeclaration/)|  [jvm] <br><br>T 相关值<br><br>open override val [value](index.md#tech.whence.echo.support.mongo.querier.criterion/NotLike/value/#/PointingToDeclaration/): [Serializable](https://docs.oracle.com/javase/8/docs/api/java/io/Serializable.html)   <br>


## Inheritors  
  
|  Name| 
|---|
| [NotEndWith](../-not-end-with/index.md)
| [NotStartWith](../-not-start-with/index.md)

