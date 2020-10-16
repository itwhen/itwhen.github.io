---
title: sourced -
---
//[echo](../../../index.md)/[tech.whence.echo.support.kafka.stream.initializer](../../index.md)/[Initializer](../index.md)/[Companion](index.md)/[sourced](sourced.md)



# sourced  
[jvm]  
Brief description  


构造



#### Return  


SourcedInitializer<V>



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| factory| <br><br>Factory<V> 处理器工厂<br><br>
| serde| <br><br>Serde<Accessor> 序列反序列化器<br><br>
  
  
Content  
@[JvmStatic](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-static/index.html)()  
  
fun <[V](sourced.md)> [sourced](sourced.md)(factory: [Factory](../../../tech.whence.echo.support.kafka.stream.processor/-factory/index.md)<[V](sourced.md)>, serde: Serde<[Accessor](../../../tech.whence.echo.container.accessor/-accessor/index.md)>): [SourcedInitializer](../../-sourced-initializer/index.md)<[V](sourced.md)>  


[jvm]  
Brief description  


构造



#### Return  


SourcedInitializer<Accessor>



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| factory| <br><br>Factory<V> 处理器工厂<br><br>
  
  
Content  
@[JvmStatic](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-static/index.html)()  
  
fun [sourced](sourced.md)(factory: [Factory](../../../tech.whence.echo.support.kafka.stream.processor/-factory/index.md)<[Accessor](../../../tech.whence.echo.container.accessor/-accessor/index.md)>): [SourcedInitializer](../../-sourced-initializer/index.md)<[Accessor](../../../tech.whence.echo.container.accessor/-accessor/index.md)>  



