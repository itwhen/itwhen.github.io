---
title: Definer -
---
//[echo](../../index.md)/[tech.whence.echo.support.jdbc.querier.component](../index.md)/[Definer](index.md)



# Definer  
 [jvm] 

定义器

interface [Definer](index.md)<[T](index.md) : [Definer](index.md)<[T](index.md)>> : [Definer](../../tech.whence.echo.dal.querier.component/-definer/index.md)<[T](index.md), [Definition](../-definition/index.md)>    


## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| T| <br><br><br><br>
  


## Functions  
  
|  Name|  Summary| 
|---|---|
| [define](../../tech.whence.echo.dal.querier.component/-definer/define.md)| [jvm]  <br>Brief description  <br><br><br>生成定义<br><br>  <br>Content  <br>abstract override fun [define](../../tech.whence.echo.dal.querier.component/-definer/define.md)(): [Definition](../-definition/index.md)  <br><br><br>
| [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)| [jvm]  <br>Content  <br>open operator override fun [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [merge](merge.md)| [jvm]  <br>Brief description  <br><br><br>合并<br><br>  <br>Content  <br>open fun [merge](merge.md)(definers: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[T](index.md)>): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[T](index.md)>  <br><br><br>
| [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>


## Properties  
  
|  Name|  Summary| 
|---|---|
| [description](index.md#tech.whence.echo.support.jdbc.querier.component/Definer/description/#/PointingToDeclaration/)|  [jvm] <br><br>String? 描述<br><br>open override val [description](index.md#tech.whence.echo.support.jdbc.querier.component/Definer/description/#/PointingToDeclaration/): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?   <br>
| [renamer](index.md#tech.whence.echo.support.jdbc.querier.component/Definer/renamer/#/PointingToDeclaration/)|  [jvm] <br><br>Fixer<String> 字段重命名<br><br>abstract override var [renamer](index.md#tech.whence.echo.support.jdbc.querier.component/Definer/renamer/#/PointingToDeclaration/): [Fixer](../../tech.whence.echo.function/-fixer/index.md)<[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)>   <br>
| [valid](index.md#tech.whence.echo.support.jdbc.querier.component/Definer/valid/#/PointingToDeclaration/)|  [jvm] <br><br>Boolean 是否有效<br><br>abstract override val [valid](index.md#tech.whence.echo.support.jdbc.querier.component/Definer/valid/#/PointingToDeclaration/): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)   <br>


## Inheritors  
  
|  Name| 
|---|
| [AbstractDelete](../../tech.whence.echo.support.jdbc.querier/-abstract-delete/index.md)
| [AbstractInsert](../../tech.whence.echo.support.jdbc.querier/-abstract-insert/index.md)
| [AbstractSelect](../../tech.whence.echo.support.jdbc.querier/-abstract-select/index.md)
| [AbstractSelect](../../tech.whence.echo.support.jdbc.querier/-abstract-select/-abstract-count/index.md)
| [AbstractUpdate](../../tech.whence.echo.support.jdbc.querier/-abstract-update/index.md)

