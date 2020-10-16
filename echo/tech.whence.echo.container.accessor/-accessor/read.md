---
title: read -
---
//[echo](../../index.md)/[tech.whence.echo.container.accessor](../index.md)/[Accessor](index.md)/[read](read.md)



# read  
[jvm]  
Brief description  


获取指定键的值 并记录



#### Return  


Any?



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| key| <br><br>String 指定键<br><br>
  
  
Content  
open override fun [read](read.md)(key: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): [Reply](../../tech.whence.echo.container/-reply/index.md)<[Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>  


[jvm]  
Brief description  


获取指定键的值 执行下一步并记录异常



#### Return  


T?



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| key| <br><br>String 指定键<br><br>
| next| <br><br>Transformer<Any?, T?> 取值成功后执行下一步<br><br>
  
  
Content  
open override fun <[T](read.md) : [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)> [read](read.md)(key: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), next: [Transformer](../../tech.whence.echo.function/-transformer/index.md)<[Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html), [T](read.md)?>): [Reply](../../tech.whence.echo.container/-reply/index.md)<[T](read.md)>  



