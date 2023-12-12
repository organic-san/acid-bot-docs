---
description: 透過等級排行，可以有效排序用戶的活躍度，以及顯示群組中的活躍度。
---

# /levels 等級排行

## 等級排行的運作方法

為伺服器導入等級排行，便可以看出一個人在伺服器的活躍度。那麼，這個東西是怎麼運作的?

詳細的運作方法是：在用戶發送一則訊息時，用戶便會獲得不定數量的經驗值。\
當經驗值夠多，直到能前往下一等時，隨著預先設定的升級訊息(或者不會有訊息提醒)，用戶會提升一個等級。

不用擔心！為了防止洗版獲得大量經驗值，每一則訊息之間都有冷卻時間，無法不斷的提升等級。

每升一等需要的經驗值會隨著等級越高而需求越高。

***

## 一般用戶可以使用的功能

### /levels rank

等級顯示：顯示用戶在伺服器中的排名、等級、前往下一等所需的經驗值。

#### 填入選項

* (選填)user: 用戶名稱，空白則視作要查看自己的等級。無法查詢機器人的等級。

<div align="left">

<img src="https://cdn.discordapp.com/attachments/848902789681381416/965633156357181560/unknown.png" alt="">

</div>

### /levels ranking

查詢整個伺服器中的等級排行。使用下方的上下一頁按紐可以查看清單的其他部分。

<div align="left">

<img src="https://media.discordapp.net/attachments/848902789681381416/965633375505379378/unknown.png" alt="">

</div>

### /levels no-dm

當升級的訊息設定為私訊時，使用這個指令可以防止ester bot私訊升級訊息。

<div align="left">

<img src="https://cdn.discordapp.com/attachments/848902789681381416/965633641814315059/unknown.png" alt="">

</div>

{% hint style="warning" %}
只有升級訊息的私訊會被過濾，且只有當升級訊息傳送方式是私訊的時候才有效。私訊預設開啟。
{% endhint %}

***

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

下表為在mode填入不同模式時，所代表的意義。

<table><thead><tr><th width="260">在mode填入的模式</th><th>當用戶升級時，會發送訊息的位置</th></tr></thead><tbody><tr><td>message-channel</td><td>接在訊息之後</td></tr><tr><td>specify-channel</td><td>在指定頻道(需要在接下來輸入指定的頻道ID)</td></tr><tr><td>dm-channel</td><td>私訊給這位用戶</td></tr><tr><td>no-react</td><td>不發送任何訊息</td></tr></tbody></table>

<div align="left">

<img src="https://cdn.discordapp.com/attachments/848902789681381416/965636659188236398/unknown.png" alt="message-channel的運作示意圖">

 

<img src="https://cdn.discordapp.com/attachments/848902789681381416/966008485546434651/unknown.png" alt="specify-channel的運作是意圖">

</div>

### /levels reset

歸零所有用戶的經驗值。

<div align="left">

<img src="https://cdn.discordapp.com/attachments/848902789681381416/965644666563350528/unknown.png" alt="">

</div>

{% hint style="danger" %}
此操作不可逆，請審慎考慮。
{% endhint %}
