---
title: Degrader -
---
//[echo](../../index.md)/[tech.whence.echo.job.stream.degrader](../index.md)/[Degrader](index.md)



# Degrader  
 [jvm] 

降级器

class [Degrader](index.md)(**controller**: [Controller](../-controller/index.md), **window**: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), **measurer**: [Measurer](../../tech.whence.echo.job.stream.work/-measurer/index.md), **idler**: [Retry](../../tech.whence.echo.retry/-retry/index.md)?)   


## Constructors  
  
|  Name|  Summary| 
|---|---|
| [Degrader](-degrader.md)|  [jvm] fun [Degrader](-degrader.md)(controller: [Controller](../-controller/index.md), window: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), measurer: [Measurer](../../tech.whence.echo.job.stream.work/-measurer/index.md), idler: [Retry](../../tech.whence.echo.retry/-retry/index.md)?)   <br>


## Functions  
  
|  Name|  Summary| 
|---|---|
| [attempt](attempt.md)| [jvm]  <br>Brief description  <br><br><br>尝试通过 1 若默认阶段允许 2 若在阻塞阶段不允许 3 否则根据权重决定最大尝试次数     在尝试次数内随机     若该随机数介乎于当前几率与控制器高水位之间则允许通过<br><br>  <br>Content  <br>fun [attempt](attempt.md)(weighting: [UInt](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-u-int/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [deflate](deflate.md)| [jvm]  <br>Brief description  <br><br><br>收缩 若不收缩则全部通过 若全部收缩则只允许一个通过 否则允许请求量扣除收缩比率的部分<br><br>  <br>Content  <br>fun [deflate](deflate.md)(value: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)| [jvm]  <br>Content  <br>open operator override fun [equals](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/equals/#kotlin.Any?/PointingToDeclaration/)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [hashCode](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/hashCode/#/PointingToDeclaration/)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [idle](idle.md)| [jvm]  <br>Brief description  <br><br><br>取下一次执行时间 若未设置空转时间则返回空 若在初始阶段则重置空转时间并返回空 否则返回空转等待的下一个时间<br><br>  <br>Content  <br>fun [idle](idle.md)(): [Duration](https://docs.oracle.com/javase/8/docs/api/java/time/Duration.html)?  <br><br><br>
| [inspect](inspect.md)| [jvm]  <br>Brief description  <br><br><br>检查当前状态 总失败率=失败+重试+丢弃 总概率=总失败率+成功+重试+忽略 当前比率=总失败率/总概率 收缩指数=1-控制器通过概率<br><br>  <br>Content  <br>fun [inspect](inspect.md)()  <br><br><br>
| [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [toString](../../tech.whence.echo.webclient.response.exception/-response-unrecognized-exception/index.md#kotlin/Any/toString/#/PointingToDeclaration/)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>
| [under](under.md)| [jvm]  <br>Brief description  <br><br><br>判断是否在指定阶段<br><br>  <br>Content  <br>fun [under](under.md)(stage: [Stage](../-stage/index.md)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>


## Properties  
  
|  Name|  Summary| 
|---|---|
| [currentRate](index.md#tech.whence.echo.job.stream.degrader/Degrader/currentRate/#/PointingToDeclaration/)|  [jvm] <br><br>Double 当前通过率<br><br>@[Volatile](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-volatile/index.html)()  <br>  <br>var [currentRate](index.md#tech.whence.echo.job.stream.degrader/Degrader/currentRate/#/PointingToDeclaration/): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)   <br>
| [deflator](index.md#tech.whence.echo.job.stream.degrader/Degrader/deflator/#/PointingToDeclaration/)|  [jvm] <br><br>Double 收缩指数<br><br>@[Volatile](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-volatile/index.html)()  <br>  <br>var [deflator](index.md#tech.whence.echo.job.stream.degrader/Degrader/deflator/#/PointingToDeclaration/): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)   <br>
| [happening](index.md#tech.whence.echo.job.stream.degrader/Degrader/happening/#/PointingToDeclaration/)|  [jvm] <br><br>Boolean 是否在降级中<br><br>val [happening](index.md#tech.whence.echo.job.stream.degrader/Degrader/happening/#/PointingToDeclaration/): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)   <br>
| [lastRate](index.md#tech.whence.echo.job.stream.degrader/Degrader/lastRate/#/PointingToDeclaration/)|  [jvm] <br><br>Double 上次通过率<br><br>@[Volatile](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-volatile/index.html)()  <br>  <br>var [lastRate](index.md#tech.whence.echo.job.stream.degrader/Degrader/lastRate/#/PointingToDeclaration/): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)   <br>
| [maxRate](index.md#tech.whence.echo.job.stream.degrader/Degrader/maxRate/#/PointingToDeclaration/)|  [jvm] <br><br>Double 最大通过滤<br><br>val [maxRate](index.md#tech.whence.echo.job.stream.degrader/Degrader/maxRate/#/PointingToDeclaration/): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)   <br>
| [minRate](index.md#tech.whence.echo.job.stream.degrader/Degrader/minRate/#/PointingToDeclaration/)|  [jvm] <br><br>Double 最小通过率<br><br>val [minRate](index.md#tech.whence.echo.job.stream.degrader/Degrader/minRate/#/PointingToDeclaration/): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)   <br>
| [recovering](index.md#tech.whence.echo.job.stream.degrader/Degrader/recovering/#/PointingToDeclaration/)|  [jvm] <br><br>Boolean 是否在恢复中<br><br>val [recovering](index.md#tech.whence.echo.job.stream.degrader/Degrader/recovering/#/PointingToDeclaration/): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)   <br>

