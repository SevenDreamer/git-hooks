# 一些不起眼的钩子
## Obsidian
### pre-commit
在进行 commit 的时候会将 .obsidian 和其他文件分成两个commit 进行提交
### pre-push
在进行 push 的时候会将 最近一次的关于 .obsidian 的那次提交，将 .obsidian 重命名为 .obsidian_<git username>，然后push

### post-merge
在进行 pull 的时候会还原你的 .obsidian 目录