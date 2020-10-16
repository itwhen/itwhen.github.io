---
title: build -
---
//[echo](../../../index.md)/[tech.whence.echo.support](../../index.md)/[Environment](../index.md)/[Companion](index.md)/[build](build.md)



# build  
[jvm]  
Brief description  


根据环境变量及生产者生成映射



#### Return  


EnumMap<Environment, E>



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| transformer| <br><br>Transformer<Environment, E><br><br>
  
  
Content  
@[JvmStatic](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-static/index.html)()  
  
fun <[E](build.md)> [build](build.md)(transformer: [Transformer](../../../tech.whence.echo.function/-transformer/index.md)<[Environment](../index.md), [E](build.md)>): [EnumMap](https://docs.oracle.com/javase/8/docs/api/java/util/EnumMap.html)<[Environment](../index.md), [E](build.md)>  



