---
title: AbstractDefinition -
---
//[echo](../../index.md)/[tech.whence.echo.dal.querier.component](../index.md)/[AbstractDefinition](index.md)



# AbstractDefinition  
 [jvm] 

抽象定义器

abstract class [AbstractDefinition](index.md)<[T](index.md) : [AbstractDefinition](index.md)<[T](index.md), [R](index.md), [A](index.md)>, [R](index.md), [A](index.md)>(**schema**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)) : [Definition](../-definition/index.md)<[R](index.md), [A](index.md)>    


## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| A| <br><br>赋值<br><br>
| R| <br><br>约束<br><br>
| T| <br><br>子类<br><br>
  


## Constructors  
  
|  Name|  Summary| 
|---|---|
| [AbstractDefinition](-abstract-definition.md)|  [jvm] <br><br><br><br>fun [AbstractDefinition](-abstract-definition.md)(schema: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html))   <br>


## Functions  
  
|  Name|  Summary| 
|---|---|
| [assign](assign.md)| [jvm]  <br>Brief description  <br><br><br>指定赋值条件<br><br>  <br>Content  <br>fun [assign](assign.md)(assignments: [A](index.md)): [T](index.md)  <br><br><br>
| [describe](describe.md)| [jvm]  <br>Brief description  <br><br><br>描述<br><br>  <br>Content  <br>fun [describe](describe.md)(description: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): [T](index.md)  <br><br><br>
| [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)| [jvm]  <br>Content  <br>open operator override fun [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [restrict](restrict.md)| [jvm]  <br>Brief description  <br><br><br>指定约束条件<br><br>  <br>Content  <br>fun [restrict](restrict.md)(restrictions: [R](index.md)): [T](index.md)  <br><br><br>
| [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>


## Properties  
  
|  Name|  Summary| 
|---|---|
| [assignments](index.md#tech.whence.echo.dal.querier.component/AbstractDefinition/assignments/#/PointingToDeclaration/)|  [jvm] <br><br>A? 已指定赋值<br><br>open override var [assignments](index.md#tech.whence.echo.dal.querier.component/AbstractDefinition/assignments/#/PointingToDeclaration/): [A](index.md)?   <br>
| [description](index.md#tech.whence.echo.dal.querier.component/AbstractDefinition/description/#/PointingToDeclaration/)|  [jvm] <br><br>String? 描述<br><br>open override var [description](index.md#tech.whence.echo.dal.querier.component/AbstractDefinition/description/#/PointingToDeclaration/): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?   <br>
| [restrictions](index.md#tech.whence.echo.dal.querier.component/AbstractDefinition/restrictions/#/PointingToDeclaration/)|  [jvm] <br><br>R? 已指定约束<br><br>open override var [restrictions](index.md#tech.whence.echo.dal.querier.component/AbstractDefinition/restrictions/#/PointingToDeclaration/): [R](index.md)?   <br>
| [schema](index.md#tech.whence.echo.dal.querier.component/AbstractDefinition/schema/#/PointingToDeclaration/)|  [jvm] <br><br>String 指定命名空间<br><br>val [schema](index.md#tech.whence.echo.dal.querier.component/AbstractDefinition/schema/#/PointingToDeclaration/): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)   <br>


## Inheritors  
  
|  Name| 
|---|
| [Definition](../../tech.whence.echo.support.jdbc.querier.component/-definition/index.md)
| [Definition](../../tech.whence.echo.support.mongo.querier.component/-definition/index.md)

