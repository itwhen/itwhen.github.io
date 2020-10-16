---
title: Operation -
---
//[echo](../../index.md)/[tech.whence.echo.dal.dao](../index.md)/[Operation](index.md)



# Operation  
 [jvm] 

操作类型

enum [Operation](index.md) : [Enum](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-enum/index.html)<[Operation](index.md)>    


## Entries  
  
|  Name|  Summary| 
|---|---|
| [FIND](-f-i-n-d/index.md)|  [jvm] <br><br>查询<br><br>[FIND](-f-i-n-d/index.md)(false, false)  <br>  <br>   <br>
| [CREATE](-c-r-e-a-t-e/index.md)|  [jvm] <br><br>数据创建<br><br>[CREATE](-c-r-e-a-t-e/index.md)(true, true)  <br>  <br>   <br>
| [DELETE](-d-e-l-e-t-e/index.md)|  [jvm] <br><br>数据删除<br><br>[DELETE](-d-e-l-e-t-e/index.md)(false, true)  <br>  <br>   <br>
| [RETRIEVE](-r-e-t-r-i-e-v-e/index.md)|  [jvm] <br><br>数据获取<br><br>[RETRIEVE](-r-e-t-r-i-e-v-e/index.md)(false, false)  <br>  <br>   <br>
| [COUNT](-c-o-u-n-t/index.md)|  [jvm] <br><br>数据统计<br><br>[COUNT](-c-o-u-n-t/index.md)(false, false)  <br>  <br>   <br>
| [UPDATE](-u-p-d-a-t-e/index.md)|  [jvm] <br><br>数据更新<br><br>[UPDATE](-u-p-d-a-t-e/index.md)(true, true)  <br>  <br>   <br>
| [SINGULARIZE](-s-i-n-g-u-l-a-r-i-z-e/index.md)|  [jvm] <br><br>数据检查唯一性<br><br>[SINGULARIZE](-s-i-n-g-u-l-a-r-i-z-e/index.md)(false, false)  <br>  <br>   <br>


## Functions  
  
|  Name|  Summary| 
|---|---|
| [compareTo](-s-i-n-g-u-l-a-r-i-z-e/index.md#kotlin/Enum/compareTo/#tech.whence.echo.dal.dao.Operation/PointingToDeclaration/)| [jvm]  <br>Content  <br>operator override fun [compareTo](-s-i-n-g-u-l-a-r-i-z-e/index.md#kotlin/Enum/compareTo/#tech.whence.echo.dal.dao.Operation/PointingToDeclaration/)(other: [Operation](index.md)): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [equals](../../tech.whence.echo.webclient.response/-response-mocker/-purpose/-p-a-r-s-e-d/index.md#kotlin/Enum/equals/#kotlin.Any?/PointingToDeclaration/)| [jvm]  <br>Content  <br>operator override fun [equals](../../tech.whence.echo.webclient.response/-response-mocker/-purpose/-p-a-r-s-e-d/index.md#kotlin/Enum/equals/#kotlin.Any?/PointingToDeclaration/)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [finalize](../../tech.whence.echo.webclient.response/-response-mocker/-purpose/-p-a-r-s-e-d/index.md#kotlin/Enum/finalize/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>override fun [finalize](../../tech.whence.echo.webclient.response/-response-mocker/-purpose/-p-a-r-s-e-d/index.md#kotlin/Enum/finalize/#/PointingToDeclaration/)()  <br><br><br>
| [getDeclaringClass](../../tech.whence.echo.webclient.response/-response-mocker/-purpose/-p-a-r-s-e-d/index.md#kotlin/Enum/getDeclaringClass/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>override fun [getDeclaringClass](../../tech.whence.echo.webclient.response/-response-mocker/-purpose/-p-a-r-s-e-d/index.md#kotlin/Enum/getDeclaringClass/#/PointingToDeclaration/)(): [Class](https://docs.oracle.com/javase/8/docs/api/java/lang/Class.html)<[Operation](index.md)>  <br><br><br>
| [hashCode](../../tech.whence.echo.webclient.response/-response-mocker/-purpose/-p-a-r-s-e-d/index.md#kotlin/Enum/hashCode/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>override fun [hashCode](../../tech.whence.echo.webclient.response/-response-mocker/-purpose/-p-a-r-s-e-d/index.md#kotlin/Enum/hashCode/#/PointingToDeclaration/)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [toString](../../tech.whence.echo.webclient.response/-response-mocker/-purpose/-p-a-r-s-e-d/index.md#kotlin/Enum/toString/#/PointingToDeclaration/)| [jvm]  <br>Content  <br>open override fun [toString](../../tech.whence.echo.webclient.response/-response-mocker/-purpose/-p-a-r-s-e-d/index.md#kotlin/Enum/toString/#/PointingToDeclaration/)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>


## Properties  
  
|  Name|  Summary| 
|---|---|
| [affecting](index.md#tech.whence.echo.dal.dao/Operation/affecting/#/PointingToDeclaration/)|  [jvm] <br><br>Boolean 是否有影响行数<br><br>val [affecting](index.md#tech.whence.echo.dal.dao/Operation/affecting/#/PointingToDeclaration/): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)   <br>
| [name](index.md#tech.whence.echo.dal.dao/Operation/name/#/PointingToDeclaration/)|  [jvm] override val [name](index.md#tech.whence.echo.dal.dao/Operation/name/#/PointingToDeclaration/): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)   <br>
| [ordinal](index.md#tech.whence.echo.dal.dao/Operation/ordinal/#/PointingToDeclaration/)|  [jvm] override val [ordinal](index.md#tech.whence.echo.dal.dao/Operation/ordinal/#/PointingToDeclaration/): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)   <br>
| [savable](index.md#tech.whence.echo.dal.dao/Operation/savable/#/PointingToDeclaration/)|  [jvm] <br><br>Boolean 是否需要保存<br><br>val [savable](index.md#tech.whence.echo.dal.dao/Operation/savable/#/PointingToDeclaration/): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)   <br>

