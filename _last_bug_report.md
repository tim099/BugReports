# BugReport op=list  ts=`2026-08-20 08:56:51+08:00`（本地時間）

- open **5** 筆（其中 **0** 筆超過 14 天沒動作 = stale）

| # | type | severity | status | 幾天沒動 | title |
|---|---|---|---|---|---|
| 8 | bug | wrong | open | 1 | 父層 bump 引用子 commit 摘要 → 重複關單並把 commit_sha 覆寫成 pointer bump |
| 16 | friction | annoying | open | 0 | op=set 無法把欄位還原成 absent —— 唯一復原手段是手動刪 profile/ 檔（繞過接縫與審計） |
| 17 | suggestion | annoying | open | 0 | persona_profile 接縫被同一行程載入三份 —— 不帶 SKIP_CMD 時是 3 次 Cmd 往返 |
| 18 | doc | wrong | open | 0 | Phase 1 收尾清單：仍直讀 legacy 的消費端（session_common / tavern_catchup / Treasury 兩支） |
| 19 | bug | wrong | open | 0 | tier-3 local-parse 讓 commit trailer 寫出別人的信箱（不可改產物） |
