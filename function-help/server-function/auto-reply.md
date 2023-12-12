# /auto-reply 自動回應

## 自動回應是什麼

自動回應就是：假設你設定了對「蘋果」會回應「西瓜」的話，那麼只要有人輸入「蘋果」，ester bot就會傳送一則訊息寫著「西瓜」。

例如下圖，只要預先設定對「晚安」與他要回應文字，即會在收到對應訊息時自動回復:

<figure><img src="../../.gitbook/assets/image (10).png" alt=""><figcaption></figcaption></figure>

將指定回覆自動化，也可以更加便於疏通多次出現的訊息，也可以為討論添增色彩。

{% hint style="warning" %}
由於Discord的方針，希望機器人回應的話，你需要同時提及機器人(@ester bot)，機器人才能捕捉到你的訊息。
{% endhint %}

***

## 一般用戶可以使用的功能

### /auto-reply show

顯示目前有設定的文字。下面的按鈕可以切換其他的頁面。

<div align="left">

<img src="https://cdn.discordapp.com/attachments/848902789681381416/965617412600893470/unknown.png" alt="">

</div>

***

## 只有管理員才能使用的功能

### /auto-reply add

新增一個自動回應。

#### 填入選項

* trigger-message:要偵測的訊息。
* reply-message:要回應的訊息。

### /auto-reply remove

刪除已經設定的自動回應。

#### 填入選項

* auto-reply-id:自動回應的ID。會在設定成功時顯示，也可以藉由/auto-reply show查詢。

<div align="left">

<img src="https://cdn.discordapp.com/attachments/848902789681381416/965618853608562800/unknown.png" alt="紅框處的ID即為auto-reply-id">

</div>

### /auto-reply reset

​清除所有已設定的自動回應。

<div align="left">

<img src="https://cdn.discordapp.com/attachments/848902789681381416/965621191136137246/unknown.png" alt="">

</div>

{% hint style="danger" %}
此操作無法復原，請審慎考慮。
{% endhint %}
