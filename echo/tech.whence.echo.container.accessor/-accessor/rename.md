---
title: rename -
---
//[echo](../../index.md)/[tech.whence.echo.container.accessor](../index.md)/[Accessor](index.md)/[rename](rename.md)



# rename  
[jvm]  
Brief description  


重命名键 若来源键与目标键一直则放弃 若定位到某节点则从节点开始 若来源键不存在则放弃 若目标键存在且不强制覆盖则放弃



#### Return  


Accessor



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| override| <br><br>Boolean 是否强制覆盖<br><br>
| root| <br><br>String? 开始节点<br><br>
| sourceKey| <br><br>String 指定来源键<br><br>
| targetKey| <br><br>String 指定目标键<br><br>
  
  
Content  
@[Synchronized](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-synchronized/index.html)()  
  
fun [rename](rename.md)(sourceKey: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), targetKey: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), root: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, override: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)): [Accessor](index.md)  



