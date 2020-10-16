---
title: write -
---
//[echo](../../index.md)/[tech.whence.echo.container.accessor](../index.md)/[Accessor](index.md)/[write](write.md)



# write  
[jvm]  
Brief description  


设置键值 此时将标记键查询路径缓存无效 若值是Accessor/JsonObject/JsonArray等复杂对象时将取其内置数据替换



#### Return  


Accessor



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| key| <br><br>String 指定键<br><br>
| override| <br><br>Boolean 是否直接覆盖<br><br>
| value| <br><br>Any? 指定值<br><br>
  
  
Content  
@[JvmOverloads](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-overloads/index.html)()  
  
fun [write](write.md)(key: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), value: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?, override: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)): [Accessor](index.md)  



