---
title: of -
---
//[echo](../../../index.md)/[tech.whence.echo.container.constant](../../index.md)/[Data](../index.md)/[Companion](index.md)/[of](of.md)



# of  
[jvm]  
Brief description  


根据具体化类来构建

  
Content  
inline fun <[C](of.md) : [Enum](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-enum/index.html)<[C](of.md)>, [Const](../../-const/index.md)<[V](of.md)>, [V](of.md) : [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)> [of](of.md)(): [Data](../index.md)<[V](of.md), [C](of.md)>  


[jvm]  
Brief description  


根据指定类来构建 将在幕后检查若非一个有效Enum将返回空

  
Content  
fun <[C](of.md) : [Const](../../-const/index.md)<[V](of.md)>, [V](of.md) : [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)> [of](of.md)(declarer: [KClass](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-class/index.html)<[C](of.md)>): [Data](../index.md)<[V](of.md), [C](of.md)>?  



