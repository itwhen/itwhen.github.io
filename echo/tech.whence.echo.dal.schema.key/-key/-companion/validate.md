---
title: validate -
---
//[echo](../../../index.md)/[tech.whence.echo.dal.schema.key](../../index.md)/[Key](../index.md)/[Companion](index.md)/[validate](validate.md)



# validate  
[jvm]  
Brief description  


校验字段属性 若指定实体是动态的则置空 否则若是虚拟字段也置空 其他返回自身



#### Return  


KProperty<*>?



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| declarer| <br><br>KClass<out Entity> 指定实体类型<br><br>
| name| <br><br>String 指定字段名<br><br>
| property| <br><br>KProperty<*>? 指定字段属性<br><br>
  
  
Content  
fun [validate](validate.md)(name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), property: [KProperty](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-property/index.html)<*>?, declarer: [KClass](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-class/index.html)<out [Entity](../../../tech.whence.echo.dal.entity/-entity/index.md)>): [KProperty](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-property/index.html)<*>?  


[jvm]  
Brief description  


判断指定字段名称是否合法



#### Return  


Validated



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| key| <br><br>CharSequence? 指定字段名称<br><br>
  
  
Content  
@[JvmStatic](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-static/index.html)()  
  
fun [validate](validate.md)(key: [CharSequence](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-char-sequence/index.html)?): [ValidatedKey](../../-validated-key/index.md)  



