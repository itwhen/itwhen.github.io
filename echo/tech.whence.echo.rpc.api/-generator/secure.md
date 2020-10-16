---
title: secure -
---
//[echo](../../index.md)/[tech.whence.echo.rpc.api](../index.md)/[Generator](index.md)/[secure](secure.md)



# secure  
[jvm]  
Brief description  


设置安全策略



#### Return  


Generator



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| requirement| <br><br>SecurityRequirement 默认安全策略<br><br>
| schemes| <br><br>Map<String, SecurityScheme> 可用安全策略<br><br>
  
  
Content  
fun [secure](secure.md)(schemes: [Map](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)<[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), SecurityScheme>, requirement: SecurityRequirement): [Generator](index.md)  



