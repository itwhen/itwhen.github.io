---
title: of -
---
//[echo](../../../index.md)/[tech.whence.echo.retry](../../index.md)/[BackoffRetry](../index.md)/[Companion](index.md)/[of](of.md)



# of  
[jvm]  
Brief description  


构造



#### Return  


BackoffRetry



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| duration| <br><br>Duration 单位持续时间<br><br>
| max| <br><br>Duration 最长时间<br><br>
| times| <br><br>Int 总次数<br><br>
  
  
Content  
@[JvmStatic](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-static/index.html)()  
  
fun [of](of.md)(times: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), max: [Duration](https://docs.oracle.com/javase/8/docs/api/java/time/Duration.html), duration: [Duration](https://docs.oracle.com/javase/8/docs/api/java/time/Duration.html)): [BackoffRetry](../index.md)  


[jvm]  
Brief description  


构造 最长时间为一个小时



#### Return  


BackoffRetry



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| duration| <br><br>Duration 单位持续时间<br><br>
| times| <br><br>Int 总次数<br><br>
  
  
Content  
@[JvmStatic](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-static/index.html)()  
  
fun [of](of.md)(times: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), duration: [Duration](https://docs.oracle.com/javase/8/docs/api/java/time/Duration.html)): [BackoffRetry](../index.md)  


[jvm]  
Brief description  


构造 默认时间单位为毫秒



#### Return  


BackoffRetry



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| duration| <br><br>Long 单位延续时间<br><br>
| max| <br><br>Long 最长时间<br><br>
| times| <br><br>Int 总次数<br><br>
  
  
Content  
@[JvmStatic](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-static/index.html)()  
  
fun [of](of.md)(times: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), max: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html), duration: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)): [BackoffRetry](../index.md)  



