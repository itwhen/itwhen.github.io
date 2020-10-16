---
title: transfer -
---
//[echo](../../index.md)/[tech.whence.echo.container.constant](../index.md)/[Data](index.md)/[transfer](transfer.md)



# transfer  
[jvm]  
Brief description  


将常量的多个值映射到另一常量

  
Content  
inline fun <[TC](transfer.md) : [Enum](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-enum/index.html)<[TC](transfer.md)>, [Const](../-const/index.md)<[V](index.md)>> [transfer](transfer.md)(vararg sources: [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<out [C](index.md)>): [Data](index.md)<[V](index.md), [TC](transfer.md)>  


[jvm]  
Brief description  


根据回调将常量的值映射到另一常量

  
Content  
inline fun <[TC](transfer.md) : [Enum](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-enum/index.html)<[TC](transfer.md)>, [Const](../-const/index.md)<[V](index.md)>> [transfer](transfer.md)(predicate: [Predicate](../../tech.whence.echo.function/-predicate/index.md)<[V](index.md)>?): [Data](index.md)<[V](index.md), [TC](transfer.md)>  



