## Git-Practice

### git rebase - 指令

#### 重新命名 commit

1. 輸入 ` git rebase -i HEAD~n `

2. 使用 ` i ` 插入 ，將 ` pick ` 改為 ` edit ` ，輸入` :wq ` 保存並退出 ，接著按 ` Enter `

3. 輸入 ` git commit --amend ` 修改 commit 訊息

4. 輸入 ` git rebase --continue ` 

5. 輸入 ` git push --force ` ( 如果已經推送到遠端倉庫 )