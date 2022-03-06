---
description: 善用投票功能，集思廣益或取得大家的意見。
---

# /poll 投票

## 指令一覽

### /poll create

建立投票。

#### 必填項：

* title:標題

#### 選填項：

* description:投票說明
* option:選項(至多10個)

如果沒有設定任何選項，投票將以圈叉模式舉行。\
若有設定選項，那麼選項會以ABC...模式舉行。



![以圈叉模式舉行投票](https://cdn.discordapp.com/attachments/949933960916504626/949945300334825482/unknown.png)

![以ABC...模式舉行投票](https://cdn.discordapp.com/attachments/949933960916504626/949945876594434078/unknown.png)

### /poll sum

統計投票的結果。

#### 必填項：

* message-id:有投票訊息的訊息ID，也就是在投票訊息裡的那一串數字。

#### 選填項：

* channel:有投票訊息的頻道。如果沒有填寫，那麼會在發送指令的頻道尋找訊息。

![](https://cdn.discordapp.com/attachments/949933960916504626/949951651609985034/unknown.png)
