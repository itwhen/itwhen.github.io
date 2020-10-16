---
title: encrypt -
---
//[echo](../../index.md)/[tech.whence.echo.encoding.algorithm](../index.md)/[TripleDES](index.md)/[encrypt](encrypt.md)



# encrypt  
[jvm]  
Brief description  


加密



#### Return  


ByteArray



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| data| <br><br>ByteArray 指定数据<br><br>
| iv| <br><br>ByteArray? 初始化向量<br><br>
| key| <br><br>ByteArray 密钥<br><br>
  
  
Content  
@[JvmOverloads](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-overloads/index.html)()  
  
fun [encrypt](encrypt.md)(data: [ByteArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte-array/index.html), key: [ByteArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte-array/index.html), iv: [ByteArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte-array/index.html)?): [ByteArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte-array/index.html)  


[jvm]  
Brief description  


加密



#### Return  


String



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| data| <br><br>String 指定数据<br><br>
| encoder| <br><br>Encoder 编码器<br><br>
| key| <br><br>String 密钥字符串<br><br>
| keygen| <br><br>Keygen 密钥生成<br><br>
  
  
Content  
fun [encrypt](encrypt.md)(data: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), key: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), keygen: [Keygen](../../tech.whence.echo.encoding/-keygen/index.md), encoder: [Encoder](../../tech.whence.echo.encoding/-encoder/index.md)): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  



