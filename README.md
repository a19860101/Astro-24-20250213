# Git

```bash
# 設定姓名
git config --global user.name your_name
# 設定email
git config --global user.email your_email
# 查詢設定
git config --list

# 初始化專案
git init

#查看狀態
git status

# 加入追蹤/暫存
git add .

# 加入儲存庫
git commit -m '訊息'

# 查詢版本
git log
git log --oneline

# 查詢完整版本(包含reset)
git reflog

# 硬回復
git reset 版本號 --hard

# 建立連線
git remote add origin 連線位置
# origin 是連線名稱 可以修改

# 上傳到雲端儲存庫
git push origin master

# 查詢分支
git branch
```