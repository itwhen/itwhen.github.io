---
title: tech.whence.echo.validation.rule -
---
//[echo](../index.md)/[tech.whence.echo.validation.rule](index.md)



# Package tech.whence.echo.validation.rule  


## Types  
  
|  Name|  Summary| 
|---|---|
| [Accepted](-accepted/index.md)| [jvm]  <br>Brief description  <br><br><br>已接受的<br><br>  <br>Content  <br>class [Accepted](-accepted/index.md)(**values**: [Set](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-set/index.html)<[Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>) : [Rule](-rule/index.md)  <br><br><br>
| [Date](-date/index.md)| [jvm]  <br>Brief description  <br><br><br>日期<br><br>  <br>Content  <br>class [Date](-date/index.md) : [Rule](-rule/index.md)  <br><br><br>
| [Different](-different/index.md)| [jvm]  <br>Brief description  <br><br><br>不一致<br><br>  <br>Content  <br>class [Different](-different/index.md)(**target**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)) : [Rule](-rule/index.md)  <br><br><br>
| [Length](-length/index.md)| [jvm]  <br>Brief description  <br><br><br>长度<br><br>  <br>Content  <br>class [Length](-length/index.md) : [Rule](-rule/index.md)  <br><br><br>
| [Predication](-predication/index.md)| [jvm]  <br>Brief description  <br><br><br>断言<br><br>  <br>Content  <br>class [Predication](-predication/index.md)(**name**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), **predicate**: [Predicate](../tech.whence.echo.function/-predicate/index.md)<[Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?>) : [Rule](-rule/index.md)  <br><br><br>
| [Range](-range/index.md)| [jvm]  <br>Brief description  <br><br><br>大小<br><br>  <br>Content  <br>class [Range](-range/index.md) : [Rule](-rule/index.md)  <br><br><br>
| [Required](-required/index.md)| [jvm]  <br>Brief description  <br><br><br>必填<br><br>  <br>Content  <br>class [Required](-required/index.md) : [Rule](-rule/index.md)  <br><br><br>
| [RequiredIf](-required-if/index.md)| [jvm]  <br>Brief description  <br><br><br>若目标键值在指定范围内则必填<br><br>  <br>Content  <br>class [RequiredIf](-required-if/index.md)(**target**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), **scope**: [Set](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-set/index.html)<[Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>) : [Rule](-rule/index.md)  <br><br><br>
| [RequiredUnless](-required-unless/index.md)| [jvm]  <br>Brief description  <br><br><br>若目标键值不在指定范围内则必填<br><br>  <br>Content  <br>class [RequiredUnless](-required-unless/index.md)(**target**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), **scope**: [Set](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-set/index.html)<[Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>) : [Rule](-rule/index.md)  <br><br><br>
| [RequiredWith](-required-with/index.md)| [jvm]  <br>Brief description  <br><br><br>若目标键非空则必填<br><br>  <br>Content  <br>class [RequiredWith](-required-with/index.md)(**targets**: [Set](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-set/index.html)<[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)>, **entire**: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)) : [Rule](-rule/index.md)  <br><br><br>
| [RequiredWithout](-required-without/index.md)| [jvm]  <br>Brief description  <br><br><br>若目标键为空则必填<br><br>  <br>Content  <br>class [RequiredWithout](-required-without/index.md)(**targets**: [Set](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-set/index.html)<[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)>, **entire**: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)) : [Rule](-rule/index.md)  <br><br><br>
| [Rule](-rule/index.md)| [jvm]  <br>Brief description  <br><br><br>校验规则<br><br>  <br>Content  <br>abstract class [Rule](-rule/index.md)  <br><br><br>
| [Same](-same/index.md)| [jvm]  <br>Brief description  <br><br><br>一致<br><br>  <br>Content  <br>class [Same](-same/index.md)(**target**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)) : [Rule](-rule/index.md)  <br><br><br>
| [Size](-size/index.md)| [jvm]  <br>Brief description  <br><br><br>容量<br><br>  <br>Content  <br>class [Size](-size/index.md) : [Rule](-rule/index.md)  <br><br><br>
| [Sometimes](-sometimes/index.md)| [jvm]  <br>Brief description  <br><br><br>可能存在 严格模式时将检查字符串长度及容器大小<br><br>  <br>Content  <br>class [Sometimes](-sometimes/index.md)(**strict**: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)) : [Rule](-rule/index.md)  <br><br><br>

