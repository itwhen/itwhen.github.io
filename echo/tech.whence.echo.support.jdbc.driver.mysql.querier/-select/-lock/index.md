---
title: Lock -
---
//[echo](../../../index.md)/[tech.whence.echo.support.jdbc.driver.mysql.querier](../../index.md)/[Select](../index.md)/[Lock](index.md)



# Lock  
 [jvm] 

锁方式

sealed class [Lock](index.md)   


## Types  
  
|  Name|  Summary| 
|---|---|
| [ForShare](-for-share/index.md)| [jvm]  <br>Brief description  <br><br><br>共享锁<br><br>  <br>Content  <br>object [ForShare](-for-share/index.md) : [Select.Lock](index.md)  <br><br><br>
| [ForShareNoWait](-for-share-no-wait/index.md)| [jvm]  <br>Brief description  <br><br><br>共享锁 若无法获取到锁时直接返回错误<br><br>  <br>Content  <br>object [ForShareNoWait](-for-share-no-wait/index.md) : [Select.Lock](index.md)  <br><br><br>
| [ForShareSkipLocked](-for-share-skip-locked/index.md)| [jvm]  <br>Brief description  <br><br><br>共享锁 忽略被其他锁定的记录<br><br>  <br>Content  <br>object [ForShareSkipLocked](-for-share-skip-locked/index.md) : [Select.Lock](index.md)  <br><br><br>
| [ForUpdate](-for-update/index.md)| [jvm]  <br>Brief description  <br><br><br>排他锁<br><br>  <br>Content  <br>object [ForUpdate](-for-update/index.md) : [Select.Lock](index.md)  <br><br><br>
| [ForUpdateNoWait](-for-update-no-wait/index.md)| [jvm]  <br>Brief description  <br><br><br>排他锁 若无法获取到锁时直接返回错误<br><br>  <br>Content  <br>object [ForUpdateNoWait](-for-update-no-wait/index.md) : [Select.Lock](index.md)  <br><br><br>
| [ForUpdateSkipLocked](-for-update-skip-locked/index.md)| [jvm]  <br>Brief description  <br><br><br>排他锁 忽略被其他锁定的记录<br><br>  <br>Content  <br>object [ForUpdateSkipLocked](-for-update-skip-locked/index.md) : [Select.Lock](index.md)  <br><br><br>


## Functions  
  
|  Name|  Summary| 
|---|---|
| [equals](../../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)| [jvm]  <br>Content  <br>open operator override fun [equals](../../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [hashCode](../../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [hashCode](../../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [toString](../../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [toString](../../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>


## Properties  
  
|  Name|  Summary| 
|---|---|
| [text](index.md#tech.whence.echo.support.jdbc.driver.mysql.querier/Select.Lock/text/#/PointingToDeclaration/)|  [jvm] <br><br>String 语句文本<br><br>val [text](index.md#tech.whence.echo.support.jdbc.driver.mysql.querier/Select.Lock/text/#/PointingToDeclaration/): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)   <br>


## Inheritors  
  
|  Name| 
|---|
| [Select.Lock](-for-update/index.md)
| [Select.Lock](-for-update-no-wait/index.md)
| [Select.Lock](-for-update-skip-locked/index.md)
| [Select.Lock](-for-share/index.md)
| [Select.Lock](-for-share-no-wait/index.md)
| [Select.Lock](-for-share-skip-locked/index.md)

