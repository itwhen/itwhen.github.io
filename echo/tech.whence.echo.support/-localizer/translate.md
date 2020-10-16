---
title: translate -
---
//[echo](../../index.md)/[tech.whence.echo.support](../index.md)/[Localizer](index.md)/[translate](translate.md)



# translate  
[jvm]  
Brief description  


本地化消息 若数据中找不到指定message则用本身代替 将用name替换消息中占位符:it 若simplify为真时将占位符:it替换为空字符串



#### Return  


String



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| id| <br><br>String 消息编号<br><br>
| message| <br><br>String? 备用消息<br><br>
| name| <br><br>String 当前校验字段<br><br>
| parameters| <br><br>Map<String, String>? 附加数据<br><br>
| simplify| <br><br>Boolean 是否简化<br><br>
  
  
Content  
fun [translate](translate.md)(id: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), message: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, parameters: [Map](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)<[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?>?, simplify: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  


[jvm]  
Brief description  


本地化消息



#### Return  


String



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| data| <br><br>Data<br><br>
  
  
Content  
fun [translate](translate.md)(data: [Localizer.Data](-data/index.md)): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  



