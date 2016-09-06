# vim学习笔记之屏幕操作

```text
Ctrl-w, w 后一个frame
Ctrl-w, p 前一个frame
Ctrl-w, h 光标移动到左面的frame
Ctrl-w, j 光标移动到下面的frame
Ctrl-w, k 光标移动到上面的frame
Ctrl-w, l 光标移动到右面的frame
Ctrl-w, r  交换两个frame

:new 上下分屏, 上面是新建文件. 快捷键 ctrl-w, n
:split 上下分屏, 将当前工作区复制一份. Ctrl-w , s
:vsplit 左右分屏。将当前工作区复制一份。快捷键 Ctrl-w, v.
:vsp filename 左右分割frame
:sp filename 上下分割frame
:only 取消分屏。将其他工作区关闭，只保留当前工作区。快捷键 Ctrl-w, o.
:close, 关闭当前分屏。快捷键 Ctrl-w , c.
:tabc 关闭当前窗口
:tabo 关闭所有窗口
:resize num  例如：:res 5，显示行数调整为5行
:resize+num 把当前窗口高度增加num行
:resize-num 把当前窗口高度减少num行

:vertical resize num 指定当前窗口为num列
:vertical resize+num 把当前窗口增加num列
:vertical resize-num 把当前窗口减少num列
:f file 给窗口重命名

:n 跳至下一个文件
:n c 可以直接跳到c文件
:e# 回到刚才编辑的文件
:Sex 水平分割当前窗口，并在一个窗口中开启目录浏览器
:ls 显示当前buffer情况

:shell 可以在不关闭vi的情况下切换到shell命令行
:exit 从shell回到vi
```


##links

* [目录](readme.md)


## 参考链接

* [vim分屏显示操作](http://tiankonguse.com/record/record.php?id=543)
* [vim多窗口使用技巧](http://blog.csdn.net/devil_2009/article/details/7006113)
