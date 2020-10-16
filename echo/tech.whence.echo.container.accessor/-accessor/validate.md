---
title: validate -
---
//[echo](../../index.md)/[tech.whence.echo.container.accessor](../index.md)/[Accessor](index.md)/[validate](validate.md)



# validate  
[jvm]  
Brief description  


根据指定条件校验数据



#### Return  


Accessor



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| handler| <br><br>Consumer<Throwable>? 异常处理<br><br>
| validities| <br><br>Array<out Validity> 指定规则<br><br>
  
  
Content  
@[JvmOverloads](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-overloads/index.html)()  
  
fun [validate](validate.md)(vararg validities: [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<out [Validity](../-validity/index.md)>, handler: [Consumer](../../tech.whence.echo.function/-consumer/index.md)<[Throwable](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-throwable/index.html)>?): [Accessor](index.md)  



