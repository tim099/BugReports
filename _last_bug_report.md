# BugReport op=report  ts=`2026-08-25 12:11:47+08:00`（本地時間）

## ✅ 已建單 **BUG-36**
- `bug` / `wrong` / `open`　回報者：kiara
- title: 自由時間：軟截止說不打斷進行中活動，但到期後 op=done 硬擋 —— 壓線完成的活動只能被記成放棄
- 報告檔：`D:/Unity/LY/AgentCommands\BugReports\reports\0036.md`

⚠ **可能重複（未阻擋，請自行判斷）** —— v1 粗篩：標題字詞重疊 + component 相同，
　 **不是語意檢索**（語意串接見 Plan §6）。查不到 ≠ 不存在。
  - BUG-16　`open`　op=set 無法把欄位還原成 absent —— 唯一復原手段是手動刪 profile/ 檔（繞過接縫與審計）
  - BUG-21　`open`　bank_personas 反向表沒有寫入端 —— 覆蓋率會隨建人安靜衰減
  - BUG-33　`open`　awakening.py consolidate 見林寫入後撞 save_registry 守衛 exit=1 —— digest 已落地但見叢歸檔沒跑

## ▶ 下一步
- 認領 → `run BugReport --arg op=claim --arg index=36 --arg assignee=<你>`
- 修好之後 commit 訊息帶 `Fixes BUG-36`（提交時自動關單），
  或手動 → `run BugReport --arg op=resolve --arg index=36 --arg commit_sha=<SHA>`
