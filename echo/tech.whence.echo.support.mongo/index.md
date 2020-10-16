---
title: tech.whence.echo.support.mongo -
---
//[echo](../index.md)/[tech.whence.echo.support.mongo](index.md)



# Package tech.whence.echo.support.mongo  


## Types  
  
|  Name|  Summary| 
|---|---|
| [MongoClient](-mongo-client/index.md)| [jvm]  <br>Brief description  <br><br><br>Mongo客户端<br><br>  <br>Content  <br>class [MongoClient](-mongo-client/index.md)(**producer**: [Producer](../tech.whence.echo.function/-producer/index.md)<MongoClient>) : [Client](../tech.whence.echo.dal.dao/-client/index.md)<[MongoClient](-mongo-client/index.md), MongoClient>   <br><br><br>
| [MongoDao](-mongo-dao/index.md)| [jvm]  <br>Brief description  <br><br><br>MySQL DAO<br><br>  <br>Content  <br>abstract class [MongoDao](-mongo-dao/index.md)<[E](-mongo-dao/index.md) : [Entity](../tech.whence.echo.dal.entity/-entity/index.md), [PK](-mongo-dao/index.md) : [Serializable](https://docs.oracle.com/javase/8/docs/api/java/io/Serializable.html)> : [AbstractDao](../tech.whence.echo.dal.dao/-abstract-dao/index.md)<[E](-mongo-dao/index.md), [PK](-mongo-dao/index.md), [MongoClient](-mongo-client/index.md), MySQLConnection, [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<JsonObject>, JsonObject, [MongoEntityAssembler](-mongo-entity-assembler/index.md), [Insert](../tech.whence.echo.support.mongo.querier/-insert/index.md), [Update](../tech.whence.echo.support.mongo.querier/-update/index.md), [Select](../tech.whence.echo.support.mongo.querier/-select/index.md), [Delete](../tech.whence.echo.support.mongo.querier/-delete/index.md), [Where](../tech.whence.echo.support.mongo.querier.component/-where/index.md), [Column](../tech.whence.echo.support.mongo.querier.component/-column/index.md), [Criterion](../tech.whence.echo.support.mongo.querier.component/-criterion/index.md)<*>, [Definer](../tech.whence.echo.support.mongo.querier.component/-definer/index.md)<*, *>>   <br><br><br>
| [MongoDataSource](-mongo-data-source/index.md)| [jvm]  <br>Brief description  <br><br><br>Mongo数据源<br><br>  <br>Content  <br>class [MongoDataSource](-mongo-data-source/index.md)(**url**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)) : [DataSource](../tech.whence.echo.dal/-data-source/index.md)  <br><br><br>
| [MongoEntityAssembler](-mongo-entity-assembler/index.md)| [jvm]  <br>Brief description  <br><br><br>Mongo实体组装器<br><br>  <br>Content  <br>class [MongoEntityAssembler](-mongo-entity-assembler/index.md)(**wrapper**: [Wrapper](../tech.whence.echo.dal.entity.wrapper/-wrapper/index.md)) : [AbstractAssembler](../tech.whence.echo.dal.entity.assembler/-abstract-assembler/index.md)<JsonObject, [Set](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-set/index.html)<[Column](../tech.whence.echo.support.mongo.querier.component/-column/index.md)>, [Column](../tech.whence.echo.support.mongo.querier.component/-column/index.md)>   <br><br><br>

