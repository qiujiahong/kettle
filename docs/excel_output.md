#  excel输出 

## 案列介绍

从MySQL数据库中读取user表，插入到excel文件.xls和xlsx中。


## 操作步骤

*  数据库准备  

```SQL
    DROP TABLE IF EXISTS `user`;

    CREATE TABLE `user`(
        `id` INT(11) NOT NULL AUTO_INCREMENT,
        `name` VARCHAR(20),
        `age` INT(3),
        PRIMARY KEY (`id`)
    );

    INSERT INTO `user` (`name`,`age`) VALUES('nick',21),('jone',21),('nacy',22);
```

* 创建表输入、excel output 和excel writer  （注： 连接第二个连线的时候选择复制）

![](./assets/2019-06-09-09-46-09.png) 

* 配置表输入，参考[该文](table.md)

* 配置excel output 
![](./assets/2019-06-09-09-48-21.png)  
![](./assets/2019-06-09-09-48-30.png)

* 配置excel writer 
![](./assets/2019-06-09-09-56-00.png)

![](./assets/2019-06-09-09-56-12.png)


* 执行检查效果  

![](./assets/2019-06-09-09-56-50.png)

![](./assets/2019-06-09-09-57-02.png)


