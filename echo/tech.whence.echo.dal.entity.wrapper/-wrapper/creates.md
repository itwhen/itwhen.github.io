---
title: creates -
---
//[echo](../../index.md)/[tech.whence.echo.dal.entity.wrapper](../index.md)/[Wrapper](index.md)/[creates](creates.md)



# creates  
[jvm]  
Brief description  


判断是否生成了指定实体类型



#### Return  


Boolean



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| declarer| <br><br>KClass<out Entity> 指定实体类型<br><br>
  
  
Content  
abstract fun [creates](creates.md)(declarer: [KClass](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-class/index.html)<out [Entity](../../tech.whence.echo.dal.entity/-entity/index.md)>): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  


[jvm]  
Brief description  


判断是否生成并管理指定字段



#### Return  


Boolean



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| key| <br><br>String 字段名<br><br>
  
  
Content  
abstract fun [creates](creates.md)(key: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  



