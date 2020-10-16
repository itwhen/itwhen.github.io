---
title: sourcing -
---
//[echo](../../../index.md)/[tech.whence.echo.support.jdbc.driver.general](../../index.md)/[JdbcDao](../index.md)/[Companion](index.md)/[sourcing](sourcing.md)



# sourcing  
[jvm]  
Brief description  


根据数据源结构静态构造



#### Return  


JdbcDAO<DEntity, PK>



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| consumer| <br><br>Consumer<SchemaBuilder<DEntity>> 回调<br><br>
| schema| <br><br>String 表名<br><br>
  
  
Content  
fun <[PK](sourcing.md) : [Serializable](https://docs.oracle.com/javase/8/docs/api/java/io/Serializable.html)> [sourcing](sourcing.md)(schema: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), consumer: [Consumer](../../../tech.whence.echo.function/-consumer/index.md)<[Builder](../../../tech.whence.echo.dal.schema/-builder/index.md)<[Record](../../../tech.whence.echo.dal.entity/-record/index.md)>>): [JdbcDao](../index.md)<[Record](../../../tech.whence.echo.dal.entity/-record/index.md), [PK](sourcing.md)>  



