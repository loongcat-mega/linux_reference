list directory contents 命令用于显示指定工作目录下之内容（列出目前工作目录所含的文件及子目录)

```bash
 ls [-alrtAFR] [name...]
```

```bash
a			显示所有文件及目录，.开头的隐藏文件也会列出
d			只列出目录
l			以常格式显示文件和目录信息
r			以倒序显示文件和目录
t			按照修改时间排序，最新的文件在最前面
A			同a，但不列出. 和 ..
F			在列出的文件名称后加一符号，可执行文档"*",目录"/"
R			递归显示目录中所有的文件和目录
h			以人类可读的方式显示
```

![image.png](https://yaaame-1317851743.cos.ap-beijing.myqcloud.com/20240106160350.png)
-   **第一列**共10位，第1位表示文档类型，`d`表示目录，`-`表示文件，`l`表示链接文件，`d`表示可随机存取的设备，如U盘等，`c`表示一次性读取设备，如鼠标、键盘等。后9位，依次对应三种身份所拥有的权限，身份顺序为：owner、group、others，权限顺序为：readable、writable、executable。如：`-r-xr-x---`的含义为**当前文档是一个文件，拥有者可读、可执行，同一个群组下的用户，可读、可执行，其他人没有任何权限**。
-   **第二列**表示链接数，表示有多少个文件链接到inode号码。
-   **第三列**表示拥有者
-   **第四列**表示所属群组
-   **第五列**表示文档容量大小，单位字节
-   **第六-八列**表示文档最后修改时间，注意不是文档的创建时间哦
-   **第九列**表示文档名称。以点(.)开头的是隐藏文档
![image.png](https://yaaame-1317851743.cos.ap-beijing.myqcloud.com/20240106160411.png)

![image.png](https://yaaame-1317851743.cos.ap-beijing.myqcloud.com/20240106160924.png)
