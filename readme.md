# 兼职人员的认证

## git

兼职人员至少会使用如下命令：

* clone
* config
* log
* branch
* checkout
* add
* commit
* pull
* push
* diff
* merge
* mv
* rm
* show
* status

兼职人员应该能熟练应付如下场景：

1. 克隆远端库到本地
2. 设定自己的用户名和邮箱
3. 查看库提交历史
4. 查看库中拥有哪些分支
5. 切换分支
6. 添加新文件
7. 提交修改到本地库
8. 从远端拉取新数据
9. 将本地修改提交到远端
10. 创建新分支
11. 文件改名
12. 删除文件
13. 查看当前工作区状态
14. 分支合并
15. 查看文件修改了哪些地方
16. 提交的日志清晰明了。

## php

### 代码规范

<!-- [code standards](http://pear.php.net/manual/en/standards.php "code standards") -->

推荐使用的编辑器为 [Aptana Studio](http://www.aptana.com/ "Aptana Studio")
以编辑器默认代码风格为准。

#### 规定

* 文件格式
    * 文件在包含多字节字符时，使用UTF-8编码。
    * 使用UNIX格式结束符。
    * 代码中不允许以空格结尾。
    * 在文件最后，不要有无用的空行。
    * 在不需要被请求的页面开头，添加判断并适当的时候结束请求
      比如 defined('ROOTPATH') or die('No direct script access.');

* 命名规范
    * 文件夹/文件名统一全部使用小写,需要时可用下划线
    * 根据功能将文件放在不同文件夹
    * 类
      * 类文件统一放在classes文件夹
      * 类名由一个或多个名词由下划线组成
      * 类名应包含classes下开始的各级路径名  
        例如： 文件 classes/view/exception.php，对应类名应该是 View_Exception
    * 测试
      * 测试使用phpunit框架
      * 测试的文件名使用驼峰法命名，首字母大写，附带Test后缀。  
        例如： 文件 tests/kohana/ArrTest.php， 对应类名为 Kohana_ArrTest

### 试题

#### php技能题

1. 请编写一个函数，返回前天的日期字符串。
2. 请编写一个函数，返回输入字符串的反转字符串，可以使用php内建函数。
3. 题目三
4. 题目四

#### php测试题

请针对php技能题，写出对应测试用例
