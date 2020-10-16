---
title: tech.whence.echo.support.jdbc.driver.general -
---
//[echo](../index.md)/[tech.whence.echo.support.jdbc.driver.general](index.md)



# Package tech.whence.echo.support.jdbc.driver.general  


## Types  
  
|  Name|  Summary| 
|---|---|
| [JdbcClient](-jdbc-client/index.md)| [jvm]  <br>Brief description  <br><br><br>JDBC客户端<br><br>  <br>Content  <br>class [JdbcClient](-jdbc-client/index.md)(**producer**: [Producer](../tech.whence.echo.function/-producer/index.md)<JDBCClient>) : [Client](../tech.whence.echo.dal.dao/-client/index.md)<[JdbcClient](-jdbc-client/index.md), SQLConnection>   <br><br><br>
| [JdbcDao](-jdbc-dao/index.md)| [jvm]  <br>Brief description  <br><br><br>JDBC DAO<br><br>  <br>Content  <br>abstract class [JdbcDao](-jdbc-dao/index.md)<[E](-jdbc-dao/index.md) : [Entity](../tech.whence.echo.dal.entity/-entity/index.md), [PK](-jdbc-dao/index.md) : [Serializable](https://docs.oracle.com/javase/8/docs/api/java/io/Serializable.html)> : [AbstractDao](../tech.whence.echo.dal.dao/-abstract-dao/index.md)<[E](-jdbc-dao/index.md), [PK](-jdbc-dao/index.md), [JdbcClient](-jdbc-client/index.md), JDBCClient, [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[Accessor](../tech.whence.echo.container.accessor/-accessor/index.md)>, [Accessor](../tech.whence.echo.container.accessor/-accessor/index.md), [JdbcEntityAssembler](-jdbc-entity-assembler/index.md), [Insert](../tech.whence.echo.support.jdbc.driver.general.querier/-insert/index.md), [Update](../tech.whence.echo.support.jdbc.driver.general.querier/-update/index.md), [Select](../tech.whence.echo.support.jdbc.driver.general.querier/-select/index.md), [Delete](../tech.whence.echo.support.jdbc.driver.general.querier/-delete/index.md), [Where](../tech.whence.echo.support.jdbc.querier.component/-where/index.md), [Column](../tech.whence.echo.support.jdbc.querier.component/-column/index.md), [Criterion](../tech.whence.echo.support.jdbc.querier.component/-criterion/index.md)<*>, [Definer](../tech.whence.echo.support.jdbc.querier.component/-definer/index.md)<*>>   <br><br><br>
| [JdbcDataSource](-jdbc-data-source/index.md)| [jvm]  <br>Brief description  <br><br><br>JDBC数据源<br><br>  <br>Content  <br>class [JdbcDataSource](-jdbc-data-source/index.md)(**url**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)) : [DataSource](../tech.whence.echo.dal/-data-source/index.md)  <br><br><br>
| [JdbcEntityAssembler](-jdbc-entity-assembler/index.md)| [jvm]  <br>Brief description  <br><br><br>JDBC实体组装器<br><br>  <br>Content  <br>class [JdbcEntityAssembler](-jdbc-entity-assembler/index.md)(**wrapper**: [Wrapper](../tech.whence.echo.dal.entity.wrapper/-wrapper/index.md)) : [AbstractAssembler](../tech.whence.echo.dal.entity.assembler/-abstract-assembler/index.md)<[Accessor](../tech.whence.echo.container.accessor/-accessor/index.md), [Set](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-set/index.html)<[Column](../tech.whence.echo.support.jdbc.querier.component/-column/index.md)>, [Column](../tech.whence.echo.support.jdbc.querier.component/-column/index.md)>   <br><br><br>

