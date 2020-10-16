---
title: invoke -
---
//[echo](../../../index.md)/[tech.whence.echo.dal.connection](../../index.md)/[ConnectionString](../index.md)/[Companion](index.md)/[invoke](invoke.md)



# invoke  
[jvm]  
Brief description  


基于查询字符串构造



#### Return  


ConnectionString



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| url| <br><br>String 指定查询字符串<br><br>
  
  
Content  
@[JvmStatic](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-static/index.html)()  
  
operator fun [invoke](invoke.md)(url: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): [ConnectionString](../index.md)  


[jvm]  
Brief description  


根据数据源构造



#### Return  


ConnectionString



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| source| <br><br>DataSource 指定数据源<br><br>
| type| <br><br>String 默认类型<br><br>
  
  
Content  
@[JvmStatic](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-static/index.html)()  
  
operator fun [invoke](invoke.md)(source: [DataSource](../../../tech.whence.echo.dal/-data-source/index.md), type: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): [ConnectionString](../index.md)  



