---
title: locate -
---
//[echo](../../index.md)/[tech.whence.echo.rpc](../index.md)/[Deployer](index.md)/[locate](locate.md)



# locate  
[jvm]  
Brief description  


根据类定位



#### Return  


Runner



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| declarer| <br><br>KClass<*> 指定类<br><br>
  
  
Content  
fun [locate](locate.md)(declarer: [KClass](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-class/index.html)<*>): [Deployer](index.md)  


[jvm]  
Brief description  


根据目录与类定位



#### Return  


Runner



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| declarer| <br><br>KClass<*> 指定类<br><br>
| dir| <br><br>String 指定目录<br><br>
  
  
Content  
fun [locate](locate.md)(dir: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), declarer: [KClass](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-class/index.html)<*>): [Deployer](index.md)  


[jvm]  
Brief description  


根据文件定位



#### Return  


Runner



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| file| <br><br>File 指定文件<br><br>
| prefix| <br><br>String 前缀<br><br>
  
  
Content  
fun [locate](locate.md)(prefix: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), file: [File](https://docs.oracle.com/javase/8/docs/api/java/io/File.html)): [Deployer](index.md)  


[jvm]  
Brief description  


定位



#### Return  


Runner



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| dir| <br><br>String 指定目录<br><br>
| id| <br><br>String 指定编号<br><br>
  
  
Content  
fun [locate](locate.md)(dir: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), id: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): [Deployer](index.md)  



