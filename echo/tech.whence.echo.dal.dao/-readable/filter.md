---
title: filter -
---
//[echo](../../index.md)/[tech.whence.echo.dal.dao](../index.md)/[Readable](index.md)/[filter](filter.md)



# filter  
[jvm]  
Brief description  


过滤字段 效率考虑指定字段必须有身份 [tech.whence.echo.dal.schema.key.Identity](../../tech.whence.echo.dal.schema.key/-identity/index.md)



#### Return  


Paginator<E>



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| column| <br><br>String 指定字段<br><br>
| limit| <br><br>UInt<br><br>
| page| <br><br>UInt<br><br>
| values| <br><br>Collection<Serializable> 相关值<br><br>
  
  
Content  
abstract suspend fun [filter](filter.md)(column: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), values: [Collection](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-collection/index.html)<[Serializable](https://docs.oracle.com/javase/8/docs/api/java/io/Serializable.html)>, limit: [UInt](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-u-int/index.html), page: [UInt](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-u-int/index.html)): [Paginator](../../tech.whence.echo.container/-paginator/index.md)<[E](index.md)>  


[jvm]  
Brief description  


过滤字段



#### Return  


Paginator<E>



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| column| <br><br>String 指定字段<br><br>
| limit| <br><br>UInt<br><br>
| page| <br><br>UInt<br><br>
| value| <br><br>Collection<Serializable> 相关值<br><br>
  
  
Content  
open suspend fun [filter](filter.md)(column: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), value: [Serializable](https://docs.oracle.com/javase/8/docs/api/java/io/Serializable.html), limit: [UInt](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-u-int/index.html), page: [UInt](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-u-int/index.html)): [Paginator](../../tech.whence.echo.container/-paginator/index.md)<[E](index.md)>  



