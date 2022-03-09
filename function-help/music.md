---
description: 播音樂功能! 可以從Youtube向大家播放喜愛的音樂。記得這些指令都要加入語音頻道才能使用!
---

# /music 音樂播放

## 與音樂播放相關的指令

### /music play

將選擇的音樂加入播放清單，如果acid bot不在語音頻道的話，這個指令也會讓acid bot加入你在的語音頻道。\
使用者需要在語音頻道才能使用這個指令。

#### 必填項：

* music-url-or-title:Youtube的音樂、播放清單網址或音樂的名稱。輸入音樂名稱的時後，acid bot會在Youtube搜尋音樂，並把第一首音樂加入播放清單中。

![](https://cdn.discordapp.com/attachments/848902789681381416/950418595198951464/unknown.png)

### /music disconnect

讓機器人離開語音頻道，同時清空目前的播放清單。

### /music skip

跳過目前正在播放的音樂，並開始播放清單中下一首音樂。

### /music replay

重頭播放現在這首音樂。

### /music pause

暫停播放音樂。重新開始播放音樂也是這個指令。

### /music loop

循環播放目前這首音樂。

## 與音樂資訊相關的指令

### /music nowplaying

顯示現在這首音樂的資訊，例如標題、播放者、播放進度等。

![](https://media.discordapp.net/attachments/848902789681381416/951138531793846312/unknown.png)

## 與播放清單相關的指令

### /music queue

顯示目前在播放清單裡面的內容，可以使用下方的按紐移動頁面。

![](https://media.discordapp.net/attachments/848902789681381416/951139260784844850/unknown.png)

### /music remove

移除特定範圍的音樂。

#### 必填項：

* from:要開始移除的音樂的編號。\
  例如，我想移除即將播放中第2首音樂，那麼要移除的音樂編號就是「2」。

#### 選填項：

* amount:從要開始移除的音樂的編號開始算起的音樂數目，預設為1。適合大量移除某個區間的音樂。\
  例如，如果想移除第2首到第5首音樂，等於移除從第2首開始的4首音樂，因此from為2，amount為4。

### /music loopqueue

循環播放整個播放清單。如果已經循環播放目前的音樂，那麼將會循還播放目前的音樂，而非整個播放清單。

### /music random

隨機排序目前的播放清單。
