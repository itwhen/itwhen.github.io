---
title: success -
---
//[echo](../../../index.md)/[tech.whence.echo.job.shell](../../index.md)/[Responder](../index.md)/[Companion](index.md)/[success](success.md)



# success  
[jvm]  
Brief description  


空响应



#### Return  


Responder

  
Content  
@[JvmStatic](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-static/index.html)()  
  
fun [success](success.md)(): [Responder](../index.md)  


[jvm]  
Brief description  


响应



#### Return  


Responder



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| message| <br><br>String 消息<br><br>
  
  
Content  
@[JvmStatic](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-static/index.html)()  
  
fun [success](success.md)(message: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): [Responder](../index.md)  


[jvm]  
Brief description  


列表格式响应



#### Return  


Responder



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| extra| <br><br>Collection<*> 附加数据<br><br>
| message| <br><br>String 消息<br><br>
  
  
Content  
@[JvmStatic](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-static/index.html)()  
  
fun [success](success.md)(message: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), extra: [Collection](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-collection/index.html)<*>): [Responder](../index.md)  


[jvm]  
Brief description  


表格格式响应



#### Return  


Responder



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| extra| <br><br>Map<String, Any> 附加数据<br><br>
| message| <br><br>String 消息<br><br>
  
  
Content  
@[JvmStatic](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-static/index.html)()  
  
fun [success](success.md)(message: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), extra: [Map](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)<[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>): [Responder](../index.md)  


[jvm]  
Brief description  


表格格式响应



#### Return  


Responder



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| extra| <br><br>Table<*, *, *> 附加数据<br><br>
| message| <br><br>String 消息<br><br>
  
  
Content  
@[JvmStatic](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-static/index.html)()  
  
fun [success](success.md)(message: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), extra: Table<*, *, *>): [Responder](../index.md)  



