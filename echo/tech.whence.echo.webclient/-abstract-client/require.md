---
title: require -
---
//[echo](../../index.md)/[tech.whence.echo.webclient](../index.md)/[AbstractClient](index.md)/[require](require.md)



# require  
[jvm]  
Brief description  


设置结果类型要求



#### Return  


ConfigBuilder<C, A, R>



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| klass| <br><br>KClass<R> 指定类<br><br>
  
  
Content  
fun <[R](require.md) : [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)> [require](require.md)(klass: [KClass](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-class/index.html)<[R](require.md)>): [ConfigBuilder](../-config-builder/index.md)<[C](index.md), [A](index.md), [R](require.md)>  


[jvm]  
Brief description  


设置结果类型要求



#### Return  


ConfigBuilder<C, A, R>

  
Content  
inline fun <[R](require.md) : [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)> [require](require.md)(): [ConfigBuilder](../-config-builder/index.md)<[C](index.md), [A](index.md), [R](require.md)>  


[jvm]  
Brief description  


设置结果类型要求



#### Return  


ConfigBuilder<C, A, R>



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| clazz| <br><br>Class<R> 指定类<br><br>
  
  
Content  
fun <[R](require.md) : [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)> [require](require.md)(clazz: [Class](https://docs.oracle.com/javase/8/docs/api/java/lang/Class.html)<[R](require.md)>): [ConfigBuilder](../-config-builder/index.md)<[C](index.md), [A](index.md), [R](require.md)>  



