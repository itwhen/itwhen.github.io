---
title: of -
---
//[echo](../../../index.md)/[tech.whence.echo.webclient.request](../../index.md)/[Request](../index.md)/[Companion](index.md)/[of](of.md)



# of  
[jvm]  
Brief description  


静态构造



#### Return  


Request<A>



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| action| <br><br>A 行为<br><br>
| method| <br><br>Method 方法<br><br>
| parameterizer| <br><br>RequestParameterizer? 请求数据回调<br><br>
| query| <br><br>Accessor? 查询数据<br><br>
  
  
Content  
@[JvmStatic](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-static/index.html)()  
@[JvmOverloads](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-overloads/index.html)()  
  
fun <[A](of.md) : [Actable](../../../tech.whence.echo.webclient/-actable/index.md)> [of](of.md)(action: [A](of.md), method: [Request.Method](../-method/index.md), query: [Accessor](../../../tech.whence.echo.container.accessor/-accessor/index.md)?, parameterizer: [RequestParameterizer](../../-request-parameterizer/index.md)?): [Request](../index.md)<[A](of.md)>  



