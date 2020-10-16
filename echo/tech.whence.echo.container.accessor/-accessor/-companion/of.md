---
title: of -
---
//[echo](../../../index.md)/[tech.whence.echo.container.accessor](../../index.md)/[Accessor](../index.md)/[Companion](index.md)/[of](of.md)



# of  
[jvm]  
Brief description  




基于对象构造



若实现了 Readable 接口 直接调用之 将获取指定对象所有属性值 包含私有的 不包含静态值





#### Return  


Accessor



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| data| <br><br>Any? 指定值<br><br>
| fixer| <br><br>PropertyFixer? 属性纠正器<br><br>
| originate| <br><br>Boolean 是否直接读取原始属性<br><br>
  
  
Content  
@[JvmStatic](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-static/index.html)()  
@[JvmOverloads](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-overloads/index.html)()  
  
fun [of](of.md)(data: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?, originate: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), fixer: [PropertyFixer](../../../tech.whence.echo.type/index.md#tech.whence.echo.type/PropertyFixer///PointingToDeclaration/)?): [Accessor](../index.md)  



