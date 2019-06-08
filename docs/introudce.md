#  kettle介绍

## 简介


JAVA编写的ETL工具，可以在WINDOW、LINUX、UNIX上运行，绿色无需安装。

kettle帮助我们从不同的数据库图形化的方式定义我们想要做如何的数据变化。

kettle有两种脚本文件transformation和job，transformation完成针对数据的基础转换,job完成工作流的控制；

## kettle组件

* spoon是构建jobs和transformations的工具。spoon以拖拽的方式图形化设计,能够通过spoon调用专用的数据集成引擎或者集群。
* pan 独立的命令行程序，用于执行spoon编辑的转换和作业
* kitchen 一个独立的命令行程序，编辑的作业
* carte是一个轻量级的web容器，用于建立专门的、远程的etl server。


