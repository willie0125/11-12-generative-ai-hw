# S01｜LLM Wiki

- 作者：Andrej Karpathy
- 類型：概念說明 gist
- URL：https://gist.github.com/karpathy/442a6bf555914893e9891c11519de94f
- 閱讀日期：2026-11-12

## 閱讀摘記

Karpathy 提出把原始文件整理成持續維護、彼此連結的 Markdown Wiki。新增來源時，LLM 讀取資料、抽取重點、更新相關知識頁並記錄異同；查詢時先從索引定位頁面；定期檢查矛盾、過時內容、孤立頁和知識缺口。來源層保持原樣，Wiki 層負責綜整，schema 文件則定義維護程序。

## 本作業採用方式

採用 `raw/`、`wiki/`、schema、索引和日誌的分層概念。這是小型課程作業示範，不是 Karpathy 官方軟體，也沒有聲稱以特定平台自動 ingest。

## 限制

這是工作模式提案，不是實驗比較或準確率保證；整理後的 Wiki 仍需回看來源。
