---
description: 所有程式語言的開端
---

# Hello World

### 開發人員工具

在前一章節已經帶你將最基礎網頁開發環境建立好，接下來會簡單介紹「開發人員工具」在之後的過程中要怎麼使用。

在剛剛開啟本地端伺服器後，可以按下「F12」或是對畫面按下右鍵「檢查」來開啟「開發人員工具」。

<figure><img src="../.gitbook/assets/image (7).png" alt=""><figcaption></figcaption></figure>

首先注意到最上面的選單有「Elements」、「Console」、「Sources」、「Network」...

<figure><img src="../.gitbook/assets/image (1) (2).png" alt=""><figcaption></figcaption></figure>

這裡我們先只介紹「Elements」、「Console」，也是之後最常用到的！

* Elements：主要用來檢視或調整網頁DOM元素，或是CSS Style。
* Console：控制台，Debug工具，可以在這邊執行程式，檢查元素或資料，或是查看錯誤訊息。

### Hello World

接下來切換到「Console」，並在畫面中輸入「1+1」會發生什麼事。

<figure><img src="../.gitbook/assets/image (12).png" alt=""><figcaption></figcaption></figure>

想必各位應該都得到「2」的答案吧！

接下來輸入 `alert('hello world!!');` 並按下「Enter」試試看會發生什麼事吧！

<figure><img src="../.gitbook/assets/image (3).png" alt=""><figcaption></figcaption></figure>

在試試看輸入 `console.log('hello world');`！

### 在編輯器上寫程式

剛剛我們是在開發人員工具的Console上寫程式。

現在我們轉移到編輯器上！

打開VSCode到「index.html」的地方。

來看一下如果在這個HTML檔案內寫程式應該怎麼寫。

<figure><img src="../.gitbook/assets/image (1).png" alt=""><figcaption></figcaption></figure>

上圖中已經先標示好「CSS」、「HTML」、「JavaScript」撰寫的區塊。

Style表示撰寫CSS，也就是網頁的樣式，程式碼通常撰寫在標籤內，`<style>這裡</style>`。

Body通常做為撰寫HTML與JavaScript的地方，所以可以看見body內有script。

Script就是我們用來寫JavaScript的地方。

也代表著我們接下來要將JavaScript寫在script標籤中，像是：

```
<script>
    var x = 10;
</script>
```

但這樣的方式是不是會感覺很混亂呢？所有東西都塞在同一個檔案內。

### 引入HTML中

但上面這個寫法是都將CSS、JavaScript寫在html檔案中。

其實我們也可以透過**引入**的方式！

可以先建立我們需要的檔案，「style.css」和「script.js」，要注意檔案後的副檔名。

下面圖中第9行是引入我們建立的「style.css」檔案的程式。

第14行是引入「script.js」檔案的程式，也就是我們原本撰寫JavaScript的地方。

<figure><img src="../.gitbook/assets/image (3) (3).png" alt=""><figcaption></figcaption></figure>

接下來我們都會在這個「script.js」中撰寫JavaScript哦！

上述的示範可以跟著練習看看！

{% hint style="success" %}
恭喜你完成到這一步啦！不過之後的地獄才剛要開始，做好心理準備前往下一課吧！
{% endhint %}
