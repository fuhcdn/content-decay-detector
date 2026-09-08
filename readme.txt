=== Decay Radar ===
Contributors: Yanlee
Tags: seo, content audit, content decay, broken links, content maintenance
Requires at least: 5.8
Tested up to: 6.6
Requires PHP: 7.4
Stable tag: 1.0.0
License: GPLv2 or later
License URI: https://www.gnu.org/licenses/gpl-2.0.html

自動偵測你網站入面正在流失SEO排名嘅過時文章 — 每週掃描,計算內容健康分數,用email通知你邊啲文章需要更新。

== Description ==

**Decay Radar** 幫你揪出網站入面正在悄悄流失SEO排名嘅舊文章。

隨住時間過去,舊文章嘅數據會過時、連結會失效,搜尋引擎亦偏好新鮮內容——但大部分站主完全唔知道邊啲文章已經開始「衰退」,直到流量已經流失先發現。

呢個外掛裝上即用,唔需要連接任何外部平台,唔需要另外登入其他儀表板:

* **自動每週掃描**全站已發佈文章
* 計算每篇文章嘅**內容健康分數**（0-100分）
* 自動偵測**失效嘅外部連結**
* 分數偏低嘅文章自動整理成清單,**email通知**你
* 後台儀表板一覽所有文章嘅健康狀態,並可隨時**手動觸發掃描**

= 免費版功能 =

* 單一網站
* 最多 100 篇文章掃描
* 每週自動掃描 + email 通知
* 失效外部連結偵測
* 後台儀表板

= Pro 版功能（升級解鎖）=

* 無限文章掃描
* 連接 Google Search Console,自動抓取真實流量下滑數據
* AI 自動生成內容更新建議
* 多站點管理與白標報告（Agency 方案）

前往 [contentdecaydetector.com](https://contentdecaydetector.com) 了解更多。

== Installation ==

1. 上傳外掛檔案到 `/wp-content/plugins/decay-radar` 目錄,或直接喺WordPress後台「外掛」>「安裝外掛」搜尋「Decay Radar」並安裝。
2. 喺「外掛」頁面啟用本外掛。
3. 前往後台選單「內容衰退偵測」查看儀表板,或按「立即手動掃描」馬上執行第一次掃描。
4. （可選）前往「內容衰退偵測」>「設定」自訂通知 email 地址。

== Frequently Asked Questions ==

= 呢個外掛會唔會拖慢我個網站？ =

唔會。掃描動作只喺背景透過 WordPress Cron 每週執行一次,唔會喺前台頁面載入時運行,唔影響訪客瀏覽速度。

= 免費版有咩限制？ =

免費版最多掃描 100 篇最舊嘅已發佈文章。如果你嘅網站文章數量超過 100 篇,建議升級 Pro 版解鎖無限掃描。

= 分數係點計出嚟嘅？ =

免費版計分因子包括：文章發佈年齡、距離上次更新嘅時間、以及文章入面失效外部連結嘅比例。Pro 版額外整合 Google Search Console 嘅真實流量趨勢數據,計分更精準。

= 我可以自訂通知頻率嗎？ =

目前固定為每週一次。歡迎透過支援論壇提出你嘅需求。

== Screenshots ==

1. 儀表板總覽 — 一眼睇晒所有文章嘅健康分數同等級
2. Email 通知範例 — 每週自動送到你信箱嘅衰退文章清單
3. 設定頁面 — 自訂通知收件地址

== Changelog ==

= 1.0.0 =
* 首次發佈：每週自動掃描、內容健康分數計算、失效連結偵測、Email通知、後台儀表板。

== Upgrade Notice ==

= 1.0.0 =
首次發佈。
