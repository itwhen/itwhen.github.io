---
title: of -
---
//[echo](../../../index.md)/[tech.whence.echo.dal.schema.key](../../index.md)/[Keys](../index.md)/[Companion](index.md)/[of](of.md)



# of  
[jvm]  
Brief description  


根据指定实体类型与字段列表构造



#### Return  


Keys



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| declarer| <br><br>KClass<out Entity> 实体类型<br><br>
| keys| <br><br>Iterable<Key> 字段列表<br><br>
| renew| <br><br>Boolean 是否刷新字段<br><br>
  
  
Content  
@[JvmStatic](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-static/index.html)()  
@[JvmOverloads](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-overloads/index.html)()  
  
fun [of](of.md)(declarer: [KClass](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-class/index.html)<out [Entity](../../../tech.whence.echo.dal.entity/-entity/index.md)>, keys: [Iterable](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-iterable/index.html)<[Key](../../-key/index.md)>, renew: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)): [Keys](../index.md)  


[jvm]  
Brief description  


根据指定实体类型及字段信息构造



#### Return  


Keys



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| declarer| <br><br>KClass<out Serializable> 实体类型<br><br>
| keys| <br><br>Map<String, Pair<KClass<*>, Key.Existence?>> 字段名及其类型及存在方式<br><br>
  
  
Content  
@[JvmStatic](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-static/index.html)()  
  
fun [of](of.md)(declarer: [KClass](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-class/index.html)<out [Entity](../../../tech.whence.echo.dal.entity/-entity/index.md)>, keys: [Map](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)<[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), [KClass](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-class/index.html)<*>>): [Keys](../index.md)  


[jvm]  
Brief description  


根据指定实体类型属性构造



#### Return  


Keys



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| declarer| <br><br>KClass<out Entity> 实体类型<br><br>
  
  
Content  
@[JvmStatic](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-static/index.html)()  
  
fun [of](of.md)(declarer: [KClass](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-class/index.html)<out [Entity](../../../tech.whence.echo.dal.entity/-entity/index.md)>): [Keys](../index.md)  



