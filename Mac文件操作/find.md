# find命令

`find`命令主要用于使用匹配表达式查找文件。

## 查找文件后缀名为html的文件

```powershell
find *.html
```

![png](../img/find_1.png)

## 查找文件后缀名为html的文件，同时也会检索子目录

```powershell
find . -name "*.js"
```

![png](../img/find_2.png)