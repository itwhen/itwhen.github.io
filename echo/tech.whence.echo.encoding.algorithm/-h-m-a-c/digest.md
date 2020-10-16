---
title: digest -
---
//[echo](../../index.md)/[tech.whence.echo.encoding.algorithm](../index.md)/[HMAC](index.md)/[digest](digest.md)



# digest  
[jvm]  
Brief description  


取摘要



#### Return  


ByteArray



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| algorithm| <br><br>Algorithm 指定算法<br><br>
| data| <br><br>ByteArray 数据<br><br>
| key| <br><br>ByteArray 密钥<br><br>
| salt| <br><br>ByteArray? 盐<br><br>
  
  
Content  
@[JvmOverloads](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-overloads/index.html)()  
  
fun [digest](digest.md)(algorithm: [HMAC.Algorithm](-algorithm/index.md), data: [ByteArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte-array/index.html), key: [ByteArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte-array/index.html), salt: [ByteArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte-array/index.html)?): [ByteArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte-array/index.html)  


[jvm]  
Brief description  


取摘要



#### Return  


String



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| algorithm| <br><br>Algorithm 指定算法<br><br>
| data| <br><br>String 数据<br><br>
| encoder| <br><br>Encoder 编码器<br><br>
| key| <br><br>String 密钥字符串<br><br>
| keygen| <br><br>Keygen 密钥生成<br><br>
| salt| <br><br>String? 盐<br><br>
  
  
Content  
@[JvmOverloads](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-overloads/index.html)()  
  
fun [digest](digest.md)(algorithm: [HMAC.Algorithm](-algorithm/index.md), data: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), key: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), salt: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, keygen: [Keygen](../../tech.whence.echo.encoding/-keygen/index.md), encoder: [Encoder](../../tech.whence.echo.encoding/-encoder/index.md)): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  



