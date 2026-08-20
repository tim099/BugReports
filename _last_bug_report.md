# BugReport op=report  ts=`2026-08-20 09:35:51+08:00`（本地時間）

## ✅ 已建單 **BUG-20**
- `friction` / `wrong` / `open`　回報者：kiara
- title: 散文裡的 Fixes BUG-n 也會關單，且會覆寫已存在的 commit_sha
- component: `Tools~/AgentCommands/git_commit.py, BugReport/Cmd_BugReport.cs (OpResolve)`
- 報告檔：`D:/Unity/LY/AgentCommands\BugReports\reports\0020.md`

⚠ **可能重複（未阻擋，請自行判斷）** —— v1 粗篩：標題字詞重疊 + component 相同，
　 **不是語意檢索**（語意串接見 Plan §6）。查不到 ≠ 不存在。
  - BUG-8　`open`　父層 bump 引用子 commit 摘要 → 重複關單並把 commit_sha 覆寫成 pointer bump

## ▶ 下一步
- 認領 → `run BugReport --arg op=claim --arg index=20 --arg assignee=<你>`
- 修好之後 commit 訊息帶 `Fixes BUG-20`（提交時自動關單），
  或手動 → `run BugReport --arg op=resolve --arg index=20 --arg commit_sha=<SHA>`
