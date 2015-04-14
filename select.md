# vim 学习笔记之选择

在可视化模式中，我们可以选择文本。  

一般使用`v`命令进入可视化模式，　使用`V`或`shift+v`命令进入可视化行选择模式。  


在可视化模式中，有几个方便的快捷键可以使用。  


## 结对符号选择

比如这里有个字符串，　光标在字符串之间，你按入`shift+v i "`, 发现字符串都选中了。  

```
hello "hello word" word
```

如果你键入`shift+v a "`的话，两个引号也选择了。  

这个方法同样适合与小括号，中括号，大括号，尖括号，双引号，单引号等成对符号。  


```
this is (content) end.
this is [content] end.
this is {content} end.
this is <content> end.
this is "content" end.
this is 'content' end.
this is `content` end.
other test $content$ end.
```

## 语法选择


我们知道 `w`在vim中代表一个单词，　`b`代表一块，　`s`代表一句，　`p` 代表一段。  

于是我们可以根据这个来快速选择。  





