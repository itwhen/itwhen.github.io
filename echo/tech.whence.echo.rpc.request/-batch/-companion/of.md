---
title: of -
---
//[echo](../../../index.md)/[tech.whence.echo.rpc.request](../../index.md)/[Batch](../index.md)/[Companion](index.md)/[of](of.md)



# of  
[jvm]  
Brief description  


构造 若指定有效key时直接寻找 否则先找批次[Batch](../index.md)字段再找[Id](../../-id/index.md)字段



#### Return  


Batch



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| delimiter| <br><br>String 指定分隔符<br><br>
| key| <br><br>String? 指定字段<br><br>
| request| <br><br>OperationRequest 指定请求<br><br>
  
  
Content  
@[JvmStatic](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-static/index.html)()  
@[JvmOverloads](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-overloads/index.html)()  
  
fun [of](of.md)(request: OperationRequest, key: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, delimiter: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): [Batch](../index.md)  



