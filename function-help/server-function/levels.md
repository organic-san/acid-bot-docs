---
description: 透過等級排行，可以有效排序用戶的活躍度，以及顯示群組中的活躍度。
---

# /levels 等級排行

## 等級排行的運作方法

為伺服器導入等級排行，便可以看出一個人在伺服器的活躍度。那麼，這個東西是怎麼運作的?

詳細的運作方法是：在用戶發送一則訊息時，用戶便會獲得不定數量的經驗值。\
當經驗值夠多，直到能前往下一等時，隨著預先設定的升級訊息(或者不會有訊息提醒)，用戶會提升一個等級。

不用擔心！為了防止洗版，每一則訊息之間都有冷卻時間，無法不斷的提升等級。

每升一等需要的經驗值會隨著等級越高而需求越高。

## 一般用戶可以使用的功能

### /levels rank

等級顯示：顯示用戶在伺服器中的排名、等級、前往下一等所需的經驗值。

#### 填入選項

* (選填)user: 用戶名稱，空白則視作要查看自己的等級。無法查詢機器人的等級。

![](https://cdn.discordapp.com/attachments/848902789681381416/965633156357181560/unknown.png)

### /levels ranking

查詢整個伺服器中的等級排行。使用下方的上下一頁按紐可以查看清單的其他部分。

![](https://media.discordapp.net/attachments/848902789681381416/965633375505379378/unknown.png)

### /levels no-dm

當升級的訊息設定為私訊時，使用這個指令可以防止ester bot私訊升級訊息。

![](https://cdn.discordapp.com/attachments/848902789681381416/965633641814315059/unknown.png)

{% hint style="warning" %}
只有升級訊息的私訊會被過濾，只有當升級訊息傳送方式是私訊的時候才有效。私訊預設開啟。
{% endhint %}

## 只有管理員才能使用的功能

### /levels open

開啟等級系統。

### /levels close

關閉等級系統。

{% hint style="info" %}
等級系統預設開啟，若不希望使用等級系統，請使用指令關閉。
{% endhint %}

### /levels level-up-react

設定升級訊息傳送的頻道。

預設為message-channel模式，也就是下方示意圖的模式。

#### 填入選項

* mode
* channel (當mode設定為specify-channel時必填)

下表為在mode填入不同模式時，所代表的意義與需要額外填入的項目。

| 在mode填入的模式      | 當用戶升級時，會發送訊息的位置 | 需要額外需要填入的資料       |
| --------------- | --------------- | ----------------- |
| message-channel | 接在訊息之後          |                   |
| specify-channel | 在指定頻道           | channel: 要發送訊息的頻道 |
| dm-channel      | 私訊給這位用戶         |                   |
| no-react        | 不發送任何訊息         |                   |

![message-channel的運作示意圖](https://cdn.discordapp.com/attachments/848902789681381416/965636659188236398/unknown.png) ![specify-channel的運作是意圖](https://cdn.discordapp.com/attachments/848902789681381416/966008485546434651/unknown.png)

### /levels reset

歸零所有用戶的經驗值。

![](https://cdn.discordapp.com/attachments/848902789681381416/965644666563350528/unknown.png)

{% hint style="danger" %}
此操作不可逆，請審慎考慮。
{% endhint %}
