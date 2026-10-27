# meetingview-app

Meet書 的手機錄音頁（靜態 HTML，透過 GitHub Pages 提供）。

> 這個 repo 是**公開**的：只放 HTML，不放部署網址、key、email 或任何會議內容。
> 來源在私人 repo 的 `app/`，改動以那邊為準，這裡只是發佈用的副本。

| 檔案 | 用途 |
|---|---|
| `record.html` | 正式錄音頁（record v4，10/20）：從今天的行事曆選會議、結束三層配套、連開會議一鍵切換、⚡臨時會議選與會人員；分段錄音、先存手機再上傳、上傳失敗自動再試／下載到手機。部署網址和 key 由使用者在手機上輸入，只存在那支手機 |
| `mic-test.html` | 麥克風權限實測（只在手機本機錄音、播放，不上傳） |

網址：
- 錄音頁：`https://gptt-jacky.github.io/meetingview-app/record.html?v=4`（更新版本時改 `?v=`，避開 Pages 快取）
- 麥克風測試：`https://gptt-jacky.github.io/meetingview-app/mic-test.html`
