---
title: tech.whence.echo.function -
---
//[echo](../index.md)/[tech.whence.echo.function](index.md)



# Package tech.whence.echo.function  


## Types  
  
|  Name|  Summary| 
|---|---|
| [Breaker](-breaker/index.md)| [jvm]  <br>Brief description  <br><br><br>断路器 判断指定初始值跟指定值 告知下一步是否中断并返回修正值<br><br>  <br>Content  <br>fun fun interface [Breaker](-breaker/index.md)<[I](-breaker/index.md), [V](-breaker/index.md)>  <br><br><br>
| [Consumer](-consumer/index.md)| [jvm]  <br>Brief description  <br><br><br>消费者<br><br>  <br>Content  <br>fun fun interface [Consumer](-consumer/index.md)<[T](-consumer/index.md)>  <br><br><br>
| [Fixer](-fixer/index.md)| [jvm]  <br>Brief description  <br><br><br>纠正器<br><br>  <br>Content  <br>fun fun interface [Fixer](-fixer/index.md)<[T](-fixer/index.md)>  <br><br><br>
| [Handler](-handler/index.md)| [jvm]  <br>Brief description  <br><br><br>处理器<br><br>  <br>Content  <br>fun fun interface [Handler](-handler/index.md)<[T](-handler/index.md)>  <br><br><br>
| [KeyValueFixer](-key-value-fixer/index.md)| [jvm]  <br>Brief description  <br><br><br>键值纠正器<br><br>  <br>Content  <br>fun fun interface [KeyValueFixer](-key-value-fixer/index.md)<[T](-key-value-fixer/index.md)>  <br><br><br>
| [Predicate](-predicate/index.md)| [jvm]  <br>Brief description  <br><br><br>断言<br><br>  <br>Content  <br>fun fun interface [Predicate](-predicate/index.md)<[T](-predicate/index.md)>  <br><br><br>
| [Producer](-producer/index.md)| [jvm]  <br>Brief description  <br><br><br>生产者<br><br>  <br>Content  <br>fun fun interface [Producer](-producer/index.md)<[T](-producer/index.md)>  <br><br><br>
| [Runner](-runner/index.md)| [jvm]  <br>Brief description  <br><br><br>执行者<br><br>  <br>Content  <br>fun fun interface [Runner](-runner/index.md)  <br><br><br>
| [Transformer](-transformer/index.md)| [jvm]  <br>Brief description  <br><br><br>转换器<br><br>  <br>Content  <br>fun fun interface [Transformer](-transformer/index.md)<[F](-transformer/index.md), [T](-transformer/index.md)>  <br><br><br>


## Functions  
  
|  Name|  Summary| 
|---|---|
| [act](act.md)| [jvm]  <br>Brief description  <br><br><br>强制转换类型<br><br>  <br>Content  <br>inline fun <[T](act.md) : [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)> [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html).[act](act.md)(): [T](act.md)?  <br><br><br>[jvm]  <br>Brief description  <br><br><br>强制转换类型并执行转换<br><br>  <br>Content  <br>inline fun <[T](act.md) : [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html), [R](act.md)> [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html).[act](act.md)(convert: [T](act.md).() -> [R](act.md)?): [R](act.md)?  <br><br><br>
| [actIf](act-if.md)| [jvm]  <br>Brief description  <br><br><br>若前置条件为真时执行指定转换返回结果 否则强转自身为指定类型<br><br>  <br>Content  <br>inline fun <[T](act-if.md) : [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html), [R](act-if.md) : [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)> [T](act-if.md).[actIf](act-if.md)(predicate: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), convert: [T](act-if.md).() -> [R](act-if.md)?): [R](act-if.md)?  <br><br><br>
| [actIn](act-in.md)| [jvm]  <br>Brief description  <br><br><br>安全强制转换类型 若类型[P](act-in.md)是类型[T](act-in.md)的子类或是后者的类型擦除产物 若自身是[P](act-in.md)则强转为[T](act-in.md) 否则返回空<br><br>  <br>Content  <br>inline fun <[P](act-in.md) : [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html), [T](act-in.md) : [P](act-in.md), [R](act-in.md)> [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html).[actIn](act-in.md)(block: [T](act-in.md).() -> [R](act-in.md)?): [R](act-in.md)?  <br><br><br>
| [actOn](act-on.md)| [jvm]  <br>Brief description  <br><br><br>若强转存在执行指定强转返回结果 否则强转自身为指定类型<br><br>  <br>Content  <br>inline fun <[T](act-on.md) : [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html), [R](act-on.md) : [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)> [T](act-on.md)?.[actOn](act-on.md)(noinline act: [T](act-on.md).() -> [R](act-on.md)??): [R](act-on.md)?  <br><br><br>
| [applyIf](apply-if.md)| [jvm]  <br>Brief description  <br><br><br>执行指定回调 若前置条件为真时执行回调 否则不执行<br><br>  <br>Content  <br>inline fun <[T](apply-if.md) : [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)> [T](apply-if.md).[applyIf](apply-if.md)(predicate: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), block: [T](apply-if.md).() -> [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)): [T](apply-if.md)  <br><br><br>
| [applyOn](apply-on.md)| [jvm]  <br>Brief description  <br><br><br>执行指定回调 若前置条件为真时执行回调 否则不执行<br><br>  <br>Content  <br>fun <[T](apply-on.md) : [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)> [T](apply-on.md).[applyOn](apply-on.md)(block: [T](apply-on.md).() -> [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)?): [T](apply-on.md)  <br><br><br>
| [be](be.md)| [jvm]  <br>Brief description  <br><br><br>强制转换类型<br><br>  <br>Content  <br>inline fun <[T](be.md) : [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)> [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?.[be](be.md)(): [T](be.md)  <br><br><br>
| [cover](cover.md)| [jvm]  <br>Brief description  <br><br><br>强制转换为子类型并执行回调<br><br>  <br>Content  <br>inline fun <[T](cover.md) : [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html), [S](cover.md) : [T](cover.md)> [T](cover.md).[cover](cover.md)(block: [T](cover.md).() -> [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)): [S](cover.md)  <br><br><br>
| [dump](dump.md)| [jvm]  <br>Brief description  <br><br><br>打印当前对象<br><br>  <br>Content  <br>fun <[T](dump.md)> [T](dump.md).[dump](dump.md)(detail: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), exceptional: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)): [T](dump.md)  <br><br><br>
| [errorIf](error-if.md)| [jvm]  <br>Brief description  <br><br><br>若满足条件抛出异常<br><br>  <br>Content  <br>fun <[T](error-if.md) : [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)> [T](error-if.md).[errorIf](error-if.md)(predicate: [T](error-if.md).() -> [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), message: [T](error-if.md).() -> [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): [T](error-if.md)  <br><br><br>
| [fixIf](fix-if.md)| [jvm]  <br>Brief description  <br><br><br>执行指定回调纠正 若前置条件为真时执行回调 否则不执行并返回自身<br><br>  <br>Content  <br>inline fun <[T](fix-if.md) : [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)> [T](fix-if.md).[fixIf](fix-if.md)(predicate: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), block: ([T](fix-if.md)) -> [T](fix-if.md)): [T](fix-if.md)  <br><br><br>
| [fixOn](fix-on.md)| [jvm]  <br>Brief description  <br><br><br>执行指定纠正<br><br>  <br>Content  <br>fun <[T](fix-on.md) : [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)> [T](fix-on.md).[fixOn](fix-on.md)(fix: ([T](fix-on.md)) -> [T](fix-on.md)?): [T](fix-on.md)  <br><br><br>
| [identity](identity.md)| [jvm]  <br>Brief description  <br><br><br>返回自身<br><br>  <br>Content  <br>fun <[T](identity.md)> [T](identity.md).[identity](identity.md)(): [T](identity.md)  <br><br><br>
| [ifNonempty](if-nonempty.md)| [jvm]  <br>Brief description  <br><br><br>若自身不为空则执行回调<br><br>  <br>Content  <br>fun <[T](if-nonempty.md), [R](if-nonempty.md)> [T](if-nonempty.md).[ifNonempty](if-nonempty.md)(block: ([T](if-nonempty.md)) -> [R](if-nonempty.md)): [R](if-nonempty.md)?  <br><br><br>
| [letIf](let-if.md)| [jvm]  <br>Brief description  <br><br><br>执行指定回调 若前置条件为真时执行回调并返回结果 否则返回空<br><br>  <br>Content  <br>inline fun <[T](let-if.md) : [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html), [R](let-if.md)> [T](let-if.md).[letIf](let-if.md)(predicate: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), block: ([T](let-if.md)) -> [R](let-if.md)?): [R](let-if.md)?  <br><br><br>
| [letOn](let-on.md)| [jvm]  <br>Brief description  <br><br><br>执行指定回调 若回调为空返回空 否则执行并返回结果<br><br>  <br>Content  <br>fun <[T](let-on.md) : [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html), [R](let-on.md)> [T](let-on.md).[letOn](let-on.md)(block: ([T](let-on.md)) -> [R](let-on.md)??): [R](let-on.md)?  <br><br><br>
| [negate](negate.md)| [jvm]  <br>Brief description  <br><br><br>给指定数值取反<br><br>  <br>Content  <br>fun [Number](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-number/index.html).[negate](negate.md)(): [Number](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-number/index.html)  <br><br><br>
| [none](none.md)| [jvm]  <br>Brief description  <br><br><br>返回空<br><br>  <br>Content  <br>inline fun <[T](none.md)> [none](none.md)(): [T](none.md)?  <br><br><br>
| [noop](noop.md)| [jvm]  <br>Brief description  <br><br><br>空操作<br><br>  <br>Content  <br>inline fun [noop](noop.md)()  <br><br><br>
| [nullIf](null-if.md)| [jvm]  <br>Brief description  <br><br><br>若前置条件为真时返回空 否则返回本身<br><br>  <br>Content  <br>fun <[T](null-if.md) : [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)> [T](null-if.md).[nullIf](null-if.md)(predicate: [T](null-if.md).() -> [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)?): [T](null-if.md)?  <br><br><br>
| [nullIfEmpty](null-if-empty.md)| [jvm]  <br>Brief description  <br><br><br>若本身是空的返回空<br><br>  <br>Content  <br>fun <[T](null-if-empty.md) : [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)> [T](null-if-empty.md).[nullIfEmpty](null-if-empty.md)(): [T](null-if-empty.md)?  <br><br><br>
| [orDefault](or-default.md)| [jvm]  <br>Brief description  <br><br><br>若自身为空执行回调返回结果<br><br>  <br>Content  <br>fun <[T](or-default.md) : [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)> [T](or-default.md)?.[orDefault](or-default.md)(create: () -> [T](or-default.md)?): [T](or-default.md)?  <br><br><br>
| [otherwise](otherwise.md)| [jvm]  <br>Brief description  <br><br><br>为假时执行下一步<br><br>  <br>Content  <br>fun [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)?.[otherwise](otherwise.md)(block: () -> [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html))  <br><br><br>
| [otherwiseIf](otherwise-if.md)| [jvm]  <br>Brief description  <br><br><br>若自身为空且前置条件为真时执行回调返回结果<br><br>  <br>Content  <br>fun <[T](otherwise-if.md) : [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)> [T](otherwise-if.md)?.[otherwiseIf](otherwise-if.md)(predicate: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), create: () -> [T](otherwise-if.md)?): [T](otherwise-if.md)?  <br><br><br>
| [predicateIf](predicate-if.md)| [jvm]  <br>Brief description  <br><br><br>若前置条件为空返回真 若自身为空且前置条件为真时返回真 否则返回假<br><br>  <br>Content  <br>fun <[T](predicate-if.md) : [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)> [T](predicate-if.md)?.[predicateIf](predicate-if.md)(predicate: [T](predicate-if.md).() -> [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [runIf](run-if.md)| [jvm]  <br>Brief description  <br><br><br>执行指定回调 若前置条件为真时执行回调并返回结果 否则返回空<br><br>  <br>Content  <br>inline fun <[T](run-if.md) : [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html), [R](run-if.md)> [T](run-if.md).[runIf](run-if.md)(predicate: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), block: [T](run-if.md).() -> [R](run-if.md)?): [R](run-if.md)?  <br><br><br>
| [runOn](run-on.md)| [jvm]  <br>Brief description  <br><br><br>执行指定回调 若回调为空返回空 否则执行并返回结果<br><br>  <br>Content  <br>fun <[T](run-on.md) : [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html), [R](run-on.md)> [T](run-on.md).[runOn](run-on.md)(block: [T](run-on.md).() -> [R](run-on.md)??): [R](run-on.md)?  <br><br><br>
| [then](then.md)| [jvm]  <br>Brief description  <br><br><br>为真时执行下一步<br><br>  <br>Content  <br>fun [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html).[then](then.md)(block: () -> [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html))  <br><br><br>
| [unsupported](unsupported.md)| [jvm]  <br>Brief description  <br><br><br>不支持的操作<br><br>  <br>Content  <br>inline fun [unsupported](unsupported.md)(message: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, cause: [Throwable](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-throwable/index.html)?): [Nothing](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-nothing/index.html)  <br><br><br>


## Properties  
  
|  Name|  Summary| 
|---|---|
| [empty](index.md#tech.whence.echo.function//empty/kotlin.Any?#/PointingToDeclaration/)|  [jvm] <br><br>判断是否为空的<br><br>val [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?.[empty](index.md#tech.whence.echo.function//empty/kotlin.Any?#/PointingToDeclaration/): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)   <br>
| [nonempty](index.md#tech.whence.echo.function//nonempty/kotlin.Any?#/PointingToDeclaration/)|  [jvm] <br><br>判断是否非空<br><br>val [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?.[nonempty](index.md#tech.whence.echo.function//nonempty/kotlin.Any?#/PointingToDeclaration/): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)   <br>
