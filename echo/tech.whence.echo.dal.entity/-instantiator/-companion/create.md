---
title: create -
---
//[echo](../../../index.md)/[tech.whence.echo.dal.entity](../../index.md)/[Instantiator](../index.md)/[Companion](index.md)/[create](create.md)



# create  
[jvm]  
Brief description  


根据静态实体类构建



#### Return  


Creator<D, E>



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| declarer| <br><br>KClass<E> 指定实体类型<br><br>
| handler| <br><br>Transformer<D, E> 转换器<br><br>
  
  
Content  
@[JvmStatic](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-static/index.html)()  
  
fun <[D](create.md), [E](create.md) : [Entity](../../-entity/index.md)> [create](create.md)(declarer: [KClass](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-class/index.html)<[E](create.md)>, handler: [Transformer](../../../tech.whence.echo.function/-transformer/index.md)<[D](create.md), [E](create.md)>): [Instantiator](../index.md)<[D](create.md), [E](create.md)>  



