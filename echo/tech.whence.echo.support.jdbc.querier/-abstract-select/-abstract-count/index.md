---
title: AbstractCount -
---
//[echo](../../../index.md)/[tech.whence.echo.support.jdbc.querier](../../index.md)/[AbstractSelect](../index.md)/[AbstractCount](index.md)



# AbstractCount  
 [jvm] 

Count

abstract class [AbstractCount](index.md)<[T](index.md) : [AbstractSelect.AbstractCount](index.md)<[T](index.md), [S](index.md)>, [S](index.md) : [AbstractSelect](../index.md)<[S](index.md), [T](index.md)>>(**select**: [S](index.md), **counting**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)) : [Definer](../../../tech.whence.echo.support.jdbc.querier.component/-definer/index.md)<[T](index.md)>    


## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| S| <br><br><br><br>
| T| <br><br><br><br>
  


## Constructors  
  
|  Name|  Summary| 
|---|---|
| [AbstractCount](-abstract-count.md)|  [jvm] <br><br><br><br>fun <[S](index.md) : [AbstractSelect](../index.md)<[S](index.md), [T](index.md)>> [AbstractCount](-abstract-count.md)(select: [S](index.md), counting: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html))   <br>


## Functions  
  
|  Name|  Summary| 
|---|---|
| [define](define.md)| [jvm]  <br>Brief description  <br><br><br>生成定义<br><br>  <br>Content  <br>open override fun [define](define.md)(): [Definition](../../../tech.whence.echo.support.jdbc.querier.component/-definition/index.md)  <br><br><br>
| [equals](../../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)| [jvm]  <br>Content  <br>open operator override fun [equals](../../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [hashCode](../../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [hashCode](../../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [merge](index.md#tech.whence.echo.support.jdbc.querier.component/Definer/merge/#kotlin.collections.List[TypeParam(bounds=[tech.whence.echo.support.jdbc.querier.AbstractSelect.AbstractCount[^,TypeParam(bounds=[tech.whence.echo.support.jdbc.querier.AbstractSelect[^^,^]])]])]/PointingToDeclaration/)| [jvm]  <br>Brief description  <br><br><br>合并<br><br>  <br>Content  <br>open override fun [merge](index.md#tech.whence.echo.support.jdbc.querier.component/Definer/merge/#kotlin.collections.List[TypeParam(bounds=[tech.whence.echo.support.jdbc.querier.AbstractSelect.AbstractCount[^,TypeParam(bounds=[tech.whence.echo.support.jdbc.querier.AbstractSelect[^^,^]])]])]/PointingToDeclaration/)(definers: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[T](index.md)>): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[T](index.md)>  <br><br><br>
| [toString](to-string.md)| [jvm]  <br>Content  <br>open override fun [toString](to-string.md)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>


## Properties  
  
|  Name|  Summary| 
|---|---|
| [description](index.md#tech.whence.echo.support.jdbc.querier/AbstractSelect.AbstractCount/description/#/PointingToDeclaration/)|  [jvm] <br><br>String? 描述<br><br>open override val [description](index.md#tech.whence.echo.support.jdbc.querier/AbstractSelect.AbstractCount/description/#/PointingToDeclaration/): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?   <br>
| [renamer](index.md#tech.whence.echo.support.jdbc.querier/AbstractSelect.AbstractCount/renamer/#/PointingToDeclaration/)|  [jvm] <br><br>Fixer<String> 字段重命名<br><br>open override var [renamer](index.md#tech.whence.echo.support.jdbc.querier/AbstractSelect.AbstractCount/renamer/#/PointingToDeclaration/): [Fixer](../../../tech.whence.echo.function/-fixer/index.md)<[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)>   <br>
| [valid](index.md#tech.whence.echo.support.jdbc.querier/AbstractSelect.AbstractCount/valid/#/PointingToDeclaration/)|  [jvm] <br><br>Boolean 是否有效<br><br>open override val [valid](index.md#tech.whence.echo.support.jdbc.querier/AbstractSelect.AbstractCount/valid/#/PointingToDeclaration/): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)   <br>


## Inheritors  
  
|  Name| 
|---|
| [Select](../../../tech.whence.echo.support.jdbc.driver.general.querier/-select/-count/index.md)
| [Select](../../../tech.whence.echo.support.jdbc.driver.mysql.querier/-select/-count/index.md)

