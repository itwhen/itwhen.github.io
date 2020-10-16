---
title: blueprint -
---
//[echo](../../index.md)/[tech.whence.echo.rpc.payload](../index.md)/[Searching](index.md)/[blueprint](blueprint.md)



# blueprint  
[jvm]  
Brief description  


生成查询条件



#### Return  


Criteria



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| defaultLimit| <br><br>UInt 默认负载<br><br>
| defaultPage| <br><br>UInt 默认分页<br><br>
| fixer| <br><br>Consumer<Criteria>? 纠正<br><br>
| keys| <br><br>Keys 指定字段<br><br>
  
  
Content  
@[JvmOverloads](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-overloads/index.html)()  
  
fun [blueprint](blueprint.md)(keys: [Keys](../../tech.whence.echo.dal.schema.key/-keys/index.md), defaultLimit: [UInt](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-u-int/index.html), defaultPage: [UInt](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-u-int/index.html), fixer: [Consumer](../../tech.whence.echo.function/-consumer/index.md)<[Criteria](../../tech.whence.echo.dal.filter/-criteria/index.md)>?): [Criteria](../../tech.whence.echo.dal.filter/-criteria/index.md)  



