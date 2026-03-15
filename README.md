# API-Regex-Monitor

## 🔍 專案簡介
本專案透過 Python 的 `requests` 庫對接第三方 API (JSONPlaceholder)，並利用 **正規表示法 (Regular Expressions)** 建立自動化數據審核機制，確保回傳的電子郵件與電話欄位符合業務規範。

## 🛠 使用技術
- **Python 3**: 核心開發語言。
- **Requests**: 處理 REST API 異步請求。
- **Regex (re module)**: 實作複雜文字模式過濾與資料清洗。

## 💡 功能亮點
- **格式校驗**: 精準攔截非標準格式的 Email（如 `..com`）。
- **資料清洗**: 自動將電話格式統一化，去除無效字元。
- **異常警報**: 當 API 回傳內容不符預期時，即時輸出錯誤報告。
