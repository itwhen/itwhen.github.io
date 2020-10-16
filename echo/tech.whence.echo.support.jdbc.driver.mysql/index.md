---
title: tech.whence.echo.support.jdbc.driver.mysql -
---
//[echo](../index.md)/[tech.whence.echo.support.jdbc.driver.mysql](index.md)



# Package tech.whence.echo.support.jdbc.driver.mysql  


## Types  
  
|  Name|  Summary| 
|---|---|
| [MysqlClient](-mysql-client/index.md)| [jvm]  <br>Brief description  <br><br><br>MySQL客户端<br><br>  <br>Content  <br>class [MysqlClient](-mysql-client/index.md)(**producer**: [Producer](../tech.whence.echo.function/-producer/index.md)<MySQLPool>) : [Client](../tech.whence.echo.dal.dao/-client/index.md)<[MysqlClient](-mysql-client/index.md), SqlConnection>   <br><br><br>
| [MysqlDao](-mysql-dao/index.md)| [jvm]  <br>Brief description  <br><br><br>MySQL DAO<br><br>  <br>Content  <br>abstract class [MysqlDao](-mysql-dao/index.md)<[E](-mysql-dao/index.md) : [Entity](../tech.whence.echo.dal.entity/-entity/index.md), [PK](-mysql-dao/index.md) : [Serializable](https://docs.oracle.com/javase/8/docs/api/java/io/Serializable.html)> : [AbstractDao](../tech.whence.echo.dal.dao/-abstract-dao/index.md)<[E](-mysql-dao/index.md), [PK](-mysql-dao/index.md), [MysqlClient](-mysql-client/index.md), MySQLConnection, RowSet<Row>, Row, [MysqlEntityAssembler](-mysql-entity-assembler/index.md), [Insert](../tech.whence.echo.support.jdbc.driver.mysql.querier/-insert/index.md), [Update](../tech.whence.echo.support.jdbc.driver.mysql.querier/-update/index.md), [Select](../tech.whence.echo.support.jdbc.driver.mysql.querier/-select/index.md), [Delete](../tech.whence.echo.support.jdbc.driver.mysql.querier/-delete/index.md), [Where](../tech.whence.echo.support.jdbc.querier.component/-where/index.md), [Column](../tech.whence.echo.support.jdbc.querier.component/-column/index.md), [Criterion](../tech.whence.echo.support.jdbc.querier.component/-criterion/index.md)<*>, [Definer](../tech.whence.echo.support.jdbc.querier.component/-definer/index.md)<*>>   <br><br><br>
| [MysqlDataSource](-mysql-data-source/index.md)| [jvm]  <br>Brief description  <br><br><br>MySQL数据源<br><br>  <br>Content  <br>class [MysqlDataSource](-mysql-data-source/index.md)(**url**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)) : [DataSource](../tech.whence.echo.dal/-data-source/index.md)  <br><br><br>
| [MysqlEntityAssembler](-mysql-entity-assembler/index.md)| [jvm]  <br>Brief description  <br><br><br>MySQL实体组装器<br><br>  <br>Content  <br>class [MysqlEntityAssembler](-mysql-entity-assembler/index.md)(**wrapper**: [Wrapper](../tech.whence.echo.dal.entity.wrapper/-wrapper/index.md)) : [AbstractAssembler](../tech.whence.echo.dal.entity.assembler/-abstract-assembler/index.md)<Row, [Set](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-set/index.html)<[Column](../tech.whence.echo.support.jdbc.querier.component/-column/index.md)>, [Column](../tech.whence.echo.support.jdbc.querier.component/-column/index.md)>   <br><br><br>

