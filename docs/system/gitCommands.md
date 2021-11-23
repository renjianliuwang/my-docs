# 常用git命令

## 账号切换
1. 查看配置
```bash
$ git config --list
$ git config user.name
$ git config user.email
```
2. 全局范围内修改账号
```bash
$ git config --global user.name "test"
$ git config --global user.email "test@163.com"
```
3. 项目范围内修改账号
```bash
$ git config user.name "test"
$ git config user.email "test@163.com"
```
4. 单次提交修改作者
```bash
# 仅针对即将到来commit，可覆盖下一个提交者信息：
$ git commit --author="test <test@163.com>"
# 对最近一次提交执行修改作者
$ git commit --amend --author="test <test@163.com>"
```
5. git Interactive Rebase
[详情参考](https://cs.xieyonghui.com/git/git-change-account-terminal_85.html)

## 常用命令
>[参考文档](https://www.ruanyifeng.com/blog/2015/12/git-cheat-sheet.html)
1. git add
```bash
# 添加指定文件
$ git add test.ts
# 添加所有内容
$ git add .
```
2. git commit
```bash
# 提交工作区自上次commit之后的变化，直接到仓库区
$ git commit -a
# 提交时显示所有diff信息
$ git commit -v
# 添加提交说明
$ git commit -m "feat: 新增操作日志"
```
3. git pull  
4. git push  

## 冲突合并

