#vim学习笔记之启动vim


## 基本操作

最常用的打开vim的方法是以打开文件的方式进入vim的.  

比如 `vim fileName` 或 `vim filePath`  


## 打开备份文件


我们会看到使用vim编辑文件的时候,会生成一个波浪线后缀的备份文件.  

既然右只个备份文件, 那我们文件异常关闭时,怎么使用备份文件呢?  

这个时候使用 -r 参数就行了.  

比如:  


```
vim -r fileName
```

## 其他操作


还有一些不常用的打开方式.  

比如以只读打开,比如指定打开后光标位置.  


### 只读打开,可以强制保存

```
vim -R fileName
```


### 只读打开,不能强制保存

```
vim -M fileName
```

### 打开后光标定位到文件末尾

```
vim + fileName
```


### 其他打开姿势

由于很多打开姿势都可以先打开文件,然后在操作相同的功能.  

所以这里就不多介绍了.  







