`git branch-filter`用来根据某些规则来重写大量的提交记录。

基于差异（`delta-based`）

git中所有的数据在存储前都计算校验和，然后以校验和来引用。

通过以下命令查看所有的配置以及它们所在的文件：

```sh
git config --list --show-origin
```

可以尝试在freenode IRC服务器`https://freenode.net`上的`#git`或`#github`频道寻求帮助。

`git status`命令的输出十分详细，但其用语有些繁琐。Git有一个选项可以帮你缩短状态命令的输出，这样可以以简洁的方式查看更改。如果你使用`git status -s`或`git status --short`，你将得到一种格式更为紧凑的输出。
