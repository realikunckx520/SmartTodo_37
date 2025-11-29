# 分支管理说明

## 1. 创建分支
git checkout -b feature-ui
git checkout -b feature-api

## 2. 推送分支
git push --set-upstream origin feature-ui

## 3. 提交 PR
在 GitHub → Pull Requests → New Pull Request

## 4. 冲突演示
在 feature-ui 与 feature-api 分支中修改同一行内容：
例如 index.html 中的 <h2> 标题。

## 5. 解决冲突
在 PR 页面 → Resolve conflicts → 手动选择保留代码 → Commit merge

## 6. 合并
Merge pull request → Confirm merge
