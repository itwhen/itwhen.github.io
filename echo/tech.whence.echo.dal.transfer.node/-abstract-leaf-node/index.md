---
title: AbstractLeafNode -
---
//[echo](../../index.md)/[tech.whence.echo.dal.transfer.node](../index.md)/[AbstractLeafNode](index.md)



# AbstractLeafNode  
 [jvm] 

抽象子节点

abstract class [AbstractLeafNode](index.md)<[D](index.md) : [Dao](../../tech.whence.echo.dal.dao/-dao/index.md)<[Record](../../tech.whence.echo.dal.entity/-record/index.md), [PK](index.md), *>, [Queriable](../../tech.whence.echo.dal.dao/-queriable/index.md)<[Record](../../tech.whence.echo.dal.entity/-record/index.md), *, *, *, [QR](index.md), [QD](index.md), *, *, *, *>, [QR](index.md) : [Retriever](../../tech.whence.echo.dal.querier/-retriever/index.md)<[QR](index.md), [R](index.md), *, *, *>, [QD](index.md) : [Deleter](../../tech.whence.echo.dal.querier/-deleter/index.md)<[QD](index.md), [R](index.md), *, *, *>, [R](index.md) : [Restrictor](../../tech.whence.echo.dal.querier.component/-restrictor/index.md)<[R](index.md), [R](index.md), *, *>, [PK](index.md) : [Serializable](https://docs.oracle.com/javase/8/docs/api/java/io/Serializable.html)>(**vertx**: Vertx, **setting**: [Setting](../../tech.whence.echo.dal.transfer.project/-setting/index.md), **mode**: [Mode](../../tech.whence.echo.dal.transfer/-mode/index.md)) : [AbstractNode](../-abstract-node/index.md)<[D](index.md), [QR](index.md), [R](index.md), [PK](index.md)> , [LeafNode](../-leaf-node/index.md)<[PK](index.md)>    


## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| D| <br><br>数据层类型<br><br>
| PK| <br><br>主键类型<br><br>
| QD| <br><br>删除<br><br>
| QR| <br><br>查询<br><br>
| R| <br><br>条件<br><br>
  


## Constructors  
  
|  Name|  Summary| 
|---|---|
| [AbstractLeafNode](-abstract-leaf-node.md)|  [jvm] <br><br><br><br>fun [AbstractLeafNode](-abstract-leaf-node.md)(vertx: Vertx, setting: [Setting](../../tech.whence.echo.dal.transfer.project/-setting/index.md), mode: [Mode](../../tech.whence.echo.dal.transfer/-mode/index.md))   <br>


## Functions  
  
|  Name|  Summary| 
|---|---|
| [count](../-abstract-node/count.md)| [jvm]  <br>Content  <br>open suspend override fun [count](../-abstract-node/count.md)(direction: [Direction](../-direction/index.md)): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)| [jvm]  <br>Content  <br>open operator override fun [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [name](../-abstract-node/name.md)| [jvm]  <br>Content  <br>open override fun [name](../-abstract-node/name.md)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>
| [preconnect](../-abstract-node/preconnect.md)| [jvm]  <br>Content  <br>open override fun [preconnect](../-abstract-node/preconnect.md)(mode: [Mode](../../tech.whence.echo.dal.transfer/-mode/index.md), direction: [Direction](../-direction/index.md), connection: [ConnectionString](../../tech.whence.echo.dal.connection/-connection-string/index.md))  <br><br><br>
| [read](read.md)| [jvm]  <br>Brief description  <br><br><br>读取数据<br><br>  <br>Content  <br>open suspend override fun [read](read.md)(direction: [Direction](../-direction/index.md), key: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), values: [Set](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-set/index.html)<[Serializable](https://docs.oracle.com/javase/8/docs/api/java/io/Serializable.html)>): [Records](../../tech.whence.echo.dal.entity/index.md#tech.whence.echo.dal.entity/Records///PointingToDeclaration/)  <br><br><br>[jvm]  <br>Content  <br>open suspend override fun [read](../-abstract-node/read.md)(direction: [Direction](../-direction/index.md), relation: [Relation](../../tech.whence.echo.dal.transfer/-relation/index.md), batch: [Set](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-set/index.html)<[PK](index.md)>): [Records](../../tech.whence.echo.dal.entity/index.md#tech.whence.echo.dal.entity/Records///PointingToDeclaration/)  <br><br><br>
| [redefine](../-abstract-node/redefine.md)| [jvm]  <br>Content  <br>open suspend override fun [redefine](../-abstract-node/redefine.md)(direction: [Direction](../-direction/index.md))  <br><br><br>
| [remove](remove.md)| [jvm]  <br>Brief description  <br><br><br>删除数据<br><br>  <br>Content  <br>open suspend override fun [remove](remove.md)(direction: [Direction](../-direction/index.md), key: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), values: [Set](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-set/index.html)<[Serializable](https://docs.oracle.com/javase/8/docs/api/java/io/Serializable.html)>): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [root](../-node/root.md)| [jvm]  <br>Content  <br>open override fun [root](../-node/root.md)(): [Root](../-root/index.md)<[Serializable](https://docs.oracle.com/javase/8/docs/api/java/io/Serializable.html), [Scope](../../tech.whence.echo.dal.transfer.scope/-scope/index.md)<[Serializable](https://docs.oracle.com/javase/8/docs/api/java/io/Serializable.html)>>  <br><br><br>
| [schematize](../-abstract-node/schematize.md)| [jvm]  <br>Content  <br>open override fun [schematize](../-abstract-node/schematize.md)(direction: [Direction](../-direction/index.md)): [Schema](../../tech.whence.echo.dal.schema/-schema/index.md)<[Record](../../tech.whence.echo.dal.entity/-record/index.md)>  <br><br><br>
| [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>
| [write](../-abstract-node/write.md)| [jvm]  <br>Content  <br>open suspend override fun [write](../-abstract-node/write.md)(direction: [Direction](../-direction/index.md), data: [Set](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-set/index.html)<[Record](../../tech.whence.echo.dal.entity/-record/index.md)>): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br>open suspend override fun [write](../-abstract-node/write.md)(direction: [Direction](../-direction/index.md), data: [Record](../../tech.whence.echo.dal.entity/-record/index.md), update: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>


## Properties  
  
|  Name|  Summary| 
|---|---|
| [daos](index.md#tech.whence.echo.dal.transfer.node/AbstractLeafNode/daos/#/PointingToDeclaration/)|  [jvm] <br><br>EnumMap<Direction, D> 数据层存放<br><br>override var [daos](index.md#tech.whence.echo.dal.transfer.node/AbstractLeafNode/daos/#/PointingToDeclaration/): [EnumMap](https://docs.oracle.com/javase/8/docs/api/java/util/EnumMap.html)<[Direction](../-direction/index.md), [D](index.md)>   <br>
| [location](index.md#tech.whence.echo.dal.transfer.node/AbstractLeafNode/location/#/PointingToDeclaration/)|  [jvm] open override val [location](index.md#tech.whence.echo.dal.transfer.node/AbstractLeafNode/location/#/PointingToDeclaration/): [Location](../-location/index.md)   <br>
| [mode](index.md#tech.whence.echo.dal.transfer.node/AbstractLeafNode/mode/#/PointingToDeclaration/)|  [jvm] open override val [mode](index.md#tech.whence.echo.dal.transfer.node/AbstractLeafNode/mode/#/PointingToDeclaration/): [Mode](../../tech.whence.echo.dal.transfer/-mode/index.md)   <br>
| [setting](index.md#tech.whence.echo.dal.transfer.node/AbstractLeafNode/setting/#/PointingToDeclaration/)|  [jvm] open override val [setting](index.md#tech.whence.echo.dal.transfer.node/AbstractLeafNode/setting/#/PointingToDeclaration/): [Setting](../../tech.whence.echo.dal.transfer.project/-setting/index.md)   <br>
| [sourceChanged](index.md#tech.whence.echo.dal.transfer.node/AbstractLeafNode/sourceChanged/#/PointingToDeclaration/)|  [jvm] open override val [sourceChanged](index.md#tech.whence.echo.dal.transfer.node/AbstractLeafNode/sourceChanged/#/PointingToDeclaration/): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)   <br>


## Inheritors  
  
|  Name| 
|---|
| [JdbcLeafNode](../../tech.whence.echo.support.jdbc.driver.general.transfer/-jdbc-leaf-node/index.md)
| [MysqlLeafNode](../../tech.whence.echo.support.jdbc.driver.mysql.transfer/-mysql-leaf-node/index.md)
| [MongoLeafNode](../../tech.whence.echo.support.mongo.transfer/-mongo-leaf-node/index.md)

