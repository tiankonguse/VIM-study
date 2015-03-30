# vim学习笔记之开始编辑

这个项目已经不再更新，迁移到[这里][vim-path]  


```text
/pattern         从光标开始处向文件尾搜索pattern
?pattern         从光标开始处向文件首搜索pattern
n                在同一方向重复上一次搜索命令
N                在反方向上重复上一次搜索命令
%                查找配对的括号
:s/p1/p2/g       将当前行中所有p1均用p2替代，若要每个替换都向用户询问则应该用gc选项
:n1,n2s/p1/p2/g  将第n1至n2行中所有p1均用p2替代
:g/p1/s//p2/g    将文件中所有p1均用p2替换

.*[]^%~$ 在Vi中具有特殊含义，若需要查找则应该加上转义字符"\"
```

##links
   * [目录](readme.md)



[vim-path]: https://github.com/tiankonguse/empty/tree/master/vim

