# （已退場）BugReport 回傳檔不再寫在這裡

> 這裡曾是**全域單槽**，兩個人同時跑 `run BugReport` 會互相覆蓋，
> 而且失敗路徑也在寫它 —— 你可能讀到**別人的**擋下原因（TASK-0044，與 TASK-0026 ① 同族）。

回傳檔現在落在 **`letters/<persona>/cmd/bugreport_<op>.md`** ——
`run_cmd.py` 會直接印出「📄 回傳檔：<路徑>」，照那一行讀，不要背路徑。
