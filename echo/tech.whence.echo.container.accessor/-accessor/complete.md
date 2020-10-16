---
title: complete -
---
//[echo](../../index.md)/[tech.whence.echo.container.accessor](../index.md)/[Accessor](index.md)/[complete](complete.md)



# complete  
[jvm]  
Brief description  


补全指定对象 对象属性可用Locate注解指定到访问器特定键 只有在存在指定键且值有变化时才会触发纠正 最后发现值有变化才写入属性



#### Return  


T



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| fixer| <br><br>PropertyFixer? 属性修正<br><br>
| target| <br><br>T 待修正对象<br><br>
  
  
Content  
@[JvmOverloads](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-overloads/index.html)()  
  
fun <[T](complete.md) : [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)> [complete](complete.md)(target: [T](complete.md), fixer: [PropertyFixer](../../tech.whence.echo.type/index.md#tech.whence.echo.type/PropertyFixer///PointingToDeclaration/)?): [T](complete.md)  



