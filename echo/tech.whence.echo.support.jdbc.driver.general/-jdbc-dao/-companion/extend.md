---
title: extend -
---
//[echo](../../../index.md)/[tech.whence.echo.support.jdbc.driver.general](../../index.md)/[JdbcDao](../index.md)/[Companion](index.md)/[extend](extend.md)



# extend  
[jvm]  
Brief description  


根据扩展静态构造



#### Return  


D



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| client| <br><br>JdbcClient 客户端<br><br>
| producer| <br><br>Producer<D> 初始化<br><br>
  
  
Content  
fun <[D](extend.md) : [JdbcDao](../index.md)<out [Entity](../../../tech.whence.echo.dal.entity/-entity/index.md), [PK](extend.md)>, [PK](extend.md) : [Serializable](https://docs.oracle.com/javase/8/docs/api/java/io/Serializable.html)> [extend](extend.md)(client: [JdbcClient](../../-jdbc-client/index.md), producer: [Producer](../../../tech.whence.echo.function/-producer/index.md)<[D](extend.md)>): [D](extend.md)  



