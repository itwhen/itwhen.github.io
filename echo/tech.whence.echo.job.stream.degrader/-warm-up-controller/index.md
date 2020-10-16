---
title: WarmUpController -
---
//[echo](../../index.md)/[tech.whence.echo.job.stream.degrader](../index.md)/[WarmUpController](index.md)



# WarmUpController  
 [jvm] 

预热式控制器

class [WarmUpController](index.md) : [Controller](../-controller/index.md)   


## Constructors  
  
|  Name|  Summary| 
|---|---|
| [WarmUpController](-warm-up-controller.md)|  [jvm] fun [WarmUpController](-warm-up-controller.md)(window: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), factor: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), min: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), max: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html))   <br>
| [WarmUpController](-warm-up-controller.md)|  [jvm] fun [WarmUpController](-warm-up-controller.md)(window: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), factor: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), period: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html))   <br>


## Functions  
  
|  Name|  Summary| 
|---|---|
| [control](control.md)| [jvm]  <br>Brief description  <br><br><br>输入当前失败率返回通过概率<br><br>  <br>Content  <br>open override fun [control](control.md)(failure: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)  <br><br><br>
| [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)| [jvm]  <br>Content  <br>open operator override fun [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>


## Properties  
  
|  Name|  Summary| 
|---|---|
| [max](index.md#tech.whence.echo.job.stream.degrader/WarmUpController/max/#/PointingToDeclaration/)|  [jvm] <br><br>Double 高水位<br><br>open override val [max](index.md#tech.whence.echo.job.stream.degrader/WarmUpController/max/#/PointingToDeclaration/): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)   <br>
| [min](index.md#tech.whence.echo.job.stream.degrader/WarmUpController/min/#/PointingToDeclaration/)|  [jvm] <br><br>Double 低水位<br><br>open override val [min](index.md#tech.whence.echo.job.stream.degrader/WarmUpController/min/#/PointingToDeclaration/): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)   <br>

