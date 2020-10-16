---
title: present -
---
//[echo](../../index.md)/[tech.whence.echo.container.accessor](../index.md)/[Accessor](index.md)/[present](present.md)



# present  
[jvm]  
Brief description  


判断指定键的值存在 若值为空返回假 若此时值是字符串且处于TrimString模式且该值前后去空后为空时被认为不存在 其他返回真



#### Return  


Boolean



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| key| <br><br>String 指定键<br><br>
  
  
Content  
fun [present](present.md)(key: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  


[jvm]  
Brief description  


判断多个键的值是否同时存在



#### Return  


Boolean



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| keys| <br><br>Array<out String> 指定键<br><br>
  
  
Content  
fun [present](present.md)(vararg keys: [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<out [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)>): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  



