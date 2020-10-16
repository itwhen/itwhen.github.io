---
title: virtual -
---
//[echo](../../../index.md)/[tech.whence.echo.dal.schema.key](../../index.md)/[Key](../index.md)/[Companion](index.md)/[virtual](virtual.md)



# virtual  
[jvm]  
Brief description  


根据指定类型及指定字段信息创建虚拟键



#### Return  


Key



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| declarer| <br><br>KClass<*> 所在类<br><br>
| name| <br><br>String 名称<br><br>
| type| <br><br>KClass<*> 自身类型<br><br>
  
  
Content  
@[JvmStatic](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-static/index.html)()  
  
fun [virtual](virtual.md)(name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), declarer: [KClass](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-class/index.html)<out [Entity](../../../tech.whence.echo.dal.entity/-entity/index.md)>, type: [KClass](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-class/index.html)<*>): [Key](../index.md)  



