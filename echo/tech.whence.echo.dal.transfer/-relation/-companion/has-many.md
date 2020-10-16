---
title: hasMany -
---
//[echo](../../../index.md)/[tech.whence.echo.dal.transfer](../../index.md)/[Relation](../index.md)/[Companion](index.md)/[hasMany](has-many.md)



# hasMany  
[jvm]  
Brief description  


没有或有多个



#### Return  


Relation



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| baseKey| <br><br>String 本地字段<br><br>
| condition| <br><br>Condition 条件<br><br>
| target| <br><br>Setting 目标设置<br><br>
| targetKey| <br><br>String 目标字段<br><br>
  
  
Content  
@[JvmStatic](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-static/index.html)()  
  
fun [hasMany](has-many.md)(target: [Setting](../../../tech.whence.echo.dal.transfer.project/-setting/index.md), baseKey: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), targetKey: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), condition: [Relation.Condition](../-condition/index.md)): [Relation](../index.md)  


[jvm]  
Brief description  


没有或有多个



#### Return  


Relation



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| column| <br><br>String 字段<br><br>
| condition| <br><br>Condition 条件<br><br>
| target| <br><br>Setting 目标设置<br><br>
  
  
Content  
@[JvmStatic](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-static/index.html)()  
  
fun [hasMany](has-many.md)(target: [Setting](../../../tech.whence.echo.dal.transfer.project/-setting/index.md), column: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), condition: [Relation.Condition](../-condition/index.md)): [Relation](../index.md)  



