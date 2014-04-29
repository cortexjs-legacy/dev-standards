# git comments

本文说明如何写更好的 git comments。

## 例如

一个比较好的 comment 可能是这样的：

    commmand/publish: adds more hints if remote registry server is down. fixes #122

## 规范

#### 包含 issue 号

包含与本次提交相关的 issue 号，格式为 `#<issue>`，可以参见 [Github Flavored Markdown](https://help.github.com/articles/github-flavored-markdown#references)。

- 如果某一次提交完全修复了某个 issue，请在注释中注明：`fixes #<issue>`，这样在该 commit 提交到远程服务器，或者 pull request 被接受后，相关 issue 会被自动关闭
- 如果某一次提交完全修复了某个 issue，但是忘记在注释中注明，请到该 issue 的页面中加入评论 `fixed by <commit-sha>`，并关闭该 issue。
    
#### 描述工作
    
描述本次提交所做的事情，避免类似 "just a commit", "bug fixes" 的注释。

#### 使用英文

#### 子系统

应当包含本次提交所属的子系统的名字，如 "command/install: " 表明是与 `cortex install` 命令相关的改动。

对于比较小的项目，这一点可以不作要求。

