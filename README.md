# TrailGuard TW — ICEIB 2027 class deliverables

本儲存庫保存 IEEE conference 論文初稿、修改稿及可重現的工具設定方法。

| 項目 | 檔案 |
|---|---|
| 修改前 LaTeX | [versions/draft_before.tex](versions/draft_before.tex) |
| 修改前 PDF（5 頁） | [artifacts/draft_before.pdf](artifacts/draft_before.pdf) |
| 修改後 LaTeX | [main.tex](main.tex) |
| 修改後 PDF（7 頁） | [artifacts/draft_after.pdf](artifacts/draft_after.pdf) |
| 修改與課堂驗收說明 | [docs/revision_notes_zh-TW.txt](docs/revision_notes_zh-TW.txt) |
| 安裝指令與方法 | [docs/installation_zh-TW.txt](docs/installation_zh-TW.txt) |
| 逐行差異 | [docs/revision.patch](docs/revision.patch) |
| 驗證摘要與 SHA-256 | [docs/verification.json](docs/verification.json) |

Overleaf 專案：[2027論文](https://www.overleaf.com/project/6b06c6b088d147181fd08fe6)。
初稿提交：`f5d4196`。修改後版本請看最新 Git 提交。

使用 `IEEEtran` conference 模式，以 pdfLaTeX 編譯。修改稿已在 Overleaf 編譯並逐頁檢查。
本機、Overleaf 與 GitHub 需要明確同步；本儲存庫未設定背景自動同步。

課堂的 olcli MCP 連線已驗證，Overleaf Skill 已安裝。MCP 讀取與編譯成功；上傳因客戶端確認框限制，經授權使用 olcli CLI 完成，沒有停用確認。

正式投稿前仍需補真實作者資料，確認會議最終模板及出版路徑。登山助理系統仍為設計與評估方案，沒有宣稱實作完成或提供虛構實測結果。
