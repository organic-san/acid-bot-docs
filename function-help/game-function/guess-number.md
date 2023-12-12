---
description: 猜一個四位數字，俗稱1A2B。
---

# /guess-number 猜數字

## 遊戲說明

在遊戲開始時，ester bot會想一個4位數字作為謎底，目標是在遊戲結束前猜到該4位數字。

遊戲開始後，使用數字按鈕排列出要猜測的4位數字，並按下決定鍵，和謎底的數字比對。\
比對完後，ester bot會用「xAyB」的結果回報比對結果，xA代表有x個位置正確的數字，yB代表有y個數字正確而位置不對的數字。

例如，當謎底為8123，而玩家猜測1052時，ester bot會回報0A2B。\
例如，當謎底為5637，而玩家猜測4931時，ester bot會回報1A0B。

遊戲可以選擇數字可能的範圍，以及數字是否會重複。

直到回合耗盡、按下放棄遊戲按鈕，或者時間超過10分鐘時，遊戲將會自動結束。

***

## 指令一覽

### /guess-number

遊玩一次猜數字遊戲。

#### 填入選項

* range:數字的範圍。可以從4個到10個之間選擇。
* is-recurring:數字是否會重複。

<div align="left">

<img src="https://cdn.discordapp.com/attachments/848902789681381416/966962776050372608/unknown.png" alt="">

 

<img src="https://cdn.discordapp.com/attachments/848902789681381416/966963547898777640/unknown.png" alt="">

</div>
