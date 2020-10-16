---
title: AbstractCreator -
---
//[echo](../../index.md)/[tech.whence.echo.dal.querier](../index.md)/[AbstractCreator](index.md)



# AbstractCreator  
 [jvm] 

抽象创建器

abstract class [AbstractCreator](index.md)<[T](index.md) : [AbstractCreator](index.md)<[T](index.md), [A](index.md), [D](index.md)>, [A](index.md) : [Assignment](../../tech.whence.echo.dal.querier.component/-assignment/index.md), [D](index.md) : [Definition](../../tech.whence.echo.dal.querier.component/-definition/index.md)<*, *>> : [AbstractQuerier](../../tech.whence.echo.dal.querier.component/-abstract-querier/index.md), [Creator](../-creator/index.md)<[T](index.md), [A](index.md), [D](index.md)>    


## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| A| <br><br>赋值<br><br>
| D| <br><br>定义<br><br>
| T| <br><br>子类<br><br>
  


## Constructors  
  
|  Name|  Summary| 
|---|---|
| [AbstractCreator](-abstract-creator.md)|  [jvm] <br><br>子类<br><br>fun [AbstractCreator](-abstract-creator.md)()   <br>


## Functions  
  
|  Name|  Summary| 
|---|---|
| [define](../../tech.whence.echo.dal.querier.component/-definer/define.md)| [jvm]  <br>Brief description  <br><br><br>生成定义<br><br>  <br>Content  <br>abstract override fun [define](../../tech.whence.echo.dal.querier.component/-definer/define.md)(): [D](index.md)  <br><br><br>
| [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)| [jvm]  <br>Content  <br>open operator override fun [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [into](into.md)| [jvm]  <br>Brief description  <br><br><br>指定创建目的地<br><br>  <br>Content  <br>open override fun [into](into.md)(schema: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): [T](index.md)  <br><br><br>
| [set](../../tech.whence.echo.dal.querier.component/-setter/set.md)| [jvm]  <br>Brief description  <br><br><br>设置赋值作业<br><br>  <br>Content  <br>open override fun [set](../../tech.whence.echo.dal.querier.component/-setter/set.md)(vararg assignments: [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<out [A](index.md)>): [T](index.md)  <br>open override fun [set](set.md)(assignments: [Set](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-set/index.html)<[A](index.md)>): [T](index.md)  <br><br><br>
| [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>


## Properties  
  
|  Name|  Summary| 
|---|---|
| [description](index.md#tech.whence.echo.dal.querier/AbstractCreator/description/#/PointingToDeclaration/)|  [jvm] <br><br>String? 描述<br><br>open override val [description](index.md#tech.whence.echo.dal.querier/AbstractCreator/description/#/PointingToDeclaration/): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?   <br>
| [renamer](index.md#tech.whence.echo.dal.querier/AbstractCreator/renamer/#/PointingToDeclaration/)|  [jvm] override var [renamer](index.md#tech.whence.echo.dal.querier/AbstractCreator/renamer/#/PointingToDeclaration/): [Fixer](../../tech.whence.echo.function/-fixer/index.md)<[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)>   <br>
| [valid](index.md#tech.whence.echo.dal.querier/AbstractCreator/valid/#/PointingToDeclaration/)|  [jvm] <br><br>Boolean 是否有效<br><br>open override val [valid](index.md#tech.whence.echo.dal.querier/AbstractCreator/valid/#/PointingToDeclaration/): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)   <br>


## Inheritors  
  
|  Name| 
|---|
| [AbstractInsert](../../tech.whence.echo.support.jdbc.querier/-abstract-insert/index.md)
| [Insert](../../tech.whence.echo.support.mongo.querier/-insert/index.md)

