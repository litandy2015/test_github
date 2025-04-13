建立一个文件夹，然后在该文件夹下执行命令
```bash
git init
git add ./*
git commit -m "some note"
```
然后执行
```bash
git remote add origin git@github.com:litandy2015/test_github.git
```
设置这个文档将要被推送到的远端服务器
然后执行
```bash
git branch -M main
git push -u origin main
```
将主分支设置成main，然后将更改推送到远程服务器