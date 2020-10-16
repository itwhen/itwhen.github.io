---
title: update -
---
//[echo](../../index.md)/[tech.whence.echo.support.jdbc.driver.mysql](../index.md)/[MysqlDao](index.md)/[update](update.md)



# update  
[jvm]  
Brief description  


更新



#### Return  


Long



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| updater| <br><br>QU 更新器<br><br>
  
  
Content  
open suspend override fun [update](update.md)(updater: [Update](../../tech.whence.echo.support.jdbc.driver.mysql.querier/-update/index.md)): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  


[jvm]  
Brief description  


更新多个



#### Return  


Int



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| entities| <br><br>Collection<E> 指定实体<br><br>
  
  
Content  
open suspend override fun [update](update.md)(entities: [Collection](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-collection/index.html)<[E](index.md)>): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  



