---
title: pack -
---
//[echo](../../../index.md)/[tech.whence.echo.dal.entity](../../index.md)/[Instantiator](../index.md)/[Companion](index.md)/[pack](pack.md)



# pack  
[jvm]  
Brief description  


构建动态实体相关



#### Return  


Packager<D, E>



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| handler| <br><br>Transformer<D, Accessor> 转换器<br><br>
| keymaker| <br><br>Creator<Keys> 取字段方法<br><br>
| name| <br><br>String 实体名称<br><br>
  
  
Content  
@[JvmStatic](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-static/index.html)()  
  
fun <[D](pack.md), [E](pack.md) : [Entity](../../-entity/index.md)> [pack](pack.md)(name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), keymaker: [Producer](../../../tech.whence.echo.function/-producer/index.md)<[Keys](../../../tech.whence.echo.dal.schema.key/-keys/index.md)>, handler: [Transformer](../../../tech.whence.echo.function/-transformer/index.md)<[D](pack.md), [Accessor](../../../tech.whence.echo.container.accessor/-accessor/index.md)>): [Instantiator](../index.md)<[D](pack.md), [E](pack.md)>  



