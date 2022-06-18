# 版本控制

- 记录文件变化,生成版本
  - 查看历史版本
  - 恢复指定版本
  - ....

# 版本控制的发展

- 集中式版本控制
  - SVN(需要联网)
- 分布是版本控制
  - git(不需要联网 本地和远程都有一份)

# Git 三大区域

![三大区域](./%E4%B8%89%E5%A4%A7%E5%8C%BA%E5%9F%9F.png)
![](./%E4%B8%89%E5%A4%A7%E5%8C%BA%E5%9F%9F1.png)
![](./%E5%B7%A5%E4%BD%9C%E5%8C%BA.png)
![](./%E6%9A%82%E5%AD%98%E5%8C%BA.png)
![git仓库](./git%E4%BB%93%E5%BA%93.png)

# 生成版本

![](./%E7%94%9F%E6%88%90%E7%89%88%E6%9C%AC.png)
![](./%E5%85%A8%E5%B1%80%E9%85%8D%E7%BD%AE%E4%BF%A1%E6%81%AF.png)
![](./%E7%94%9F%E6%88%90%E7%89%88%E6%9C%AC1.png)
![](./%E7%94%9F%E6%88%90%E7%89%88%E6%9C%AC2.png)
![](./%E7%94%9F%E6%88%90%E7%89%88%E6%9C%AC3.png)
![](./%E7%94%9F%E6%88%90%E7%89%88%E6%9C%AC4.png)
![](./%E7%94%9F%E6%88%90%E7%89%88%E6%9C%AC5.png)
![](./%E7%94%9F%E6%88%90%E7%89%88%E6%9C%AC6.png)

- git 全局配置用户信息
  - `git config --global user.name 'xxxx'`
  - `git config --global user.email 'yyyy'`
- git init
- git status
- git add xx
- git commit -m 'xxx'
- git log(commit 的提交版本)

# 版本重置

![](./%E9%87%8D%E7%BD%AE%E7%89%88%E6%9C%AC.png)
![](./%E9%87%8D%E7%BD%AE%E7%89%88%E6%9C%AC1.png)

# Git 忽略文件

- .gitignore
- 指定哪些文件不需要 Git 管理

```
# 注释

# 要忽略的文件

# 忽略指定文件，不让 Git 管理
# test.html

# 忽略所有文件名是 test 的文件，不管后缀是什么
test.*

# 忽略所有后缀是 .tmp 的文件，不管文件名是什么
# *.tmp

# 取反，不忽略 test.tmp 文件，让 Git 管理起来
# !test.tmp

# 要忽略的目录（中的文件）
# 空目录会自动被 Git 忽略掉 .gitkeep 占位

# 忽略 node_modules 目录下的所有文件
node_modules/

```

![](./gitignore.png)
![](./gitignore1.png)

# 分支

![](./%E5%88%9B%E5%BB%BA%E5%88%86%E6%94%AF.png)
![](./%E5%88%9B%E5%BB%BA%E5%88%86%E6%94%AF1.png)
![](./%E5%90%88%E5%B9%B6%E5%88%86%E6%94%AF.png)
![](./%E5%90%88%E5%B9%B6%E5%88%86%E6%94%AF1.png)

# 远程仓库

![](./%E4%BB%93%E5%BA%93.png)
![](./%E8%BF%9C%E7%A8%8B%E4%BB%93%E5%BA%93.png)
![](./%E8%BF%9C%E7%A8%8B%E4%BB%93%E5%BA%931.png)
![](./%E8%BF%9C%E7%A8%8B%E4%BB%93%E5%BA%932.png)
![](./%E8%BF%9C%E7%A8%8B%E4%BB%93%E5%BA%933.png)
![](./%E8%BF%9C%E7%A8%8B%E4%BB%93%E5%BA%934.png)
![](./%E8%BF%9C%E7%A8%8B%E4%BB%93%E5%BA%935.png)