---
title: entitify -
---
//[echo](../../index.md)/[tech.whence.echo.container.accessor](../index.md)/[Accessor](index.md)/[entitify](entitify.md)



# entitify  
[jvm]  
Brief description  


转换为动态实体



#### Return  


DEntity



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| complete| <br><br>Consumer<DEntity>? 属性补全<br><br>
| name| <br><br>String 指定实体名<br><br>
  
  
Content  
fun [entitify](entitify.md)(name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), complete: [Consumer](../../tech.whence.echo.function/-consumer/index.md)<[Record](../../tech.whence.echo.dal.entity/-record/index.md)>?): [Record](../../tech.whence.echo.dal.entity/-record/index.md)  


[jvm]  
Brief description  


转换为静态实体



#### Return  


E



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| complete| <br><br>Consumer<E>? 属性补全<br><br>
| declarer| <br><br>KClass<E> 指定实体类型<br><br>
  
  
Content  
fun <[E](entitify.md) : [Entity](../../tech.whence.echo.dal.entity/-entity/index.md)> [entitify](entitify.md)(declarer: [KClass](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-class/index.html)<[E](entitify.md)>, complete: [Consumer](../../tech.whence.echo.function/-consumer/index.md)<[E](entitify.md)>?): [E](entitify.md)  


[jvm]  
Brief description  


转换为静态实体



#### Return  


E



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| complete| <br><br>Consumer<E>? 属性补全<br><br>
| declarer| <br><br>Class<E> 指定实体类型<br><br>
  
  
Content  
fun <[E](entitify.md) : [Entity](../../tech.whence.echo.dal.entity/-entity/index.md)> [entitify](entitify.md)(declarer: [Class](https://docs.oracle.com/javase/8/docs/api/java/lang/Class.html)<[E](entitify.md)>, complete: [Consumer](../../tech.whence.echo.function/-consumer/index.md)<[E](entitify.md)>?): [E](entitify.md)  


[jvm]  
Brief description  


转换为静态实体



#### Return  


E



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| complete| <br><br>Consumer<E>? 属性补全<br><br>
  
  
Content  
inline fun <[E](entitify.md) : [Entity](../../tech.whence.echo.dal.entity/-entity/index.md)> [entitify](entitify.md)(complete: [Consumer](../../tech.whence.echo.function/-consumer/index.md)<[E](entitify.md)>?): [E](entitify.md)  


[jvm]  
Brief description  


补全实体



#### Return  


E



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| entity| <br><br>E 指定实体<br><br>
  
  
Content  
fun <[E](entitify.md) : [Entity](../../tech.whence.echo.dal.entity/-entity/index.md)> [entitify](entitify.md)(entity: [E](entitify.md)): [E](entitify.md)  



