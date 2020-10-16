---
title: Definition -
---
//[echo](../../index.md)/[tech.whence.echo.support.mongo.querier.component](../index.md)/[Definition](index.md)



# Definition  
 [jvm] 

定义

class [Definition](index.md)<[O](index.md)> : [AbstractDefinition](../../tech.whence.echo.dal.querier.component/-abstract-definition/index.md)<[Definition](index.md)<[O](index.md)>, JsonObject, JsonObject>    


## Types  
  
|  Name|  Summary| 
|---|---|
| [Companion](-companion/index.md)| [jvm]  <br>Content  <br>object [Companion](-companion/index.md)  <br><br><br>


## Functions  
  
|  Name|  Summary| 
|---|---|
| [assign](index.md#tech.whence.echo.dal.querier.component/AbstractDefinition/assign/#io.vertx.core.json.JsonObject/PointingToDeclaration/)| [jvm]  <br>Brief description  <br><br><br>指定赋值条件<br><br>  <br>Content  <br>override fun [assign](index.md#tech.whence.echo.dal.querier.component/AbstractDefinition/assign/#io.vertx.core.json.JsonObject/PointingToDeclaration/)(assignments: JsonObject): [Definition](index.md)<[O](index.md)>  <br><br><br>[jvm]  <br>Brief description  <br><br><br>将指定字段转换为赋值条件<br><br>  <br>Content  <br>fun [assign](assign.md)(creator: [Producer](../../tech.whence.echo.function/-producer/index.md)<JsonObject>): [Definition](index.md)<[O](index.md)>  <br><br><br>
| [describe](../../tech.whence.echo.dal.querier.component/-abstract-definition/describe.md)| [jvm]  <br>Brief description  <br><br><br>描述<br><br>  <br>Content  <br>override fun [describe](../../tech.whence.echo.dal.querier.component/-abstract-definition/describe.md)(description: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): [Definition](index.md)<[O](index.md)>  <br><br><br>[jvm]  <br>Brief description  <br><br><br>设置描述<br><br>  <br>Content  <br>fun [describe](describe.md)(creator: [Producer](../../tech.whence.echo.function/-producer/index.md)<[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)>): [Definition](index.md)<[O](index.md)>  <br><br><br>
| [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)| [jvm]  <br>Content  <br>open operator override fun [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [opt](opt.md)| [jvm]  <br>Brief description  <br><br><br>设置选项<br><br>  <br>Content  <br>fun [opt](opt.md)(options: [O](index.md)?): [Definition](index.md)<[O](index.md)>  <br><br><br>
| [prepare](prepare.md)| [jvm]  <br>Brief description  <br><br><br>预备<br><br>  <br>Content  <br>fun [prepare](prepare.md)(runner: [Runner](../../tech.whence.echo.function/-runner/index.md)): [Definition](index.md)<[O](index.md)>  <br><br><br>
| [restrict](index.md#tech.whence.echo.dal.querier.component/AbstractDefinition/restrict/#io.vertx.core.json.JsonObject/PointingToDeclaration/)| [jvm]  <br>Brief description  <br><br><br>指定约束条件<br><br>  <br>Content  <br>override fun [restrict](index.md#tech.whence.echo.dal.querier.component/AbstractDefinition/restrict/#io.vertx.core.json.JsonObject/PointingToDeclaration/)(restrictions: JsonObject): [Definition](index.md)<[O](index.md)>  <br>fun [restrict](restrict.md)(creator: [Producer](../../tech.whence.echo.function/-producer/index.md)<JsonObject>): [Definition](index.md)<[O](index.md)>  <br><br><br>
| [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>


## Properties  
  
|  Name|  Summary| 
|---|---|
| [assignments](index.md#tech.whence.echo.support.mongo.querier.component/Definition/assignments/#/PointingToDeclaration/)|  [jvm] <br><br>A? 已指定赋值<br><br>open override var [assignments](index.md#tech.whence.echo.support.mongo.querier.component/Definition/assignments/#/PointingToDeclaration/): JsonObject?   <br>
| [description](index.md#tech.whence.echo.support.mongo.querier.component/Definition/description/#/PointingToDeclaration/)|  [jvm] <br><br>String? 描述<br><br>open override var [description](index.md#tech.whence.echo.support.mongo.querier.component/Definition/description/#/PointingToDeclaration/): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?   <br>
| [options](index.md#tech.whence.echo.support.mongo.querier.component/Definition/options/#/PointingToDeclaration/)|  [jvm] <br><br>选项<br><br>var [options](index.md#tech.whence.echo.support.mongo.querier.component/Definition/options/#/PointingToDeclaration/): [O](index.md)?   <br>
| [restrictions](index.md#tech.whence.echo.support.mongo.querier.component/Definition/restrictions/#/PointingToDeclaration/)|  [jvm] <br><br>R? 已指定约束<br><br>open override var [restrictions](index.md#tech.whence.echo.support.mongo.querier.component/Definition/restrictions/#/PointingToDeclaration/): JsonObject?   <br>
| [schema](index.md#tech.whence.echo.support.mongo.querier.component/Definition/schema/#/PointingToDeclaration/)|  [jvm] <br><br>String 指定命名空间<br><br>override val [schema](index.md#tech.whence.echo.support.mongo.querier.component/Definition/schema/#/PointingToDeclaration/): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)   <br>

