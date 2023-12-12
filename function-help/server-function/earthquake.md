---
description: 每當有地震發生的時候，機器人就會在你設定的頻道提醒你注意安全。
---

# /earthquake 地震消息

## 功能說明

當地震發生時，會在設定的頻道發送像下面圖示的一則訊息。

<div align="left">

<figure><img src="../../.gitbook/assets/image (7).png" alt=""><figcaption><p>像這樣，可以快速掌握到剛剛天搖地動的震央與位置在哪裡</p></figcaption></figure>

</div>

相關資料來源為中央氣象署API，目前僅提供台灣地區資料設定。

***

## 指令一覽(需要管理員權限)

### /earthquake

設定地震消息發送的頻道與模式，訊息會發送在輸入指令的頻道。

#### 填入選項

* mode:所要設定的回覆模式。是否歸類於顯著有感地震將依照中央氣象署的資料分類。

