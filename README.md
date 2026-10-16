# Hytech SSC — Employee V3 v0.4（HR × Finance 靜態概念）

獨立於 [Finance SSC V2](https://paician.github.io/Finance-SSC-Static-Demo/?role=employee) 的 HR／Finance 統一服務入口。V2 不修改；本網站為可互動 UX Demo，**不接任何正式 HR、Finance、Lark API 或資料庫**，也不屬於 2026 年年底 Production 上線承諾或 AWS 預算。

- **GitHub Pages**：[Hytech SSC V3 Demo](https://paician.github.io/Finance-SSC-StaticV3-Demo/)
- 可下載本 Repository 後直接開啟 `index.html`，不需 npm、build、Docker 或外部語言套件。

## 本版調整（v0.4）

1. 馬來西亞假日示意：`2026-11-08`、**Deepavali (Regional Holiday)**，地區 **Malaysia**；首頁示範初始日曆設為 2026 年 11 月、Malaysia，以便直接看到該事件。區域假日的實際適用性需由 HR 與 Lark 共用行事曆核實。
2. **Employee／Manager 角色切換移至左上角**原角色標籤，右上角保留使用者資訊，不再放角色選單。
3. **語系自動依瀏覽器判斷**：繁體中文 `zh-TW`（含 zh-HK／zh-Hant）、簡體中文 `zh-CN`（含 zh-SG／zh-Hans）、英文 `en`；可從頂部的小型語言選單手動切換 Auto／繁中／简中／EN。偏好保存在本瀏覽器，不傳到伺服器。
4. 原有 V2 四格 Logo、群組式 HR SSC／Finance SSC 導覽、個人出缺勤／主管團隊資料排序、右側日曆、快捷入口、文件與差旅搜尋均維持。

## 示意資訊與授權界線

- 角色切換只是 UI 展示，**不代表真實 RBAC**。
- 出缺勤顯示通用來源與「未連線」狀態；BIPO 僅為可能整合對象之一。
- 日曆僅為前端固定 Fixtures，不呼叫 Lark；**Deepavali 日期／標籤是本次概念展示指定值，不表示公司及全國各州假日規則已正式確認**。
- 財務、HR、差旅人員搜尋均使用 Synthetic Data。正式版需要另外確認權威資料來源、可見範圍、同步與存取授權。
- 預定於年底的正式 Finance SSC 上線範圍與本 V3 概念版分離。

詳見 [`docs/V3_v0.4_Design_Spec.md`](docs/V3_v0.4_Design_Spec.md)。