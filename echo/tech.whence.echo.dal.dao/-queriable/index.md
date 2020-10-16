---
title: Queriable -
---
//[echo](../../index.md)/[tech.whence.echo.dal.dao](../index.md)/[Queriable](index.md)



# Queriable  
 [jvm] 

可查询

interface [Queriable](index.md)<[E](index.md) : [Entity](../../tech.whence.echo.dal.entity/-entity/index.md), [R](index.md), [QC](index.md) : [Creator](../../tech.whence.echo.dal.querier/-creator/index.md)<[QC](index.md), [QA](index.md), *>, [QU](index.md) : [Updater](../../tech.whence.echo.dal.querier/-updater/index.md)<[QU](index.md), [QF](index.md), [QA](index.md), *, *>, [QR](index.md) : [Retriever](../../tech.whence.echo.dal.querier/-retriever/index.md)<[QR](index.md), [QF](index.md), [QA](index.md), *, *>, [QD](index.md) : [Deleter](../../tech.whence.echo.dal.querier/-deleter/index.md)<[QD](index.md), [QF](index.md), [QA](index.md), *, *>, [QF](index.md) : [Restrictor](../../tech.whence.echo.dal.querier.component/-restrictor/index.md)<[QF](index.md), [QF](index.md), [QA](index.md), *>, [QA](index.md) : [Assignment](../../tech.whence.echo.dal.querier.component/-assignment/index.md), [QO](index.md) : [Criterion](../../tech.whence.echo.dal.querier.component/-criterion/index.md)<*, [QA](index.md), *>, [QI](index.md) : [Definer](../../tech.whence.echo.dal.querier.component/-definer/index.md)<*, *>>   


## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| E| <br><br>实体类型<br><br>
| QA| <br><br>赋值<br><br>
| QC| <br><br>创建器<br><br>
| QD| <br><br>删除器<br><br>
| QF| <br><br>约束<br><br>
| QO| <br><br>条件<br><br>
| QR| <br><br>查询器<br><br>
| QU| <br><br>更新器<br><br>
| R| <br><br>行记录类型<br><br>
  


## Functions  
  
|  Name|  Summary| 
|---|---|
| [count](count.md)| [jvm]  <br>Brief description  <br><br><br>统计<br><br>  <br>Content  <br>abstract suspend fun [count](count.md)(retriever: [QR](index.md)): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [create](create.md)| [jvm]  <br>Brief description  <br><br><br>写入<br><br>  <br>Content  <br>abstract suspend fun [create](create.md)(creator: [QC](index.md)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [delete](delete.md)| [jvm]  <br>Brief description  <br><br><br>删除<br><br>  <br>Content  <br>abstract suspend fun [delete](delete.md)(deleter: [QD](index.md)): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)| [jvm]  <br>Content  <br>open operator override fun [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [find](find.md)| [jvm]  <br>Brief description  <br><br><br>查找<br><br>  <br>Content  <br>abstract suspend fun [find](find.md)(retriever: [QR](index.md)): [Entities](../../tech.whence.echo.dal.entity/-entities/index.md)<[E](index.md)>  <br><br><br>[jvm]  <br>Brief description  <br><br><br>查找 若有数据则每次返回capably大小的列表供消费 回调返回真假来控制是否继续<br><br>  <br>Content  <br>abstract suspend fun [find](find.md)(retriever: [QR](index.md), limit: [UInt](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-u-int/index.html), capably: [UInt](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-u-int/index.html), predicate: [Predicate](../../tech.whence.echo.function/-predicate/index.md)<[Entities](../../tech.whence.echo.dal.entity/-entities/index.md)<[E](index.md)>>)  <br><br><br>
| [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [paginate](paginate.md)| [jvm]  <br>Brief description  <br><br><br>分页查找<br><br>  <br>Content  <br>abstract suspend fun [paginate](paginate.md)(retriever: [QR](index.md)): [Paginator](../../tech.whence.echo.container/-paginator/index.md)<[E](index.md)>  <br>abstract suspend fun [paginate](paginate.md)(criteria: [Criteria](../../tech.whence.echo.dal.filter/-criteria/index.md)): [Paginator](../../tech.whence.echo.container/-paginator/index.md)<[E](index.md)>  <br><br><br>
| [query](query.md)| [jvm]  <br>Brief description  <br><br><br>通用查询<br><br>  <br>Content  <br>abstract suspend fun [query](query.md)(operation: [Operation](../-operation/index.md), definer: [QI](index.md)): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[Accessor](../../tech.whence.echo.container.accessor/-accessor/index.md)>?  <br><br><br>
| [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>
| [update](update.md)| [jvm]  <br>Brief description  <br><br><br>更新<br><br>  <br>Content  <br>abstract suspend fun [update](update.md)(updater: [QU](index.md)): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>[jvm]  <br>Brief description  <br><br><br>按条件更新<br><br>  <br>Content  <br>abstract suspend fun [update](update.md)(restriction: [QF](index.md), data: [Map](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)<[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), [Serializable](https://docs.oracle.com/javase/8/docs/api/java/io/Serializable.html)>): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>


## Properties  
  
|  Name|  Summary| 
|---|---|
| [creator](index.md#tech.whence.echo.dal.dao/Queriable/creator/#/PointingToDeclaration/)|  [jvm] <br><br>QC 创建器<br><br>abstract val [creator](index.md#tech.whence.echo.dal.dao/Queriable/creator/#/PointingToDeclaration/): [QC](index.md)   <br>
| [deleter](index.md#tech.whence.echo.dal.dao/Queriable/deleter/#/PointingToDeclaration/)|  [jvm] <br><br>QD 删除器<br><br>abstract val [deleter](index.md#tech.whence.echo.dal.dao/Queriable/deleter/#/PointingToDeclaration/): [QD](index.md)   <br>
| [restrictor](index.md#tech.whence.echo.dal.dao/Queriable/restrictor/#/PointingToDeclaration/)|  [jvm] <br><br>QF 约束器<br><br>abstract val [restrictor](index.md#tech.whence.echo.dal.dao/Queriable/restrictor/#/PointingToDeclaration/): [QF](index.md)   <br>
| [retriever](index.md#tech.whence.echo.dal.dao/Queriable/retriever/#/PointingToDeclaration/)|  [jvm] <br><br>QR 查询器<br><br>abstract val [retriever](index.md#tech.whence.echo.dal.dao/Queriable/retriever/#/PointingToDeclaration/): [QR](index.md)   <br>
| [updater](index.md#tech.whence.echo.dal.dao/Queriable/updater/#/PointingToDeclaration/)|  [jvm] <br><br>QU 更新器<br><br>abstract val [updater](index.md#tech.whence.echo.dal.dao/Queriable/updater/#/PointingToDeclaration/): [QU](index.md)   <br>


## Inheritors  
  
|  Name| 
|---|
| [AbstractDao](../-abstract-dao/index.md)

