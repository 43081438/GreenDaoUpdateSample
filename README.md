# GreenDao版本升级

实现思路是：

- 1、创建临时表temporary，将原先表数据迁移过去

- 2、删除所有原表

- 3、创建新表

- 4、将temporary表数据复制到新表，最后将temporary表删除