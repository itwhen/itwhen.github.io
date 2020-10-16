---
title: of -
---
//[echo](../../../index.md)/[tech.whence.echo.dal.schema.key](../../index.md)/[Key](../index.md)/[Companion](index.md)/[of](of.md)



# of  
[jvm]  
Brief description  


创建字段



#### Return  


Key



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| annotations| <br><br>List<Annotation>? 相关属性注解集合<br><br>
| declarer| <br><br>KClass<*> 所在类<br><br>
| existence| <br><br>Existence 存在方式<br><br>
| name| <br><br>String 名称<br><br>
| property| <br><br>KProperty<*>? 相应属性<br><br>
| type| <br><br>KClass<*> 自身类型<br><br>
| watcher| <br><br>Watcher? 观察者<br><br>
  
  
Content  
@[JvmStatic](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-static/index.html)()  
@[JvmOverloads](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-overloads/index.html)()  
  
fun [of](of.md)(name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), declarer: [KClass](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-class/index.html)<out [Entity](../../../tech.whence.echo.dal.entity/-entity/index.md)>, type: [KClass](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-class/index.html)<*>, existence: [Existence](../../-existence/index.md), property: [KProperty](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-property/index.html)<*>?, annotations: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[Annotation](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-annotation/index.html)>?, watcher: [Watcher](../../-watcher/index.md)?): [Key](../index.md)  



