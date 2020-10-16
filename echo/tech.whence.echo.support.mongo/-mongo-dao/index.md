---
title: MongoDao -
---
//[echo](../../index.md)/[tech.whence.echo.support.mongo](../index.md)/[MongoDao](index.md)



# MongoDao  
 [jvm] 

MySQL DAO

abstract class [MongoDao](index.md)<[E](index.md) : [Entity](../../tech.whence.echo.dal.entity/-entity/index.md), [PK](index.md) : [Serializable](https://docs.oracle.com/javase/8/docs/api/java/io/Serializable.html)> : [AbstractDao](../../tech.whence.echo.dal.dao/-abstract-dao/index.md)<[E](index.md), [PK](index.md), [MongoClient](../-mongo-client/index.md), MySQLConnection, [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<JsonObject>, JsonObject, [MongoEntityAssembler](../-mongo-entity-assembler/index.md), [Insert](../../tech.whence.echo.support.mongo.querier/-insert/index.md), [Update](../../tech.whence.echo.support.mongo.querier/-update/index.md), [Select](../../tech.whence.echo.support.mongo.querier/-select/index.md), [Delete](../../tech.whence.echo.support.mongo.querier/-delete/index.md), [Where](../../tech.whence.echo.support.mongo.querier.component/-where/index.md), [Column](../../tech.whence.echo.support.mongo.querier.component/-column/index.md), [Criterion](../../tech.whence.echo.support.mongo.querier.component/-criterion/index.md)<*>, [Definer](../../tech.whence.echo.support.mongo.querier.component/-definer/index.md)<*, *>>    


## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| E| <br><br>: Entity 实体类型<br><br>
  


## Constructors  
  
|  Name|  Summary| 
|---|---|
| [MongoDao](-mongo-dao.md)|  [jvm] fun [MongoDao](-mongo-dao.md)()   <br>
| [MongoDao](-mongo-dao.md)|  [jvm] fun <[E](index.md) : [Entity](../../tech.whence.echo.dal.entity/-entity/index.md)> [MongoDao](-mongo-dao.md)(builder: [Builder](../../tech.whence.echo.dal.schema/-builder/index.md)<[E](index.md)>)   <br>
| [MongoDao](-mongo-dao.md)|  [jvm] fun <[E](index.md) : [Entity](../../tech.whence.echo.dal.entity/-entity/index.md), [PK](index.md) : [Serializable](https://docs.oracle.com/javase/8/docs/api/java/io/Serializable.html)> [MongoDao](-mongo-dao.md)(consumer: [MongoDao](index.md)<[E](index.md), [PK](index.md)>.() -> [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html))   <br>


## Types  
  
|  Name|  Summary| 
|---|---|
| [Companion](-companion/index.md)| [jvm]  <br>Content  <br>object [Companion](-companion/index.md)  <br><br><br>


## Functions  
  
|  Name|  Summary| 
|---|---|
| [count](../../tech.whence.echo.dal.dao/-abstract-dao/count.md)| [jvm]  <br>Brief description  <br><br><br>统计<br><br>  <br>Content  <br>open suspend override fun [count](../../tech.whence.echo.dal.dao/-abstract-dao/count.md)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br>open suspend override fun [count](count.md)(retriever: [Select](../../tech.whence.echo.support.mongo.querier/-select/index.md)): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [create](../../tech.whence.echo.dal.dao/-abstract-dao/create.md)| [jvm]  <br>Brief description  <br><br><br>写入数据<br><br>  <br>Content  <br>open suspend override fun [create](../../tech.whence.echo.dal.dao/-abstract-dao/create.md)(data: [Accessor](../../tech.whence.echo.container.accessor/-accessor/index.md)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>[jvm]  <br>Brief description  <br><br><br>写入<br><br>  <br>Content  <br>open suspend override fun [create](create.md)(entity: [E](index.md)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br>open suspend override fun [create](create.md)(creator: [Insert](../../tech.whence.echo.support.mongo.querier/-insert/index.md)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>[jvm]  <br>Brief description  <br><br><br>写入多个<br><br>  <br>Content  <br>open suspend override fun [create](create.md)(entities: [Collection](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-collection/index.html)<[E](index.md)>): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [delete](../../tech.whence.echo.dal.dao/-abstract-dao/delete.md)| [jvm]  <br>Brief description  <br><br><br>删除<br><br>  <br>Content  <br>open suspend override fun [delete](../../tech.whence.echo.dal.dao/-abstract-dao/delete.md)(id: [PK](index.md)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br>open suspend override fun [delete](../../tech.whence.echo.dal.dao/-abstract-dao/delete.md)(batch: [Collection](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-collection/index.html)<[PK](index.md)>): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br>open suspend override fun [delete](delete.md)(deleter: [Delete](../../tech.whence.echo.support.mongo.querier/-delete/index.md)): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>[jvm]  <br>Brief description  <br><br><br>删除指定实体<br><br>  <br>Content  <br>open suspend override fun [delete](../../tech.whence.echo.dal.dao/-abstract-dao/delete.md)(entity: [E](index.md)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>[jvm]  <br>Brief description  <br><br><br>按字段删除<br><br>  <br>Content  <br>open suspend override fun [delete](../../tech.whence.echo.dal.dao/-abstract-dao/delete.md)(column: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), values: [Collection](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-collection/index.html)<[Serializable](https://docs.oracle.com/javase/8/docs/api/java/io/Serializable.html)>): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br>open suspend override fun [delete](../../tech.whence.echo.dal.dao/-writeable/delete.md)(column: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), value: [Serializable](https://docs.oracle.com/javase/8/docs/api/java/io/Serializable.html)): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [dirty](../../tech.whence.echo.dal.dao/-abstract-dao/dirty.md)| [jvm]  <br>Brief description  <br><br><br>检查实体是否变化<br><br>  <br>Content  <br>open override fun [dirty](../../tech.whence.echo.dal.dao/-abstract-dao/dirty.md)(entity: [E](index.md))  <br><br><br>
| [disconnect](../../tech.whence.echo.dal.dao/-abstract-dao/disconnect.md)| [jvm]  <br>Brief description  <br><br><br>释放数据库连接<br><br>  <br>Content  <br>open suspend override fun [disconnect](../../tech.whence.echo.dal.dao/-abstract-dao/disconnect.md)()  <br><br><br>
| [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)| [jvm]  <br>Content  <br>open operator override fun [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [filter](../../tech.whence.echo.dal.dao/-abstract-dao/filter.md)| [jvm]  <br>Brief description  <br><br><br>过滤字段 效率考虑指定字段必须有身份 [tech.whence.echo.dal.schema.key.Identity](../../tech.whence.echo.dal.schema.key/-identity/index.md)<br><br>  <br>Content  <br>open suspend override fun [filter](../../tech.whence.echo.dal.dao/-abstract-dao/filter.md)(column: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), values: [Collection](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-collection/index.html)<[Serializable](https://docs.oracle.com/javase/8/docs/api/java/io/Serializable.html)>, limit: [UInt](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-u-int/index.html), page: [UInt](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-u-int/index.html)): [Paginator](../../tech.whence.echo.container/-paginator/index.md)<[E](index.md)>  <br><br><br>[jvm]  <br>Brief description  <br><br><br>过滤字段<br><br>  <br>Content  <br>open suspend override fun [filter](../../tech.whence.echo.dal.dao/-readable/filter.md)(column: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), value: [Serializable](https://docs.oracle.com/javase/8/docs/api/java/io/Serializable.html), limit: [UInt](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-u-int/index.html), page: [UInt](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-u-int/index.html)): [Paginator](../../tech.whence.echo.container/-paginator/index.md)<[E](index.md)>  <br><br><br>
| [find](../../tech.whence.echo.dal.dao/-abstract-dao/find.md)| [jvm]  <br>Brief description  <br><br><br>查找<br><br>  <br>Content  <br>open suspend override fun [find](../../tech.whence.echo.dal.dao/-abstract-dao/find.md)(): [Entities](../../tech.whence.echo.dal.entity/-entities/index.md)<[E](index.md)>  <br>open suspend override fun [find](find.md)(retriever: [Select](../../tech.whence.echo.support.mongo.querier/-select/index.md)): [Entities](../../tech.whence.echo.dal.entity/-entities/index.md)<[E](index.md)>  <br><br><br>[jvm]  <br>Brief description  <br><br><br>查找 若有数据则每次返回capably大小的列表供消费 回调返回真假来控制是否继续<br><br>  <br>Content  <br>open suspend override fun [find](find.md)(retriever: [Select](../../tech.whence.echo.support.mongo.querier/-select/index.md), limit: [UInt](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-u-int/index.html), capably: [UInt](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-u-int/index.html), predicate: [Predicate](../../tech.whence.echo.function/-predicate/index.md)<[Entities](../../tech.whence.echo.dal.entity/-entities/index.md)<[E](index.md)>>)  <br><br><br>
| [has](../../tech.whence.echo.dal.dao/-abstract-dao/has.md)| [jvm]  <br>Brief description  <br><br><br>判断是否存在<br><br>  <br>Content  <br>open suspend override fun [has](../../tech.whence.echo.dal.dao/-abstract-dao/has.md)(id: [PK](index.md)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>[jvm]  <br>Brief description  <br><br><br>判断实体是否存在<br><br>  <br>Content  <br>open suspend override fun [has](../../tech.whence.echo.dal.dao/-abstract-dao/has.md)(entity: [E](index.md)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [paginate](../../tech.whence.echo.dal.dao/-abstract-dao/paginate.md)| [jvm]  <br>Brief description  <br><br><br>分页查找<br><br>  <br>Content  <br>open suspend override fun [paginate](../../tech.whence.echo.dal.dao/-abstract-dao/paginate.md)(criteria: [Criteria](../../tech.whence.echo.dal.filter/-criteria/index.md)): [Paginator](../../tech.whence.echo.container/-paginator/index.md)<[E](index.md)>  <br>open suspend override fun [paginate](index.md#tech.whence.echo.dal.dao/AbstractDao/paginate/#tech.whence.echo.support.mongo.querier.Select/PointingToDeclaration/)(retriever: [Select](../../tech.whence.echo.support.mongo.querier/-select/index.md)): [Paginator](../../tech.whence.echo.container/-paginator/index.md)<[E](index.md)>  <br><br><br>
| [preconnect](preconnect.md)| [jvm]  <br>Brief description  <br><br><br>设置数据库连接<br><br>  <br>Content  <br>open override fun [preconnect](preconnect.md)(vertx: Vertx, connection: [ConnectionString](../../tech.whence.echo.dal.connection/-connection-string/index.md))  <br><br><br>
| [query](query.md)| [jvm]  <br>Brief description  <br><br><br>通用查询<br><br>  <br>Content  <br>open suspend override fun [query](query.md)(operation: [Operation](../../tech.whence.echo.dal.dao/-operation/index.md), definer: [Definer](../../tech.whence.echo.support.mongo.querier.component/-definer/index.md)<*, *>): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[Accessor](../../tech.whence.echo.container.accessor/-accessor/index.md)>?  <br><br><br>
| [ready](index.md#tech.whence.echo.dal.dao/AbstractDao/ready/#kotlin.coroutines.SuspendFunction1[tech.whence.echo.support.mongo.MongoClient,TypeParam(bounds=[kotlin.Any?])]/PointingToDeclaration/)| [jvm]  <br>Brief description  <br><br><br>使用数据库连接执行回调<br><br>  <br>Content  <br>open suspend override fun <R> [ready](index.md#tech.whence.echo.dal.dao/AbstractDao/ready/#kotlin.coroutines.SuspendFunction1[tech.whence.echo.support.mongo.MongoClient,TypeParam(bounds=[kotlin.Any?])]/PointingToDeclaration/)(block: [SuspendFunction1](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.coroutines/-suspend-function1/index.html)<[MongoClient](../-mongo-client/index.md), R>): R  <br><br><br>
| [redefine](redefine.md)| [jvm]  <br>Brief description  <br><br><br>重新从数据源加载表结构<br><br>  <br>Content  <br>open suspend override fun [redefine](redefine.md)(force: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html))  <br><br><br>
| [retrieve](../../tech.whence.echo.dal.dao/-abstract-dao/retrieve.md)| [jvm]  <br>Brief description  <br><br><br>查找<br><br>  <br>Content  <br>open suspend override fun [retrieve](../../tech.whence.echo.dal.dao/-abstract-dao/retrieve.md)(id: [PK](index.md)): [E](index.md)?  <br><br><br>[jvm]  <br>Brief description  <br><br><br>查找多个<br><br>  <br>Content  <br>open suspend override fun [retrieve](../../tech.whence.echo.dal.dao/-abstract-dao/retrieve.md)(batch: [Collection](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-collection/index.html)<[PK](index.md)>): [Entities](../../tech.whence.echo.dal.entity/-entities/index.md)<[E](index.md)>  <br>open suspend override fun [retrieve](../../tech.whence.echo.dal.dao/-readable/retrieve.md)(vararg batch: [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<out [PK](index.md)>): [Entities](../../tech.whence.echo.dal.entity/-entities/index.md)<[E](index.md)>  <br><br><br>
| [singularize](../../tech.whence.echo.dal.dao/-abstract-dao/singularize.md)| [jvm]  <br>Brief description  <br><br><br>检查实体字段值的唯一性 通过注解 Unique 检查 合并注解 [In](../../tech.whence.echo.dal.dao/-operation/-s-i-n-g-u-l-a-r-i-z-e/index.md) 内的字段及其值<br><br>  <br>Content  <br>open suspend override fun [singularize](../../tech.whence.echo.dal.dao/-abstract-dao/singularize.md)(entity: [E](index.md))  <br><br><br>
| [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>
| [transact](index.md#tech.whence.echo.dal.dao/AbstractDao/transact/#kotlin.coroutines.SuspendFunction1[tech.whence.echo.support.mongo.MongoClient,TypeParam(bounds=[kotlin.Any?])]/PointingToDeclaration/)| [jvm]  <br>Brief description  <br><br><br>在事务中调用回调 若不支持事务时将直接调用回调<br><br>  <br>Content  <br>open suspend override fun <R> [transact](index.md#tech.whence.echo.dal.dao/AbstractDao/transact/#kotlin.coroutines.SuspendFunction1[tech.whence.echo.support.mongo.MongoClient,TypeParam(bounds=[kotlin.Any?])]/PointingToDeclaration/)(block: [SuspendFunction1](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.coroutines/-suspend-function1/index.html)<[MongoClient](../-mongo-client/index.md), R>): R  <br><br><br>
| [update](../../tech.whence.echo.dal.dao/-abstract-dao/update.md)| [jvm]  <br>Brief description  <br><br><br>更新<br><br>  <br>Content  <br>open suspend override fun [update](../../tech.whence.echo.dal.dao/-abstract-dao/update.md)(entity: [E](index.md)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br>open suspend override fun [update](update.md)(updater: [Update](../../tech.whence.echo.support.mongo.querier/-update/index.md)): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>[jvm]  <br>Brief description  <br><br><br>更新多个<br><br>  <br>Content  <br>open suspend override fun [update](update.md)(entities: [Collection](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-collection/index.html)<[E](index.md)>): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>[jvm]  <br>Brief description  <br><br><br>按照指定主键更新多个字段<br><br>  <br>Content  <br>open suspend override fun [update](../../tech.whence.echo.dal.dao/-abstract-dao/update.md)(batch: [Collection](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-collection/index.html)<[PK](index.md)>, data: [Map](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)<[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), [Serializable](https://docs.oracle.com/javase/8/docs/api/java/io/Serializable.html)>): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>[jvm]  <br>Brief description  <br><br><br>按条件更新<br><br>  <br>Content  <br>open suspend override fun [update](index.md#tech.whence.echo.dal.dao/AbstractDao/update/#tech.whence.echo.support.mongo.querier.component.Where#kotlin.collections.Map[kotlin.String,java.io.Serializable]/PointingToDeclaration/)(restriction: [Where](../../tech.whence.echo.support.mongo.querier.component/-where/index.md), data: [Map](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)<[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), [Serializable](https://docs.oracle.com/javase/8/docs/api/java/io/Serializable.html)>): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>[jvm]  <br>Brief description  <br><br><br>按照指定主键更新字段<br><br>  <br>Content  <br>open suspend override fun [update](../../tech.whence.echo.dal.dao/-writeable/update.md)(batch: [Collection](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-collection/index.html)<[PK](index.md)>, column: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), value: [Serializable](https://docs.oracle.com/javase/8/docs/api/java/io/Serializable.html)): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>[jvm]  <br>Brief description  <br><br><br>按字段更新<br><br>  <br>Content  <br>open suspend override fun [update](../../tech.whence.echo.dal.dao/-abstract-dao/update.md)(batch: [Collection](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-collection/index.html)<[PK](index.md)>, column: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), to: [Serializable](https://docs.oracle.com/javase/8/docs/api/java/io/Serializable.html), unassigned: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br>open suspend override fun <T : [Serializable](https://docs.oracle.com/javase/8/docs/api/java/io/Serializable.html)> [update](../../tech.whence.echo.dal.dao/-abstract-dao/update.md)(batch: [Collection](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-collection/index.html)<[PK](index.md)>, column: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), from: [Collection](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-collection/index.html)<T>, to: T): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>


## Properties  
  
|  Name|  Summary| 
|---|---|
| [creator](index.md#tech.whence.echo.support.mongo/MongoDao/creator/#/PointingToDeclaration/)|  [jvm] <br><br>QC 创建器<br><br>open override val [creator](index.md#tech.whence.echo.support.mongo/MongoDao/creator/#/PointingToDeclaration/): [Insert](../../tech.whence.echo.support.mongo.querier/-insert/index.md)   <br>
| [deleter](index.md#tech.whence.echo.support.mongo/MongoDao/deleter/#/PointingToDeclaration/)|  [jvm] <br><br>QD 删除器<br><br>open override val [deleter](index.md#tech.whence.echo.support.mongo/MongoDao/deleter/#/PointingToDeclaration/): [Delete](../../tech.whence.echo.support.mongo.querier/-delete/index.md)   <br>
| [restrictor](index.md#tech.whence.echo.support.mongo/MongoDao/restrictor/#/PointingToDeclaration/)|  [jvm] <br><br>QF 约束器<br><br>open override val [restrictor](index.md#tech.whence.echo.support.mongo/MongoDao/restrictor/#/PointingToDeclaration/): [Where](../../tech.whence.echo.support.mongo.querier.component/-where/index.md)   <br>
| [retriever](index.md#tech.whence.echo.support.mongo/MongoDao/retriever/#/PointingToDeclaration/)|  [jvm] <br><br>QR 查询器<br><br>open override val [retriever](index.md#tech.whence.echo.support.mongo/MongoDao/retriever/#/PointingToDeclaration/): [Select](../../tech.whence.echo.support.mongo.querier/-select/index.md)   <br>
| [schema](index.md#tech.whence.echo.support.mongo/MongoDao/schema/#/PointingToDeclaration/)|  [jvm] <br><br>Schema<E> 表名<br><br>override val [schema](index.md#tech.whence.echo.support.mongo/MongoDao/schema/#/PointingToDeclaration/): [Schema](../../tech.whence.echo.dal.schema/-schema/index.md)<[E](index.md)>   <br>
| [updater](index.md#tech.whence.echo.support.mongo/MongoDao/updater/#/PointingToDeclaration/)|  [jvm] <br><br>QU 更新器<br><br>open override val [updater](index.md#tech.whence.echo.support.mongo/MongoDao/updater/#/PointingToDeclaration/): [Update](../../tech.whence.echo.support.mongo.querier/-update/index.md)   <br>
