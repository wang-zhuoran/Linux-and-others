# Linux基础
 - ``linux``的文件是成树形结构的
 - ``bin``中一般存可执行文件，``lib``中一般存静态链接库，``home``是用户文件，也是使用linux系统时最开始的地方。根目录是```/```
## 1. 常用文件管理命令
```ls```
![ls](https://github.com/wang-zhuoran/Linux-and-others/blob/main/Linux-notes/img/ls.PNG)
 ```cd```
![cd](img/cd.png)
```mkdir```
![mkdir](img/mkdir.png)
- 绝对路径  
- 相对路径  
    开头是```/```就是绝对路径，相对路径开头一定不是```/```  
- ```.```是当前目录 ```..```是上级目录
- ```~/```家目录
- ```ctrl+c```强制终止
- ```ctrl+u```清空本行命令

1. ```ctrl c```: 取消命令，并且换行  
2. ```ctrl u```: 清空本行命令  
3. ```tab```键：可以补全命令和文件名，如果补全不了快速按两下tab键，可以显示备选选项
4. ```ls```: 列出当前目录下所有文件，蓝色的是文件夹，白色的是普通文件，绿色的是可执行文件
5. ```pwd```: 显示当前路径
6. ```cd XXX```: 进入XXX目录下, ```cd .. ```返回上层目录
7. ```cp XXX YYY```: 将XXX文件复制成YYY，XXX和YYY可以是一个路径，比如../dir_c/a.txt，表示上层目录下的dir_c文件夹下的文件a.txt
8. ```mkdir XXX```: 创建目录XXX
9. ```rm XXX```: 删除普通文件;  rm XXX -r: 删除文件夹
10. ```mv XXX YYY```: 将XXX文件移动到YYY，和cp命令一样，XXX和YYY可以是一个路径；重命名也是用这个命令
11. ```touch XXX```: 创建一个文件
12. ```cat XXX```: 展示文件XXX中的内容
13. 复制文本
        windows/Linux下：```Ctrl + insert```，Mac下：```command + c```
14. 粘贴文本
        windows/Linux下：```Shift + insert```，Mac下：```command + v```


