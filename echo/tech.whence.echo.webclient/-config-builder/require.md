---
title: require -
---
//[echo](../../index.md)/[tech.whence.echo.webclient](../index.md)/[ConfigBuilder](index.md)/[require](require.md)



# require  
[jvm]  
Brief description  


设置结果类型



#### Return  


ConfigBuilder<C, A, R>



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| resultType| <br><br>ResultType<R> 指定结果类型<br><br>
  
  
Content  
fun [require](require.md)(resultType: [ResultType](../-result-type/index.md)<[R](index.md)>): [ConfigBuilder](index.md)<[C](index.md), [A](index.md), [R](index.md)>  


[jvm]  
Brief description  


设置结果类



#### Return  


ConfigBuilder<C, A, R>



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| resultClass| <br><br>KClass<R> 指定类<br><br>
  
  
Content  
fun [require](require.md)(resultClass: [KClass](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-class/index.html)<[R](index.md)>): [ConfigBuilder](index.md)<[C](index.md), [A](index.md), [R](index.md)>  



