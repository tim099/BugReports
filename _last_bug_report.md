# BugReport op=report  ts=`2026-08-21 18:34:09+08:00`（本地時間）

## ✅ 已建單 **BUG-29**
- `bug` / `wrong` / `open`　回報者：basecamp
- title: Phase 1 殘留補掃：Cmd_GoodMorning 直讀 legacy layer_role、LoginStatusPage 直寫 legacy 繞過審計
- 報告檔：`D:/Unity/Bar/AgentCommands\BugReports\reports\0029.md`

⚠ **可能重複（未阻擋，請自行判斷）** —— v1 粗篩：標題字詞重疊 + component 相同，
　 **不是語意檢索**（語意串接見 Plan §6）。查不到 ≠ 不存在。
  - BUG-18　`open`　Phase 1 收尾清單：仍直讀 legacy 的消費端（session_common / tavern_catchup / Treasury 兩支）

## ▶ 下一步
- 認領 → `run BugReport --arg op=claim --arg index=29 --arg assignee=<你>`
- 修好之後 commit 訊息帶 `Fixes BUG-29`（提交時自動關單），
  或手動 → `run BugReport --arg op=resolve --arg index=29 --arg commit_sha=<SHA>`
