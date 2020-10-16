---
title: validate -
---
//[echo](../../index.md)/[tech.whence.echo.validation](../index.md)/[Validator](index.md)/[validate](validate.md)



# validate  
[jvm]  
Brief description  


校验 遍历所有规则执行校验返回校验结果



#### Return  


Boolean



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| data| <br><br>Accessor 指定数据<br><br>
| failfast| <br><br>Boolean 是否快速失败 若为真时有任一规则校验失败则返回<br><br>
  
  
Content  
@[JvmOverloads](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-overloads/index.html)()  
  
fun [validate](validate.md)(data: [Accessor](../../tech.whence.echo.container.accessor/-accessor/index.md), failfast: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)): [Errors](../-errors/index.md)  



