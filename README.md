# ACHB Quotation Tool

ACHB 內部使用的報價單製作工具，純前端單頁 HTML，無需伺服器或安裝軟體。

## 使用方式

直接用瀏覽器（Chrome / Edge）開啟 `ACHB quotation-tool V2.2.html` 即可，無需網路連線。

> PDF 匯入功能需要網路連線載入 PDF.js。

## 功能

- **即時預覽**：左側編輯面板 + 右側 A4 報價單同步顯示
- **PDF 匯入**：自動解析客戶 RFQ PDF 中的 Part No. / Description / Qty，支援人工修正後匯入
- **多數量列報價**：同一品項可設定多組 Qty × Unit Price，自動計算 Amount
- **報價單號自動產生**：依業務人員 ID + 日期 + 流水號組合，序號記憶於 localStorage
- **客戶資料庫**：內建 34 家客戶名稱與代碼，選取後自動帶入
- **品項複製**：一鍵複製整筆品項（含所有數量列）建立相似品項
- **草稿儲存 / 載入**：匯出 JSON 檔案，可跨工作階段還原所有欄位
- **History**：自動儲存最近 3 筆列印紀錄於 localStorage，一鍵載入
- **列印 / PDF 輸出**：A4 尺寸，隱藏編輯面板，瀏覽器直接列印為 PDF

## 檔案說明

| 檔案 | 說明 |
|------|------|
| `ACHB quotation-tool V2.2.html` | 最新版本（目前使用版本） |
| `ACHB quotation-tool CHANGELOG.html` | 版本更新紀錄 |
| `ACHB quotation-tool SOP.html` | 使用說明 SOP |

## 版本

目前版本：**V2.2**　　詳細更新紀錄請見 `ACHB quotation-tool CHANGELOG.html`
