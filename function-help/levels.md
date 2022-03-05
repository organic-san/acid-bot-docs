---
description: 透過等級排行，可以有效排序用戶的活躍度，以及顯示群組中的活躍度。本功能預設開啟。
---

# /levels 等級排行功能

## 等級排行的運作方法

## 一般用戶可以使用的功能

### /levels rank

等級顯示：顯示用戶在伺服器中的排名、等級、前往下一等所需的經驗值。

#### 選填項：

* user: 用戶名稱，空白則視作要查看自己的等級。無法查詢機器人的等級。

![](https://cdn.discordapp.com/attachments/848902789681381416/949707422702899240/unknown.png)

### /levels ranking

查詢整個伺服器中的等級排行。使用下方的上下一頁按紐可以查看清單的其他部分。

![](https://media.discordapp.net/attachments/848902789681381416/949713595338469496/unknown.png)

## 只有管理員才能使用的功能

### /levels open

開啟等級系統

### /levels close

關閉等級系統

{% hint style="info" %}
等級系統預設開啟，若不希望使用等級系統，請使用指令關閉。
{% endhint %}

### /levels reset

歸零所有用戶的經驗值。

![](https://cdn.discordapp.com/attachments/815510939179941891/949717851034505256/unknown.png)

{% hint style="danger" %}
此操作不可逆，請仔細考慮。
{% endhint %}

### /levels level-up-react

設定升等訊息傳送的頻道。下表為在mode填入不同模式時，所代表的意義與需要額外填入的項目。

| 在mode填入的模式      | 當用戶升等時，會發送訊息的位置 | 需要額外需要填入的資料       |
| --------------- | --------------- | ----------------- |
| message-channel | 接在訊息之後          |                   |
| specify-channel | 在指定頻道           | channel: 要發送訊息的頻道 |
| dm-channel      | 私訊給這位用戶         |                   |
| no-react        | 不發送任何訊息         |                   |

![選擇message-channel的示意圖](https://cdn.discordapp.com/attachments/848902789681381416/949725165502230568/unknown.png)

![選擇specify-channel的示意圖](https://media.discordapp.net/attachments/848902789681381416/949726788660105256/unknown.png)
