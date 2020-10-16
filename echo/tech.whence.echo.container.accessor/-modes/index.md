---
title: Modes -
---
//[echo](../../index.md)/[tech.whence.echo.container.accessor](../index.md)/[Modes](index.md)



# Modes  
 [jvm] 

模式设置 用于存储多个模式值并提供简便操作方式

class [Modes](index.md)(**data**: [LinkedHashSet](https://docs.oracle.com/javase/8/docs/api/java/util/LinkedHashSet.html)<[Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>)   


## Constructors  
  
|  Name|  Summary| 
|---|---|
| [Modes](-modes.md)|  [jvm] <br><br><br><br>fun [Modes](-modes.md)(data: [LinkedHashSet](https://docs.oracle.com/javase/8/docs/api/java/util/LinkedHashSet.html)<[Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>)   <br>


## Functions  
  
|  Name|  Summary| 
|---|---|
| [contains](contains.md)| [jvm]  <br>Brief description  <br><br><br>判断是否包含指定模式<br><br>  <br>Content  <br>fun [contains](contains.md)(mode: [Mode](../-mode/index.md)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [equals](equals.md)| [jvm]  <br>Content  <br>open operator override fun [equals](equals.md)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [hashCode](hash-code.md)| [jvm]  <br>Content  <br>open override fun [hashCode](hash-code.md)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [minus](minus.md)| [jvm]  <br>Brief description  <br><br><br>提供 mode - mode 支持<br><br>  <br>Content  <br>operator fun [minus](minus.md)(mode: [Mode](../-mode/index.md)): [Modes](index.md)  <br><br><br>
| [plus](plus.md)| [jvm]  <br>Brief description  <br><br><br>提供 mode + mode 支持<br><br>  <br>Content  <br>operator fun [plus](plus.md)(mode: [Mode](../-mode/index.md)): [Modes](index.md)  <br><br><br>
| [reset](reset.md)| [jvm]  <br>Brief description  <br><br><br>重置到初始状态<br><br>  <br>Content  <br>fun [reset](reset.md)(): [Modes](index.md)  <br><br><br>
| [toString](to-string.md)| [jvm]  <br>Content  <br>open override fun [toString](to-string.md)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>

