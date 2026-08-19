# Privacy Policy — RiftAtlasI18n

_Last updated: 2026-08-18_

## English

This extension does **not** collect, store, transmit, or sell any personal data.

- **No analytics, no tracking, no accounts.** The extension has no server of its own.
- **Settings** (language preferences, cache generation counters) are stored locally
  via the browser's `chrome.storage` and sync only through your own browser profile.
- **Network requests**: the extension redirects card-image requests on
  riftatlas.com / play.riftatlas.com to publicly available localized card images
  hosted on the official Riftbound CN site CDN (cdn.playloltcg.com), and rewrites their cache headers locally.
  These requests contain no personal information beyond what any ordinary image
  request contains (IP address, user agent), sent directly by your browser to that site.
- **Permissions**: `declarativeNetRequest` (image redirect), `storage` (settings),
  `scripting` (apply translation to already-open tabs on install), host access limited
  to riftatlas.com, play.riftatlas.com, assets.riftatlas-workers.com, and
  cdn.playloltcg.com (official Riftbound CN site CDN).

Contact: totoro255032@gmail.com

## 繁體中文

本擴充功能**不**收集、儲存、傳輸或販售任何個人資料。

- **無分析、無追蹤、無帳號**，擴充功能沒有自己的伺服器。
- **設定值**（語言偏好、快取世代號）僅存於瀏覽器的 `chrome.storage`，
  只透過你自己的瀏覽器設定檔同步。
- **網路請求**：擴充功能將 riftatlas.com / play.riftatlas.com 上的卡圖請求
  重導至 cdn.playloltcg.com (official Riftbound CN site CDN) 公開提供的中文卡面圖，並在本機改寫其
  快取標頭。這些請求除一般圖片請求本就包含的資訊（IP、user agent）外，
  不含任何個資，且由你的瀏覽器直接送出。
- **權限用途**：`declarativeNetRequest`（卡圖重導）、`storage`（設定）、
  `scripting`（安裝時對已開啟分頁套用翻譯）、host 權限僅限上述四個網域。

聯絡方式：totoro255032@gmail.com
