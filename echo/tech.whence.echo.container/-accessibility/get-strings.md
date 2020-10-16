---
title: getStrings -
---
//[echo](../../index.md)/[tech.whence.echo.container](../index.md)/[Accessibility](index.md)/[getStrings](get-strings.md)



# getStrings  
[jvm]  
Brief description  


取字符串数组



#### Return  


Result<StringArray>



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| blankable| <br><br>Boolean 是否允许空字符串<br><br>
| key| <br><br>K 指定键<br><br>
| trim| <br><br>Boolean 是否前后去除空格<br><br>
  
  
Content  
open fun [getStrings](get-strings.md)(key: [K](index.md), trim: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), blankable: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)): [Reply](../-reply/index.md)<[StringArray](../../tech.whence.echo.type/index.md#tech.whence.echo.type/StringArray///PointingToDeclaration/)>  


[jvm]  
Brief description  


取字符串数组



#### Return  


Result<StringArray>



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| caster| <br><br>Transformer<String, String>? 转换器<br><br>
| delimiter| <br><br>Regex? 分隔正则<br><br>
| key| <br><br>K 指定键<br><br>
  
  
Content  
open fun [getStrings](get-strings.md)(key: [K](index.md), delimiter: [Regex](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.text/-regex/index.html)?, caster: [Transformer](../../tech.whence.echo.function/-transformer/index.md)<[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)>?): [Reply](../-reply/index.md)<[StringArray](../../tech.whence.echo.type/index.md#tech.whence.echo.type/StringArray///PointingToDeclaration/)>  


[jvm]  
Brief description  


取字符串数组



#### Return  


Reply<StringArray>



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| caster| <br><br>Transformer<String, String>? 转换器<br><br>
| delimiter| <br><br>CharSequence 分割字符串<br><br>
| key| <br><br>K 指定键<br><br>
  
  
Content  
open fun [getStrings](get-strings.md)(key: [K](index.md), delimiter: [CharSequence](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-char-sequence/index.html), caster: [Transformer](../../tech.whence.echo.function/-transformer/index.md)<[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)>?): [Reply](../-reply/index.md)<[StringArray](../../tech.whence.echo.type/index.md#tech.whence.echo.type/StringArray///PointingToDeclaration/)>  



