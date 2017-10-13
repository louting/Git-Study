# GIT 命令学习笔记
git remote -v 显示目前的远程仓库

## 添加新的远程库
```shell
git remote add origin git@github.com:louting/ruby.git
```

## 向多远程库推送代码
    Git同时提交到多个远程仓库
    http://wonux.tech/git-remote.html

```shell
git push all --all
```

## add 与 commit 同时完成
```
git commit -am "commit-comment"
```

## 修改作者和邮件设置
```
git config --global --edit
```