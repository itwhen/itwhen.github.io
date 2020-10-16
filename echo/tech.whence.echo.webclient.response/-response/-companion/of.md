---
title: of -
---
//[echo](../../../index.md)/[tech.whence.echo.webclient.response](../../index.md)/[Response](../index.md)/[Companion](index.md)/[of](of.md)



# of  
[jvm]  
Brief description  


基于HttpResponse构造



#### Return  


Response



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| response| <br><br>HttpResponse<*><br><br>
  
  
Content  
@[JvmStatic](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-static/index.html)()  
  
fun [of](of.md)(response: HttpResponse<*>): [Response](../index.md)  


[jvm]  
Brief description  


构造



#### Return  


Response



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| content| <br><br>String? 内容<br><br>
| exception| <br><br>ResponseException? 异常<br><br>
| headers| <br><br>MultiMap? 响应头<br><br>
| status| <br><br>Int 状态码<br><br>
  
  
Content  
@[JvmStatic](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-static/index.html)()  
@[JvmOverloads](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-overloads/index.html)()  
  
fun [of](of.md)(status: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), headers: MultiMap?, content: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, exception: [ResponseException](../../../tech.whence.echo.webclient.response.exception/-response-exception/index.md)?): [Response](../index.md)  



