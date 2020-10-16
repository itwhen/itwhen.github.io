---
title: fail -
---
//[echo](../../../index.md)/[tech.whence.echo.rpc.response](../../index.md)/[Failure](../index.md)/[Companion](index.md)/[fail](fail.md)



# fail  
[jvm]  
Brief description  


业务失败



#### Return  


Failure



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| code| <br><br>String 编码<br><br>
| message| <br><br>String 消息<br><br>
  
  
Content  
@[JvmStatic](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-static/index.html)()  
  
fun [fail](fail.md)(code: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), message: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): [Failure](../index.md)  


[jvm]  
Brief description  


业务失败



#### Return  


Failure



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| code| <br><br>String 编码<br><br>
| messager| <br><br>Producer<Localizer.Data> 消息格式生成<br><br>
  
  
Content  
@[JvmStatic](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-static/index.html)()  
  
fun [fail](fail.md)(code: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), messager: [Producer](../../../tech.whence.echo.function/-producer/index.md)<[Localizer.Data](../../../tech.whence.echo.support/-localizer/-data/index.md)>): [Failure](../index.md)  


[jvm]  
Brief description  


常规失败 将自动本地化消息



#### Return  


Failure



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| cause| <br><br>Throwable? 缘由<br><br>
| message| <br><br>String? 额外消息<br><br>
| name| <br><br>String? 名称<br><br>
| parameters| <br><br>Map<String, String>? 本地化数据<br><br>
| reason| <br><br>Reason 原因<br><br>
  
  
Content  
@[JvmStatic](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-static/index.html)()  
@[JvmOverloads](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-overloads/index.html)()  
  
fun [fail](fail.md)(reason: [Reason](../../-reason/index.md), message: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, parameters: [Map](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)<[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?>?, cause: [Throwable](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-throwable/index.html)?): [Failure](../index.md)  


[jvm]  
Brief description  


异常



#### Return  


Failure



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| exception| <br><br>ResponseException<br><br>
  
  
Content  
@[JvmStatic](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-static/index.html)()  
  
fun [fail](fail.md)(exception: [ResponseException](../../../tech.whence.echo.rpc.exception/-response-exception/index.md)): [Failure](../index.md)  


[jvm]  
Brief description  


异常



#### Return  


Failure



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| cause| <br><br>Throwable<br><br>
  
  
Content  
@[JvmStatic](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-static/index.html)()  
  
fun [fail](fail.md)(cause: [Throwable](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-throwable/index.html)): [Failure](../index.md)  



