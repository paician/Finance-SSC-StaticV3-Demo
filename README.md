# Hytech SSC — Employee V3 v0.3（靜態 UX 概念）

本 Repository 僅作為 **Hytech SSC HR × Finance Unified Employee Portal** 的獨立概念展示。與 [Finance SSC V2](https://paician.github.io/Finance-SSC-Static-Demo/?role=employee) 分離；**不修改原版 V2，不介接正式 HR／Finance／Lark API 或資料庫**。

## 開啟

以瀏覽器開啟 `index.html`，或將根目錄發佈為 GitHub Pages 靜態網站（若 Repository／帳戶支援）。不需要 npm、Python、Docker 或其他相依。

## 互動展示

- 上方角色切換：`Employee` 與 `Manager`，**僅 UX 模擬，不代表 RBAC**。
- 左側 `HR SSC`、`Finance SSC` 可展開／收合，並提供獨立「服務總覽」內頁。
- 員工：第一個內容區為「我的出缺勤」；主管：「團隊出缺勤概況」後緊接「人員出差狀況」。
- 日曆區：卡片／月曆切換、年月切換、全部地區與台灣／馬來西亞／新加坡／日本篩選。
- 出差區：搜尋姓名／地點及篩選地區，資料都是虛構示意。
- 右側保留跨部門快捷入口、常見財務情境與公告。原 V2 常見流程文件與出差資訊保留。
- 左下角提供低調的 V2 連結。

## 資料來源與隱私界線

- HR 出缺勤：目前全部合成資料；顯示通用資料來源說明（如 BIPO 只是候選），同步狀態標示「未連線」。
- 假期與重要日程：未連接 Lark Calendar。`10/10 Taiwan National Day` 等示意活動並非完整法定假日清單；其餘日程也是概念展示。
- 差旅名單：皆為合成內容；正式員工搜尋／主管可見範圍、資料同步／查詢方式須另行規劃與授權。
- 所有外部服務僅提供示意互動，沒有真實薪資、假單或交易資料，也不執行外部 API 呼叫。
- 正式產品務必在 Backend 驗證登入者身分、所屬公司／國家及主管部屬關係；前端角色選擇器不可用作授權。

## 交付範圍

這是未來方向探索，**不納入 2026 年既定 Production 交付範圍或 AWS Cost Baseline**。後續需 HR、Lark Calendar、差旅資料擁有者與 IAM 團隊共同確認技術及資料權限，才能估算正式介接。

相關界面與互動契約：`docs/V3_v0.3_Design_Spec.md`。