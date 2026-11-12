# S02｜Building effective agents

- 作者／機構：Anthropic
- 類型：工程研究文章
- URL：https://www.anthropic.com/research/building-effective-agents
- 閱讀日期：2026-11-12

## 閱讀摘記

文章把 agentic systems 分成固定程式路徑編排的 workflows，以及由 LLM 動態決定步驟與工具使用的 agents。兩者界線可依文章定義理解，日常用語未必一致。作者建議先從最簡單可行方案開始，因為 agentic 系統可能用更高延遲與成本換取任務表現；按需要再加入 prompt chaining、routing、parallelization、orchestrator-workers 或 evaluator-optimizer 等模式。

## 支持的 Wiki 主張

- 工作流程和 Agent 的自主程度不同，並非所有 LLM 應用都需要 Agent。
- 需要依任務不確定性、成本和錯誤後果選擇流程複雜度。

## 限制

這是 Anthropic 的工程經驗文章，不是跨系統的統一術語標準，也不能直接推成每個任務的量化效益。
