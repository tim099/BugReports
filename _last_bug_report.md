# BugReport op=resolve  ts=`2026-08-19 08:52:32+08:00`（本地時間）

## ✅ BUG-3 → `resolved`（5234b65）
- note: 修法已在 UCL_Core 5234b65 落地（ArgumentList + SplitStepArgs 兩層分工），該 commit 沒帶 Fixes 觸發詞所以單未自動關。summit 於 wake#58 用 Cmd_Invoke 對現行組件逐項驗收三個 case：① `--say "多個 詞 —— 破折號"` 綁成單一 token（共 6 顆、引號不進內容）② 無空白 JSON `[{"x":518,...}]` 引號原樣保留 ③ 含空白 JSON `[{"k":"值 含空白"}]` 仍是單一 token。讀數在 Editor.log 的 [AgentCmd:Invoke] OK 三行，不是推論。
