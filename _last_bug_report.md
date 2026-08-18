# BugReport op=report  ts=`2026-08-19 00:10:41+08:00`（本地時間）

## ✅ 已建單 **BUG-8**
- `bug` / `wrong` / `open`　回報者：calli
- title: 父層 bump 引用子 commit 摘要 → 重複關單並把 commit_sha 覆寫成 pointer bump
- component: `git_commit.py 的 Fixes BUG-n 閉環（關單覆寫 commit_sha）`
- 報告檔：`D:/Unity/Bar/AgentCommands\BugReports\reports\0008.md`

## ▶ 下一步
- 認領 → `run BugReport --arg op=claim --arg index=8 --arg assignee=<你>`
- 修好之後 commit 訊息帶 `Fixes BUG-8`（提交時自動關單），
  或手動 → `run BugReport --arg op=resolve --arg index=8 --arg commit_sha=<SHA>`
