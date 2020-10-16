---
title: getSequence -
---
//[echo](../../index.md)/[tech.whence.echo.container](../index.md)/[Accessibility](index.md)/[getSequence](get-sequence.md)



# getSequence  
[jvm]  
Brief description  


取序列



#### Return  


Result<Sequence<T>>



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| forcible| <br><br>Boolean 是否强转<br><br>
| key| <br><br>K 指定键<br><br>
| transformer| <br><br>Transformer<Any?, T?> 值准换<br><br>
  
  
Content  
open fun <[T](get-sequence.md) : [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)> [getSequence](get-sequence.md)(key: [K](index.md), forcible: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), transformer: [Transformer](../../tech.whence.echo.function/-transformer/index.md)<[Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?, [T](get-sequence.md)?>): [Reply](../-reply/index.md)<[Sequence](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.sequences/-sequence/index.html)<[T](get-sequence.md)>>  



