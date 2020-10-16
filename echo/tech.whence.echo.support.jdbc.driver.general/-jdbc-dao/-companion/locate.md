---
title: locate -
---
//[echo](../../../index.md)/[tech.whence.echo.support.jdbc.driver.general](../../index.md)/[JdbcDao](../index.md)/[Companion](index.md)/[locate](locate.md)



# locate  
[jvm]  
Brief description  


根据实体构造



#### Return  


JdbcDAO<E, PK>



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| consumer| <br><br>Consumer<SchemaBuilder<E>> 回调<br><br>
| schema| <br><br>String 表名<br><br>
  
  
Content  
inline fun <[E](locate.md) : [Entity](../../../tech.whence.echo.dal.entity/-entity/index.md), [PK](locate.md) : [Serializable](https://docs.oracle.com/javase/8/docs/api/java/io/Serializable.html)> [locate](locate.md)(schema: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), consumer: [Consumer](../../../tech.whence.echo.function/-consumer/index.md)<[Builder](../../../tech.whence.echo.dal.schema/-builder/index.md)<[E](locate.md)>>): [JdbcDao](../index.md)<[E](locate.md), [PK](locate.md)>  



