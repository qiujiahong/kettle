# json输入

##  案例介绍

## 操作步骤

## 补充知识

* JSON的核心概念

  * 数组： []
  * 对象： {}
  * 属性： key: value

* JSONPath，点记法 

|符号|说明|
|--|--|
|$|查询根节点对象，用于表示一个JSON数据，可以是数组或者对象|
|@|过滤断言处理当前节点对象，类似于JAVA中的THIS|
|*|通配符，可以表示一个名字或数字|
|..|可以理解为递归搜索，deep scan, avaliable anywhere a name is required.|
|.name|表示一个子节点|
|['\<name>'(,'\<name>')]|表示一个或者多个子节点|
|[\<number>(,\<number>)]|表示一个或者多个数组下标|
|[start:end]|数组片段，区间为[start,end)|
|[?(\<expression>)]|过滤表达式表示结果必须为true|



![](./assets/2019-06-08-16-39-45.png)