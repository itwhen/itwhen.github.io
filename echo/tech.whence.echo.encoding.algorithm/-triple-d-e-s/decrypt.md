---
title: decrypt -
---
//[echo](../../index.md)/[tech.whence.echo.encoding.algorithm](../index.md)/[TripleDES](index.md)/[decrypt](decrypt.md)



# decrypt  
[jvm]  
Brief description  


解密



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
  
fun [decrypt](decrypt.md)(data: [ByteArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte-array/index.html), key: [ByteArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte-array/index.html), iv: [ByteArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte-array/index.html)?): [ByteArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte-array/index.html)  


[jvm]  
Brief description  


解密



#### Return  


String



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| data| <br><br>String 指定数据<br><br>
| decoder| <br><br>Decoder 解码器<br><br>
| key| <br><br>String 密钥字符串<br><br>
| keygen| <br><br>Keygen 密钥生成<br><br>
  
  
Content  
fun [decrypt](decrypt.md)(data: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), key: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), keygen: [Keygen](../../tech.whence.echo.encoding/-keygen/index.md), decoder: [Decoder](../../tech.whence.echo.encoding/-decoder/index.md)): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  



