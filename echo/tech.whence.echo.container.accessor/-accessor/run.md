---
title: run -
---
//[echo](../../index.md)/[tech.whence.echo.container.accessor](../index.md)/[Accessor](index.md)/[run](run.md)



# run  
[jvm]  
Brief description  


在指定模式下执行 执行前将保存现场执行后恢复



#### Return  


R



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| block| <br><br>@kotlin.ExtensionFunctionType Function1<Accessor, R> 调用<br><br>
| modes| <br><br>Modes 指定模式<br><br>
  
  
Content  
@[Synchronized](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-synchronized/index.html)()  
  
fun <[R](run.md)> [run](run.md)(modes: [Modes](../-modes/index.md), block: [Accessor](index.md).() -> [R](run.md)): [R](run.md)  



