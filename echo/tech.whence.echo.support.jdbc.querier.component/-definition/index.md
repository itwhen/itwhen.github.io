---
title: Definition -
---
//[echo](../../index.md)/[tech.whence.echo.support.jdbc.querier.component](../index.md)/[Definition](index.md)



# Definition  
 [jvm] 

定义

class [Definition](index.md) : [AbstractDefinition](../../tech.whence.echo.dal.querier.component/-abstract-definition/index.md)<[Definition](index.md), [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[Accessor](../../tech.whence.echo.container.accessor/-accessor/index.md)>>    


## Types  
  
|  Name|  Summary| 
|---|---|
| [Companion](-companion/index.md)| [jvm]  <br>Content  <br>object [Companion](-companion/index.md)  <br><br><br>


## Functions  
  
|  Name|  Summary| 
|---|---|
| [assign](index.md#tech.whence.echo.dal.querier.component/AbstractDefinition/assign/#kotlin.collections.List[tech.whence.echo.container.accessor.Accessor]/PointingToDeclaration/)| [jvm]  <br>Brief description  <br><br><br>指定赋值条件<br><br>  <br>Content  <br>override fun [assign](index.md#tech.whence.echo.dal.querier.component/AbstractDefinition/assign/#kotlin.collections.List[tech.whence.echo.container.accessor.Accessor]/PointingToDeclaration/)(assignments: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[Accessor](../../tech.whence.echo.container.accessor/-accessor/index.md)>): [Definition](index.md)  <br><br><br>[jvm]  <br>Brief description  <br><br><br>将指定字段转换为赋值条件<br><br>  <br>Content  <br>fun [assign](assign.md)(columns: [LinkedHashSet](https://docs.oracle.com/javase/8/docs/api/java/util/LinkedHashSet.html)<[Column](../-column/index.md)>): [Definition](index.md)  <br>fun [assign](assign.md)(columns: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[LinkedHashSet](https://docs.oracle.com/javase/8/docs/api/java/util/LinkedHashSet.html)<[Column](../-column/index.md)>>): [Definition](index.md)  <br>fun [assign](assign.md)(creator: [Producer](../../tech.whence.echo.function/-producer/index.md)<[List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[LinkedHashSet](https://docs.oracle.com/javase/8/docs/api/java/util/LinkedHashSet.html)<[Column](../-column/index.md)>>>): [Definition](index.md)  <br><br><br>
| [describe](../../tech.whence.echo.dal.querier.component/-abstract-definition/describe.md)| [jvm]  <br>Brief description  <br><br><br>描述<br><br>  <br>Content  <br>override fun [describe](../../tech.whence.echo.dal.querier.component/-abstract-definition/describe.md)(description: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): [Definition](index.md)  <br><br><br>
| [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)| [jvm]  <br>Content  <br>open operator override fun [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [parameterize](parameterize.md)| [jvm]  <br>Brief description  <br><br><br>绑定参数转换 将命名参数转换为占位符参数<br><br>  <br>Content  <br>fun [parameterize](parameterize.md)(): [Pair](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-pair/index.html)<[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?>>?  <br><br><br>
| [prepare](prepare.md)| [jvm]  <br>Brief description  <br><br><br>预备<br><br>  <br>Content  <br>fun [prepare](prepare.md)(runner: [Runner](../../tech.whence.echo.function/-runner/index.md)): [Definition](index.md)  <br><br><br>
| [restrict](index.md#tech.whence.echo.dal.querier.component/AbstractDefinition/restrict/#kotlin.String/PointingToDeclaration/)| [jvm]  <br>Brief description  <br><br><br>指定约束条件<br><br>  <br>Content  <br>override fun [restrict](index.md#tech.whence.echo.dal.querier.component/AbstractDefinition/restrict/#kotlin.String/PointingToDeclaration/)(restrictions: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): [Definition](index.md)  <br>fun [restrict](restrict.md)(transformer: [Transformer](../../tech.whence.echo.function/-transformer/index.md)<[Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)>): [Definition](index.md)  <br><br><br>
| [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>


## Properties  
  
|  Name|  Summary| 
|---|---|
| [assignments](index.md#tech.whence.echo.support.jdbc.querier.component/Definition/assignments/#/PointingToDeclaration/)|  [jvm] <br><br>A? 已指定赋值<br><br>open override var [assignments](index.md#tech.whence.echo.support.jdbc.querier.component/Definition/assignments/#/PointingToDeclaration/): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[Accessor](../../tech.whence.echo.container.accessor/-accessor/index.md)>?   <br>
| [description](index.md#tech.whence.echo.support.jdbc.querier.component/Definition/description/#/PointingToDeclaration/)|  [jvm] <br><br>String? 描述<br><br>open override var [description](index.md#tech.whence.echo.support.jdbc.querier.component/Definition/description/#/PointingToDeclaration/): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?   <br>
| [restrictions](index.md#tech.whence.echo.support.jdbc.querier.component/Definition/restrictions/#/PointingToDeclaration/)|  [jvm] <br><br>R? 已指定约束<br><br>open override var [restrictions](index.md#tech.whence.echo.support.jdbc.querier.component/Definition/restrictions/#/PointingToDeclaration/): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?   <br>
| [schema](index.md#tech.whence.echo.support.jdbc.querier.component/Definition/schema/#/PointingToDeclaration/)|  [jvm] <br><br>String 指定命名空间<br><br>override val [schema](index.md#tech.whence.echo.support.jdbc.querier.component/Definition/schema/#/PointingToDeclaration/): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)   <br>

