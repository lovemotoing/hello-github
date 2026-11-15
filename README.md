# hello-github

我的第一个 GitHub 练习仓库，用来跑通 `clone → 修改 → commit → push` 这条流程。

账号：lovemotoing · 创建于 2026-11-15

## 常用命令

| 命令 | 作用 |
| --- | --- |
| `git status` | 查看当前改动 |
| `git add .` | 把改动放进暂存区 |
| `git commit -m "说明"` | 保存一次快照 |
| `git pull` | 拉取云端最新内容 |
| `git push` | 推送到 GitHub |

## 第一次推送

```bash
git push -u origin main
```

第一次会弹出浏览器让你登录 GitHub，授权完成后代码就上传了。之后推送不用再登录。

## 试试看

改一下这个文件，然后提交一次：

```bash
git add README.md
git commit -m "更新 README"
git push
```

## 提醒

`.gitignore` 已经排除了 `.env`、密钥文件、`node_modules` 等。不要把密码或 token 写进代码提交上来。
