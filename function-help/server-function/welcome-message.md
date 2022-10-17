# /welcome-message 歡迎訊息

## 歡迎訊息是什麼

當有人加入伺服器時，如果開啟內建的歡迎訊息，那麼系統就會像下面這張圖一樣自動傳送一則歡迎訊息。

![](https://cdn.discordapp.com/attachments/848902789681381416/966337759549751296/unknown.png)

但是，這個功能並沒有辦法手動定義要傳送的訊息，也沒有辦法在用戶離開伺服器時傳送一則訊息。

這時，就可以使用這個功能，歡迎訊息功能可以自訂歡迎訊息的內容，也可以在有人離開伺服器時傳送一則訊息，就像下面這張圖那樣。

![](https://cdn.discordapp.com/attachments/848902789681381416/966529297034641488/unknown.png)

## 只有管理員才能使用的功能

### /welcome-message show

顯示目前的設定狀態。

![](https://cdn.discordapp.com/attachments/848902789681381416/966521538549530654/unknown.png)

### /welcome-message open

開啟歡迎或送別訊息。

#### 填入選項

* type:選擇要開啟的範圍。需選擇歡迎訊息、送別訊息或者兩邊都開啟。

### /welcome-message close

關閉歡迎或送別訊息。

#### 填入選項

* type:選擇要關閉的範圍。需選擇歡迎訊息、送別訊息或者兩邊都關閉。

![](https://cdn.discordapp.com/attachments/848902789681381416/966520908158210118/unknown.png)

### /welcome-message set message

設定當傳送歡迎訊息時，訊息的內容。

#### 填入選項

* type:選擇要設定的訊息。需選擇歡迎訊息，或者送別訊息。
* (選填)message:要設定的訊息內容。

訊息內容中需要加入標誌\<user>(必須)與\<server>(選擇性)，例如:\
`<user>，歡迎加入<server>!閱讀完規則後按下表情符號即可加入伺服器!`

實際運作時將會這樣顯示:\
`(用戶名稱)，歡迎加入(伺服器名稱)!閱讀完規則後按下表情符號即可加入伺服器!`

![自訂訊息的設定示意圖](https://cdn.discordapp.com/attachments/848902789681381416/966528630710763570/unknown.png)

![自訂訊息的執行示意圖](https://cdn.discordapp.com/attachments/848902789681381416/966529297034641488/unknown.png)

如果沒有設定訊息內容，將會採用預設的訊息。

![預設訊息的設定示意圖](https://cdn.discordapp.com/attachments/848902789681381416/966540463119159306/unknown.png)

![預設訊息的](https://cdn.discordapp.com/attachments/848902789681381416/966541030478471258/unknown.png)

### /welcome-message set channel

設定當傳送歡迎訊息時，要傳送訊息的頻道。

#### 填入選項

* type:選擇要設定的頻道。需選擇要設定的範圍是傳送歡迎訊息的頻道，或是送別訊息的頻道，或者兩者都設定。
* (選填)channel:要發送訊息的頻道。

![](https://cdn.discordapp.com/attachments/848902789681381416/966543144940363786/unknown.png)

如果沒有設定頻道，訊息將發送在系統訊息頻道。

![](https://cdn.discordapp.com/attachments/848902789681381416/966543504518045716/unknown.png)

{% hint style="warning" %}
如果沒有設定頻道也沒有系統訊息頻道，或者設定的頻道已消失，那麼將不會發送訊息。
{% endhint %}
