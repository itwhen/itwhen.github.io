---
title: requiredUnless -
---
//[echo](../../index.md)/[tech.whence.echo.validation](../index.md)/[Ruler](index.md)/[requiredUnless](required-unless.md)



# requiredUnless  
[jvm]  
Brief description  


当另外一个属性没有提供特定值时当前属性必填



#### Return  


Ruler



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| scope| <br><br>Array<out Any> 特定值范围<br><br>
| target| <br><br>String 目标属性<br><br>
  
  
Content  
fun [requiredUnless](required-unless.md)(target: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), vararg scope: [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>): [Ruler](index.md)  


[jvm]  
Brief description  


当另外一个属性没有提供特定值时当前属性必填



#### Return  


Ruler



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| scope| <br><br>Set<Any> 特定值范围<br><br>
| target| <br><br>String 目标属性<br><br>
  
  
Content  
fun [requiredUnless](required-unless.md)(target: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), scope: [Set](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-set/index.html)<[Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>): [Ruler](index.md)  



