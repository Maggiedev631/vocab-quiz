# 單字小考 Vocab Quiz

1200 單字小考出卷工具：輸入範圍（例如 T24-T43）→ 亂序 → 下載 PDF（含老師答案版），網頁上可依 No. 查看答案與例句。

- `index.html`：網頁
- `bank.json`：1200 單題庫（編號 → [英文, 中文]）
- `sentences.json`：例句（編號 → [英文例句, 中文翻譯]）

同一個範圍＋題型＋No. 永遠是同一個順序，所以在任何電腦或手機輸入範圍和 No. 都能看到同一份答案。

## 拼字練習（學生版＋老師端）
- `spell.html`：學生用。選名字、輸入密碼後練習，每次練完成績自動上傳。
- `teacher.html`：老師用（拼字之星老師帳號登入）。看每位學生的練習紀錄、常錯字，新增學生、改密碼。
- 資料存在 Firebase 專案 `amc-spelling-star`（vq_students / vq_secrets / vq_login / vq_results）。第一次使用要到老師端「設定」複製規則貼到 Firebase。
