---
title: JdbcLeafNode -
---
//[echo](../../index.md)/[tech.whence.echo.support.jdbc.driver.general.transfer](../index.md)/[JdbcLeafNode](index.md)



# JdbcLeafNode  
 [jvm] 

Jdbc子节点

class [JdbcLeafNode](index.md)<[PK](index.md) : [Serializable](https://docs.oracle.com/javase/8/docs/api/java/io/Serializable.html)>(**vertx**: Vertx, **setting**: [Setting](../../tech.whence.echo.dal.transfer.project/-setting/index.md), **mode**: [Mode](../../tech.whence.echo.dal.transfer/-mode/index.md)) : [AbstractLeafNode](../../tech.whence.echo.dal.transfer.node/-abstract-leaf-node/index.md)<[JdbcDao](../../tech.whence.echo.support.jdbc.driver.general/-jdbc-dao/index.md)<[Record](../../tech.whence.echo.dal.entity/-record/index.md), [PK](index.md)>, [Select](../../tech.whence.echo.support.jdbc.driver.general.querier/-select/index.md), [Delete](../../tech.whence.echo.support.jdbc.driver.general.querier/-delete/index.md), [Where](../../tech.whence.echo.support.jdbc.querier.component/-where/index.md), [PK](index.md)> , [JdbcSource](../-jdbc-source/index.md)<[PK](index.md)>    


## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| PK| <br><br>: Serializable 主键类型<br><br>
  


## Constructors  
  
|  Name|  Summary| 
|---|---|
| [JdbcLeafNode](-jdbc-leaf-node.md)|  [jvm] <br><br>: Serializable 主键类型<br><br>fun [JdbcLeafNode](-jdbc-leaf-node.md)(vertx: Vertx, setting: [Setting](../../tech.whence.echo.dal.transfer.project/-setting/index.md), mode: [Mode](../../tech.whence.echo.dal.transfer/-mode/index.md))   <br>


## Functions  
  
|  Name|  Summary| 
|---|---|
| [count](../../tech.whence.echo.dal.transfer.node/-abstract-node/count.md)| [jvm]  <br>Content  <br>open suspend override fun [count](../../tech.whence.echo.dal.transfer.node/-abstract-node/count.md)(direction: [Direction](../../tech.whence.echo.dal.transfer.node/-direction/index.md)): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)| [jvm]  <br>Content  <br>open operator override fun [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [name](../../tech.whence.echo.dal.transfer.node/-abstract-node/name.md)| [jvm]  <br>Content  <br>open override fun [name](../../tech.whence.echo.dal.transfer.node/-abstract-node/name.md)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>
| [preconnect](../../tech.whence.echo.dal.transfer.node/-abstract-node/preconnect.md)| [jvm]  <br>Content  <br>open override fun [preconnect](../../tech.whence.echo.dal.transfer.node/-abstract-node/preconnect.md)(mode: [Mode](../../tech.whence.echo.dal.transfer/-mode/index.md), direction: [Direction](../../tech.whence.echo.dal.transfer.node/-direction/index.md), connection: [ConnectionString](../../tech.whence.echo.dal.connection/-connection-string/index.md))  <br><br><br>
| [read](../../tech.whence.echo.dal.transfer.node/-abstract-leaf-node/read.md)| [jvm]  <br>Brief description  <br><br><br>读取数据<br><br>  <br>Content  <br>open suspend override fun [read](../../tech.whence.echo.dal.transfer.node/-abstract-leaf-node/read.md)(direction: [Direction](../../tech.whence.echo.dal.transfer.node/-direction/index.md), key: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), values: [Set](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-set/index.html)<[Serializable](https://docs.oracle.com/javase/8/docs/api/java/io/Serializable.html)>): [Records](../../tech.whence.echo.dal.entity/index.md#tech.whence.echo.dal.entity/Records///PointingToDeclaration/)  <br><br><br>[jvm]  <br>Content  <br>open suspend override fun [read](../../tech.whence.echo.dal.transfer.node/-abstract-node/read.md)(direction: [Direction](../../tech.whence.echo.dal.transfer.node/-direction/index.md), relation: [Relation](../../tech.whence.echo.dal.transfer/-relation/index.md), batch: [Set](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-set/index.html)<[PK](index.md)>): [Records](../../tech.whence.echo.dal.entity/index.md#tech.whence.echo.dal.entity/Records///PointingToDeclaration/)  <br><br><br>
| [redefine](../../tech.whence.echo.dal.transfer.node/-abstract-node/redefine.md)| [jvm]  <br>Content  <br>open suspend override fun [redefine](../../tech.whence.echo.dal.transfer.node/-abstract-node/redefine.md)(direction: [Direction](../../tech.whence.echo.dal.transfer.node/-direction/index.md))  <br><br><br>
| [remove](../../tech.whence.echo.dal.transfer.node/-abstract-leaf-node/remove.md)| [jvm]  <br>Brief description  <br><br><br>删除数据<br><br>  <br>Content  <br>open suspend override fun [remove](../../tech.whence.echo.dal.transfer.node/-abstract-leaf-node/remove.md)(direction: [Direction](../../tech.whence.echo.dal.transfer.node/-direction/index.md), key: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), values: [Set](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-set/index.html)<[Serializable](https://docs.oracle.com/javase/8/docs/api/java/io/Serializable.html)>): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [root](../../tech.whence.echo.dal.transfer.node/-node/root.md)| [jvm]  <br>Content  <br>open override fun [root](../../tech.whence.echo.dal.transfer.node/-node/root.md)(): [Root](../../tech.whence.echo.dal.transfer.node/-root/index.md)<[Serializable](https://docs.oracle.com/javase/8/docs/api/java/io/Serializable.html), [Scope](../../tech.whence.echo.dal.transfer.scope/-scope/index.md)<[Serializable](https://docs.oracle.com/javase/8/docs/api/java/io/Serializable.html)>>  <br><br><br>
| [schematize](../../tech.whence.echo.dal.transfer.node/-abstract-node/schematize.md)| [jvm]  <br>Content  <br>open override fun [schematize](../../tech.whence.echo.dal.transfer.node/-abstract-node/schematize.md)(direction: [Direction](../../tech.whence.echo.dal.transfer.node/-direction/index.md)): [Schema](../../tech.whence.echo.dal.schema/-schema/index.md)<[Record](../../tech.whence.echo.dal.entity/-record/index.md)>  <br><br><br>
| [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>
| [write](../../tech.whence.echo.dal.transfer.node/-abstract-node/write.md)| [jvm]  <br>Content  <br>open suspend override fun [write](../../tech.whence.echo.dal.transfer.node/-abstract-node/write.md)(direction: [Direction](../../tech.whence.echo.dal.transfer.node/-direction/index.md), data: [Set](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-set/index.html)<[Record](../../tech.whence.echo.dal.entity/-record/index.md)>): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br>open suspend override fun [write](../../tech.whence.echo.dal.transfer.node/-abstract-node/write.md)(direction: [Direction](../../tech.whence.echo.dal.transfer.node/-direction/index.md), data: [Record](../../tech.whence.echo.dal.entity/-record/index.md), update: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>


## Properties  
  
|  Name|  Summary| 
|---|---|
| [daos](index.md#tech.whence.echo.support.jdbc.driver.general.transfer/JdbcLeafNode/daos/#/PointingToDeclaration/)|  [jvm] <br><br>EnumMap<Direction, D> 数据层存放<br><br>override var [daos](index.md#tech.whence.echo.support.jdbc.driver.general.transfer/JdbcLeafNode/daos/#/PointingToDeclaration/): [EnumMap](https://docs.oracle.com/javase/8/docs/api/java/util/EnumMap.html)<[Direction](../../tech.whence.echo.dal.transfer.node/-direction/index.md), [JdbcDao](../../tech.whence.echo.support.jdbc.driver.general/-jdbc-dao/index.md)<[Record](../../tech.whence.echo.dal.entity/-record/index.md), [PK](index.md)>>   <br>
| [location](index.md#tech.whence.echo.support.jdbc.driver.general.transfer/JdbcLeafNode/location/#/PointingToDeclaration/)|  [jvm] open override val [location](index.md#tech.whence.echo.support.jdbc.driver.general.transfer/JdbcLeafNode/location/#/PointingToDeclaration/): [Location](../../tech.whence.echo.dal.transfer.node/-location/index.md)   <br>
| [mode](index.md#tech.whence.echo.support.jdbc.driver.general.transfer/JdbcLeafNode/mode/#/PointingToDeclaration/)|  [jvm] open override val [mode](index.md#tech.whence.echo.support.jdbc.driver.general.transfer/JdbcLeafNode/mode/#/PointingToDeclaration/): [Mode](../../tech.whence.echo.dal.transfer/-mode/index.md)   <br>
| [setting](index.md#tech.whence.echo.support.jdbc.driver.general.transfer/JdbcLeafNode/setting/#/PointingToDeclaration/)|  [jvm] open override val [setting](index.md#tech.whence.echo.support.jdbc.driver.general.transfer/JdbcLeafNode/setting/#/PointingToDeclaration/): [Setting](../../tech.whence.echo.dal.transfer.project/-setting/index.md)   <br>
| [sourceChanged](index.md#tech.whence.echo.support.jdbc.driver.general.transfer/JdbcLeafNode/sourceChanged/#/PointingToDeclaration/)|  [jvm] open override val [sourceChanged](index.md#tech.whence.echo.support.jdbc.driver.general.transfer/JdbcLeafNode/sourceChanged/#/PointingToDeclaration/): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)   <br>

