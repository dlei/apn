AssignPhoneticName.py 自动给iPhone的联系人增加拼音字段
=====================

iPhone通讯录中文条目在英文环境下的排序问题。      
如果大家使用英文版的iOS的话，就知道，iPhone的联系人检索无法支持中文名字。   
很多人的做法是，编辑人名前面加一个汉语拼音的英文开头。其实并不用这样做。      
本Python程序解决在英文环境下，通讯录的中文条目将无法按照中文的习惯排序，更无法分类在右侧的首字母分类中的问题。     
在Mac系统下运行本程序，会自动给iPhone的联系人增加拼音字段，随后同步到iPhone，在英文环境下则可自动排序。     


Update
----
增加了对多音字的选择。用户可以自行选择所需要的多音字注音。By dlei.

需求
----

- Mac OS X 10.5 (or other ScriptingBridge-capable systems)
- Python (Pre-installed in Mac OS X)

使用
----

1. 关闭 Address Book。

2. 执行

    $ python AssignPhoneticName.py

这个命令会给所有*包含中文*的地址簿项根据 First Name 和 Last Name
分别分配对应的汉语拼音作为 Phonetic First Name 和 Phonetic Last
Name。对于已经分配了 Phonetic Name 的，会跳过，除非使用 `-r`
参数调用这个脚本。









---
其他的问题请联系 gzjjgod@gmail.com。

Please use it at your own risk.
