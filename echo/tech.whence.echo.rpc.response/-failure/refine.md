---
title: refine -
---
//[echo](../../index.md)/[tech.whence.echo.rpc.response](../index.md)/[Failure](index.md)/[refine](refine.md)



# refine  
[jvm]  
Brief description  


完善消息



#### Return  


Failure



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| message| <br><br>String 最新消息<br><br>
| override| <br><br>Boolean 是否覆盖原消息 为假时原消息将附加在最新消息之后<br><br>
  
  
Content  
@[JvmOverloads](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-overloads/index.html)()  
  
fun [refine](refine.md)(message: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), override: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)): [Failure](index.md)  


[jvm]  
Brief description  


完善错误



#### Return  


Failure



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| code| <br><br>String 最新错误编码<br><br>
| message| <br><br>String 最新错误消息<br><br>
| override| <br><br>Boolean 是否覆盖原错误 为假时原错误将附加在最新错误之后<br><br>
  
  
Content  
@[JvmOverloads](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-overloads/index.html)()  
  
fun [refine](refine.md)(code: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), message: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), override: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)): [Failure](index.md)  


[jvm]  
Brief description  


完善错误



#### Return  


Failure



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| failure| <br><br>Failure 最新错误<br><br>
| override| <br><br>Boolean 是否覆盖原错误 为假时原错误将附加在最新错误之后<br><br>
  
  
Content  
@[JvmOverloads](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-overloads/index.html)()  
  
fun [refine](refine.md)(failure: [Failure](index.md), override: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)): [Failure](index.md)  



