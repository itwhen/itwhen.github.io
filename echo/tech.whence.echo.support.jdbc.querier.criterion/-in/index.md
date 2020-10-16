---
title: In -
---
//[echo](../../index.md)/[tech.whence.echo.support.jdbc.querier.criterion](../index.md)/[In](index.md)



# In  
 [jvm] 

在范围内

class [In](index.md)<[T](index.md) : [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>(**name**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), **value**: [Set](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-set/index.html)<[T](index.md)>) : [Criterion](../../tech.whence.echo.support.jdbc.querier.component/-criterion/index.md)<[Set](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-set/index.html)<[T](index.md)>>    


## Constructors  
  
|  Name|  Summary| 
|---|---|
| [In](-in.md)|  [jvm] <br><br><br><br>fun <[T](index.md) : [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)> [In](-in.md)(name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), value: [Set](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-set/index.html)<[T](index.md)>)   <br>


## Functions  
  
|  Name|  Summary| 
|---|---|
| [describe](describe.md)| [jvm]  <br>Brief description  <br><br><br>描述当前操作字段及其值<br><br>  <br>Content  <br>open override fun [describe](describe.md)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>
| [equals](../../tech.whence.echo.support.jdbc.querier.component/-criterion/equals.md)| [jvm]  <br>Content  <br>open operator override fun [equals](../../tech.whence.echo.support.jdbc.querier.component/-criterion/equals.md)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [hashCode](../../tech.whence.echo.support.jdbc.querier.component/-criterion/hash-code.md)| [jvm]  <br>Content  <br>open override fun [hashCode](../../tech.whence.echo.support.jdbc.querier.component/-criterion/hash-code.md)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [name](../../tech.whence.echo.support.jdbc.querier.component/-criterion/name.md)| [jvm]  <br>Brief description  <br><br><br>取字段名<br><br>  <br>Content  <br>open override fun [name](../../tech.whence.echo.support.jdbc.querier.component/-criterion/name.md)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>
| [prefix](../../tech.whence.echo.support.jdbc.querier.component/-criterion/prefix.md)| [jvm]  <br>Brief description  <br><br><br>生成前缀<br><br>  <br>Content  <br>open override fun [prefix](../../tech.whence.echo.support.jdbc.querier.component/-criterion/prefix.md)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>
| [prepare](../../tech.whence.echo.support.jdbc.querier.component/-criterion/prepare.md)| [jvm]  <br>Brief description  <br><br><br>准备预备查询字符串及其赋值<br><br>  <br>Content  <br>open override fun [prepare](../../tech.whence.echo.support.jdbc.querier.component/-criterion/prepare.md)(): [Criterion.Preparation](../../tech.whence.echo.support.jdbc.querier.component/-criterion/-preparation/index.md)<[Column](../../tech.whence.echo.support.jdbc.querier.component/-column/index.md)>  <br><br><br>[jvm]  <br>Brief description  <br><br><br>准备当前位置下的预备查询字符串及其赋值<br><br>  <br>Content  <br>open override fun [prepare](../../tech.whence.echo.support.jdbc.querier.component/-criterion/prepare.md)(position: [Criterion.Position](../../tech.whence.echo.support.jdbc.querier.component/-criterion/-position/index.md)): [Criterion.Preparation](../../tech.whence.echo.support.jdbc.querier.component/-criterion/-preparation/index.md)<[Column](../../tech.whence.echo.support.jdbc.querier.component/-column/index.md)>  <br><br><br>
| [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>


## Properties  
  
|  Name|  Summary| 
|---|---|
| [index](index.md#tech.whence.echo.support.jdbc.querier.criterion/In/index/#/PointingToDeclaration/)|  [jvm] <br><br>序号<br><br>override var [index](index.md#tech.whence.echo.support.jdbc.querier.criterion/In/index/#/PointingToDeclaration/): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)   <br>
| [name](index.md#tech.whence.echo.support.jdbc.querier.criterion/In/name/#/PointingToDeclaration/)|  [jvm] <br><br>String? 字段名<br><br>open override val [name](index.md#tech.whence.echo.support.jdbc.querier.criterion/In/name/#/PointingToDeclaration/): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?   <br>
| [template](index.md#tech.whence.echo.support.jdbc.querier.criterion/In/template/#/PointingToDeclaration/)|  [jvm] <br><br>String 格式化模板<br><br>override val [template](index.md#tech.whence.echo.support.jdbc.querier.criterion/In/template/#/PointingToDeclaration/): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)   <br>
| [value](index.md#tech.whence.echo.support.jdbc.querier.criterion/In/value/#/PointingToDeclaration/)|  [jvm] <br><br>T 相关值<br><br>open override val [value](index.md#tech.whence.echo.support.jdbc.querier.criterion/In/value/#/PointingToDeclaration/): [Set](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-set/index.html)<[T](index.md)>   <br>

