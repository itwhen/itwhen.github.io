---
title: customize -
---
//[echo](../../../index.md)/[tech.whence.echo.support.jdbc.driver.general](../../index.md)/[JdbcDao](../index.md)/[Companion](index.md)/[customize](customize.md)



# customize  
[jvm]  
Brief description  


根据指定结构静态构造



#### Return  


JdbcDAO<DEntity, PK>



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| consumer| <br><br>Consumer<SchemaBuilder<DEntity>> 回调<br><br>
| keys| <br><br>Keys 字段集合<br><br>
| schema| <br><br>String 表名<br><br>
  
  
Content  
fun <[PK](customize.md) : [Serializable](https://docs.oracle.com/javase/8/docs/api/java/io/Serializable.html)> [customize](customize.md)(schema: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), keys: [Keys](../../../tech.whence.echo.dal.schema.key/-keys/index.md), consumer: [Consumer](../../../tech.whence.echo.function/-consumer/index.md)<[Builder](../../../tech.whence.echo.dal.schema/-builder/index.md)<[Record](../../../tech.whence.echo.dal.entity/-record/index.md)>>): [JdbcDao](../index.md)<[Record](../../../tech.whence.echo.dal.entity/-record/index.md), [PK](customize.md)>  



