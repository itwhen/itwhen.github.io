---
title: get -
---
//[echo](../../index.md)/[tech.whence.echo.job.stream.provider](../index.md)/[Store](index.md)/[get](get.md)



# get  
[jvm]  
Brief description  


取消息



#### Return  


Message?



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| key| <br><br>String 指定键名<br><br>
  
  
Content  
fun [get](get.md)(key: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): [Message](../../tech.whence.echo.job.stream.message/-message/index.md)?  


[jvm]  
Brief description  


取全部数据



#### Return  


Map<String, Message>

  
Content  
fun [get](get.md)(): [Map](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)<[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), [Message](../../tech.whence.echo.job.stream.message/-message/index.md)>  



