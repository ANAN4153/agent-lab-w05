# My lab evidence / 我的實作紀錄

- Group code / 組別：個人實作（請依課程要求填寫正式組別代碼）
- Tool / 工具：GitHub Web editor、Google Chrome
- Route / 路線：individual 個人
- Tasks completed / 完成題目：A、B v1、B v2、D
- Material / 素材：NDHU classroom tasks 東華課堂版
- For original-pack work / 原版實作：不適用，本次依課堂版任務完成
- My role and what I checked / 我的角色與實際檢查：本人透過 GitHub 網頁編輯器建立及修改檔案，檢查提交歷史，並在瀏覽器開啟活動選擇器查看介面。

## Scope and plan / 範圍與計畫

**Allowed input and output folders / 可讀取與輸出的資料夾：**

- Input：`practice/01-club-files/input/`
- Activity data：`practice/02-campus-picker/activities.json`
- Output：`practice/01-club-files/output/`、`practice/02-campus-picker/output/`、`practice/04-review/`、`evidence/`

**What I asked for / 原始需求：**

完成 A、B v1、B v2、D 任務，整理模擬社團活動資料、製作活動選擇器、改善介面，並審查不安全的模擬計畫。

**What I checked before execution / 動手前我檢查了什麼：**

閱讀課堂任務要求與提供的模擬資料，確認原始 `activities.json` 不應修改，活動選擇器需要支援地點、時間、強度篩選、中英文切換及抽選紀錄。

## Tests actually performed / 我真的做過的測試

| Test / 測試 | Expected / 預期 | Observed / 實際 | Evidence / 證據 |
|---|---|---|---|
| 1. 開啟活動選擇器 | 頁面正常顯示 | 已在瀏覽器開啟並查看，畫面看起來正常 | 待補活動選擇器截圖 |
| 2. GitHub 提交歷史 | A、B v1、B v2、D 均有提交紀錄 | 已確認四筆提交存在 | 待補 commit-history 截圖 |

## One revision / 一次修改

**Before / 原來的情況：**

活動選擇器沒有集中顯示目前使用者選取的篩選條件。

**Request / 我提出的修改：**

在結果區新增目前篩選條件摘要，並在條件變更及切換語言時更新。

**After and retest / 修改後與重測結果：**

已修改程式碼並提交 B v2。條件摘要及中英文同步更新的完整行為仍需進一步測試。

**New requirement or defect? / 新需求還是原規格未做到？**

屬於介面改善需求，讓目前選取的條件更容易辨識。

## One rejection / 一次退回

**Which action I reject and why / 退回哪個動作、為什麼：**

拒絕直接整理整個 Downloads 資料夾、刪除重複檔案、自行認定 `final2` 是最新版、編造缺失資料，以及未經同意公開成果。這些操作可能造成資料遺失、資訊錯誤或隱私外洩。

**An acceptable alternative / 可以怎麼改：**

先列出檔案及疑似重複項目，根據可查證的資訊比較版本；缺失資料標記為未知。任何刪除、移動或公開操作，都應先提出計畫並取得使用者明確同意。

## Still unverified / 還沒驗證

- 活動選擇器的所有篩選組合與隨機抽選結果尚未完整測試。
- 最近五次紀錄、清除紀錄、重設篩選及中英文切換仍需逐項驗收。
- B v2 的條件摘要需要實際測試，確認選項變更與語言切換時都會正確更新。
- 尚未完成所有必要測試截圖的整理與提交。

## Repository / 倉庫

https://github.com/ANAN4153/agent-lab-w05
