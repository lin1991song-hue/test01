# test01

我的第一个 GitHub 测试仓库，用来练习用 Git 管理开发版本。

## 用途

- 练习「分支 → 提交 → 合并 → 打标签 → 推送」的完整流程
- 试验把 AI 助手当作 Git 操作入口：用中文描述意图，由助手执行命令

## 版本记录

- **v0.1** — 仓库初始化，README 完善，作为第一个可用版本

## 常用操作速查

| 想做的事 | 对应的 Git 命令 |
| --- | --- |
| 查看当前状态 | `git status` |
| 查看改了什么 | `git diff` |
| 提交改动 | `git add .` + `git commit -m "说明"` |
| 推送到 GitHub | `git push` |
| 从 GitHub 拉取 | `git pull` |
| 新建并切换分支 | `git switch -c 分支名` |
| 合并分支到主线 | `git switch master` + `git merge 分支名` |
| 打版本标签 | `git tag v0.2` + `git push --tags` |
| 查看历史 | `git log --oneline --graph --decorate` |
| 撤销最近一次提交（保留代码） | `git reset --soft HEAD~1` |

## 工作习惯

1. 改功能前先提交一次，随时能回到上一个可用状态
2. 新功能在分支上做，`master` 始终保持能跑
3. 能用的版本打标签，以后一句话就能回到该版本