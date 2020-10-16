---
title: wrap -
---
//[echo](../../index.md)/[tech.whence.echo.dal.entity.wrapper](../index.md)/[StaticCglibWrapper](index.md)/[wrap](wrap.md)



# wrap  
[jvm]  
Brief description  


打包



#### Return  


E



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| declarer| <br><br>KClass<out E> 指定实体类型<br><br>
| keys| <br><br>Keys 指定字段集合<br><br>
| valuate| <br><br>Transformer<Key, Any?> 取值<br><br>
  
  
Content  
open override fun <[E](wrap.md) : [Entity](../../tech.whence.echo.dal.entity/-entity/index.md)> [wrap](wrap.md)(name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), declarer: [KClass](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-class/index.html)<out [E](wrap.md)>, keys: [Keys](../../tech.whence.echo.dal.schema.key/-keys/index.md), valuate: [Transformer](../../tech.whence.echo.function/-transformer/index.md)<[Key](../../tech.whence.echo.dal.schema.key/-key/index.md), [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?>): [E](wrap.md)  



