# CLAUDE.md

## 專案資訊
- **專案名稱**: 學習重點圖表畫-學生作品
- **用途**: 學生學習重點整理
- **部署**: GitHub Pages
- **GitHub**: 公開

## 工作流程
### 開工
1. 讀取 CLAUDE.md 了解專案結構
2. 讀取 Obsidian 工作筆記
3. 執行 `git status` 確認狀態
4. 回報下一步計畫

### 收工
1. 檢查是否有敏感資料洩漏
2. 更新 Obsidian 工作筆記
3. 執行 `git commit` 與 `git push`
4. 執行 `chezmoi` 同步

## 程式碼規範
- 使用中文註解
- 保持檔案結構清晰
- 定期提交並推送變更

## 目錄結構
```
├── CLAUDE.md          # Claude Code 工作說明
├── README.md          # 專案說明
├── .gitignore         # Git 忽略規則
└── [其他檔案]
```
