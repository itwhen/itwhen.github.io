---
title: register -
---
//[echo](../../index.md)/[tech.whence.echo.codec](../index.md)/[Codecs](index.md)/[register](register.md)



# register  
[jvm]  
Brief description  


注册解编器 根据解编器身份自动设置



#### Return  


Codecs



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| codecs| <br><br>Array<out Codec> 解编器<br><br>
  
  
Content  
fun [register](register.md)(vararg codecs: [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<out [Codec](../-codec/index.md)>): [Codecs](index.md)  


[jvm]  
Brief description  


注册解编器类



#### Return  


Codecs



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| codec| <br><br>KClass<out Codec> 解编器类型<br><br>
  
  
Content  
fun [register](register.md)(codec: [KClass](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-class/index.html)<out [Codec](../-codec/index.md)>): [Codecs](index.md)  


[jvm]  
Brief description  


注册解码器 将解码器转换为解码器再注册



#### Return  


Codecs



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| decoder| <br><br>Conversion<T, *> 解码器<br><br>
  
  
Content  
inline fun <[T](register.md)> [register](register.md)(decoder: [Decoder](../-decoder/index.md)<[T](register.md), *>): [Codecs](index.md)  



