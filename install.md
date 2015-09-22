# 安装 #

需求：
php 和 mysql 扩展.
mysql 数据库

# 步骤 #

  * 下载 php 脚本，在 .bashrc 或者 .bash\_alias 中添加以下命令
  * alias dict='php PATH\_TO\_YOUR\_SCRIPT.php'
  * 在 mysql 中创建 test 数据库
  * 导入 test.sql 到 test 数据库
  * 更改 dict.php 中的数据库用户名和密码

参数

dict hello 查询单词
dict -l hello 查询相近的单词
dict -e hello 查询单词的例句