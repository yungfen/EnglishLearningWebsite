繁體中文 | [English](README.en.md)

# 英語學習網：從故事學西洋節慶文化

給國小五年級學生使用的英語學習網站。學生透過四個西洋節慶的故事學英文，並且在學的過程中認識節慶文化。

- 線上版：https://learn-english-western-festival.netlify.app/homepage
- 製作者：劉永芬（U10809003，英語教學五）

<!-- TODO: 補一兩句製作背景，例如是哪門課的作品、指導老師 -->
<!-- TODO: 放一張主畫面截圖，例如 images/screenshot.png -->

## 學習內容

收錄四個節慶：復活節（Easter）、萬聖節（Halloween）、感恩節（Thanksgiving）、聖誕節（Christmas）。每個節慶分成五個單元：

| 單元 | 內容 |
| --- | --- |
| Story 故事 | 英文故事附朗讀音檔，可以切換 1、0.75、0.5 倍速。可以查生字，也可以看全文中文翻譯 |
| Practice 練習 | <!-- TODO: 確認練習形式（目前只有聖誕節頁面用到 cards/ 單字圖卡）--> |
| Game 遊戲 | 記憶翻牌遊戲，把英文單字和對應的中文意思或圖片配成一對 |
| Test 測驗 | 選擇題、是非題、看圖題，作答完立刻顯示分數 |
| Extended Learning 延伸學習 | 嵌入 YouTube 影片，延伸認識節慶相關內容 |

## 使用方式

1. 在首頁輸入班級、座號、姓名，按「下一頁」
2. 從左側選一個節慶，再選要進行的單元
3. 點「Learning Record 學習歷程」，可以看到自己在每個單元花了多少時間

學生的資料和學習紀錄只存在自己的瀏覽器裡（localStorage），不會上傳到任何伺服器。換一台裝置或清除瀏覽器資料後，紀錄就不見了。

## 技術

只用 HTML、CSS、JavaScript，搭配 Bootstrap 和 jQuery，沒有後端。網站部署在 Netlify。

## 素材來源

- 首頁插圖：[Image by upklyak](https://www.freepik.com/free-vector/happy-people-celebrate-party-corporate-fun-holiday_22393762.htm) on Freepik
- 其他參考資料：見網站內的「Reference 參考資料」頁
