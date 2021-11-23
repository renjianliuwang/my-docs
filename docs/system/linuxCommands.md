# 常用Linux命令

## 常用快捷键

## 处理目录的常用命令
> [参考文档](https://www.runoob.com/linux/linux-file-content-manage.html)

1. ls（英文全拼：list files）: 列出目录及文件名  
`-a` 全部的文件，连同隐藏文件( 开头为 . 的文件) 一起列出来(常用)  
`-d` 仅列出目录本身，而不是列出目录内的文件数据(常用)  
`-l` 长数据串列出，包含文件的属性与权限等等数据；(常用)  

2. cd（英文全拼：change directory）：切换目录  

3. pwd（英文全拼：print work directory）：显示目前的目录  

4. mkdir（英文全拼：make directory）：创建一个新的目录  

5. rmdir（英文全拼：remove directory）：删除一个空的目录  

6. cp（英文全拼：copy file）: 复制文件或目录  

7. rm（英文全拼：remove）: 删除文件或目录  
`-f` 就是 force 的意思，忽略不存在的文件，不会出现警告信息；  
`-i` 互动模式，在删除前会询问使用者是否动作  
`-r` 递归删除啊！最常用在目录的删除了！这是非常危险的选项！！！  

8.mv（英文全拼：move file）: 移动文件与目录，或修改文件与目录的名称  

## 文件内容查看命令
1. cat  由第一行开始显示文件内容
   
2. tac  从最后一行开始显示，可以看出 tac 是 cat 的倒着写！
   
3. nl   显示的时候，顺道输出行号！
   
4. more 一页一页的显示文件内容
   
5. less 与 more 类似，但是比 more 更好的是，他可以往前翻页！
   
6. head 只看头几行
   
7. tail 只看尾巴几行



## 开关机命令
1.`shutdown –h now`  立刻进行关机  
2.`shutdown –r now`  现在重新启动计算机  
3.`reboot`  现在重新启动计算机  
4.`su -`  切换用户  
5.`passwd`  修改用户密码  
6.`logout`  用户注销  






