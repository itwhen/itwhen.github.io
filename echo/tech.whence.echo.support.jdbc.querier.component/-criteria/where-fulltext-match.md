---
title: whereFulltextMatch -
---
//[echo](../../index.md)/[tech.whence.echo.support.jdbc.querier.component](../index.md)/[Criteria](index.md)/[whereFulltextMatch](where-fulltext-match.md)



# whereFulltextMatch  
[jvm]  
Brief description  


判断指定字段是否与指定值全文匹配



#### Return  


T



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| mode| <br><br>Mode 指定模式<br><br>
| name| <br><br>String 指定字段<br><br>
| value| <br><br>String 指定值<br><br>
  
  
Content  
open fun [whereFulltextMatch](where-fulltext-match.md)(name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), value: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), mode: [FulltextMatch.Mode](../../tech.whence.echo.support.jdbc.querier.criterion/-fulltext-match/-mode/index.md)): [T](index.md)  


[jvm]  
Brief description  


判断指定字段是否与指定值全文匹配



#### Return  


T



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| mode| <br><br>Mode 指定模式<br><br>
| names| <br><br>Set<String> 指定字段<br><br>
| value| <br><br>String 指定值<br><br>
  
  
Content  
open fun [whereFulltextMatch](where-fulltext-match.md)(names: [Set](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-set/index.html)<[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)>, value: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), mode: [FulltextMatch.Mode](../../tech.whence.echo.support.jdbc.querier.criterion/-fulltext-match/-mode/index.md)): [T](index.md)  



