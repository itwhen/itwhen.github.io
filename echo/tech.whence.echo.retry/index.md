---
title: tech.whence.echo.retry -
---
//[echo](../index.md)/[tech.whence.echo.retry](index.md)



# Package tech.whence.echo.retry  


## Types  
  
|  Name|  Summary| 
|---|---|
| [AbstractRetry](-abstract-retry/index.md)| [jvm]  <br>Brief description  <br><br><br>抽象重试<br><br>  <br>Content  <br>abstract class [AbstractRetry](-abstract-retry/index.md) : [Retry](-retry/index.md)  <br><br><br>
| [BackoffRetry](-backoff-retry/index.md)| [jvm]  <br>Brief description  <br><br><br>回退重试 随重试次数增加等待时间直到最大等待时间<br><br>  <br>Content  <br>class [BackoffRetry](-backoff-retry/index.md)(**times**: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), **max**: [Duration](https://docs.oracle.com/javase/8/docs/api/java/time/Duration.html), **duration**: [Duration](https://docs.oracle.com/javase/8/docs/api/java/time/Duration.html)) : [AbstractRetry](-abstract-retry/index.md)  <br><br><br>
| [ForeverRetry](-forever-retry/index.md)| [jvm]  <br>Brief description  <br><br><br>永久重试<br><br>  <br>Content  <br>class [ForeverRetry](-forever-retry/index.md)(**duration**: [Duration](https://docs.oracle.com/javase/8/docs/api/java/time/Duration.html)) : [Retry](-retry/index.md)  <br><br><br>
| [NTimesRetry](-n-times-retry/index.md)| [jvm]  <br>Brief description  <br><br><br>指定次数重试<br><br>  <br>Content  <br>open class [NTimesRetry](-n-times-retry/index.md)(**times**: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), **duration**: [Duration](https://docs.oracle.com/javase/8/docs/api/java/time/Duration.html)) : [AbstractRetry](-abstract-retry/index.md)  <br><br><br>
| [OneTimeRetry](-one-time-retry/index.md)| [jvm]  <br>Brief description  <br><br><br>一次重试<br><br>  <br>Content  <br>class [OneTimeRetry](-one-time-retry/index.md)(**duration**: [Duration](https://docs.oracle.com/javase/8/docs/api/java/time/Duration.html)) : [NTimesRetry](-n-times-retry/index.md)  <br><br><br>
| [Retry](-retry/index.md)| [jvm]  <br>Brief description  <br><br><br>重试<br><br>  <br>Content  <br>interface [Retry](-retry/index.md)  <br><br><br>
| [Retrying](-retrying/index.md)| [jvm]  <br>Brief description  <br><br><br>重试设置<br><br>  <br>Content  <br>class [Retrying](-retrying/index.md)  <br><br><br>
| [RetrySleeper](-retry-sleeper/index.md)| [jvm]  <br>Brief description  <br><br><br>休眠器<br><br>  <br>Content  <br>fun fun interface [RetrySleeper](-retry-sleeper/index.md)  <br><br><br>
| [UntilRetry](-until-retry/index.md)| [jvm]  <br>Brief description  <br><br><br>直到指定条件重试<br><br>  <br>Content  <br>class [UntilRetry](-until-retry/index.md)(**max**: [Duration](https://docs.oracle.com/javase/8/docs/api/java/time/Duration.html), **duration**: [Duration](https://docs.oracle.com/javase/8/docs/api/java/time/Duration.html)) : [AbstractRetry](-abstract-retry/index.md)  <br><br><br>

