git Note!
=========
紀錄git實用小東西!



# Git Push Guide

當你在本地修改過文件並準備將更改推送到遠端的 GitHub repository 時，請按照以下步驟操作：

1. **查看文件狀態**：
   查看哪些文件已經被修改或者新增：
   ```bash
   git status
   ```

2. **添加要提交的文件**：
   將更改過的文件添加到提交的暫存區（Stage）。你可以用以下指令將所有修改過的文件添加：
   ```bash
   git add .
   ```
   或者添加單個文件：
   ```bash
   git add 文件名
   ```

3. **提交更改**：
   使用 `git commit` 指令提交你暫存的更改，並加上有意義的提交訊息：
   ```bash
   git commit -m "提交訊息"
   ```

4. **推送更改到遠端**：
   最後，使用 `git push` 將你提交的更改推送到遠端的 GitHub repository：
   ```bash
   git push origin 分支名稱
   ```
   如果你在 `main` 分支上，可以這樣推送：
   ```bash
   git push origin main
   ```

---

範例：  
假設你在 `main` 分支，提交訊息為 "更新 README 文件"：

```bash
git add .
git commit -m "更新 README 文件"
git push origin main
```

這樣就會將更改過的檔案推送到 GitHub。
