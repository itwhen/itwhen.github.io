---
title: getQuery -
---
//[echo](../../index.md)/[tech.whence.echo.container](../index.md)/[Accessibility](index.md)/[getQuery](get-query.md)



# getQuery  
[jvm]  
Brief description  


取查询字符串数据



#### Return  


Result<Accessor>



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| assignment| <br><br>String 赋值符<br><br>
| fixer| <br><br>Transformer<String, String>? 纠正器<br><br>
| key| <br><br>K 指定键<br><br>
| separator| <br><br>String 分隔符<br><br>
  
  
Content  
open fun [getQuery](get-query.md)(key: [K](index.md), separator: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), assignment: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), fixer: [Fixer](../../tech.whence.echo.function/-fixer/index.md)<[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)>?): [Reply](../-reply/index.md)<[Accessor](../../tech.whence.echo.container.accessor/-accessor/index.md)>  



