# 資料型態(Data Type)

### 介紹

JavaScript 和其他語言的資料型態比較不同，JavaScript 是屬於**弱型別**語言，所以在宣告時不必特別定義資料的型別，而在操作資料的過程中也會自動轉換。

舉例來說JavaScript和C++的宣告：

<pre class="language-javascript"><code class="lang-javascript"><strong>// JavaScript
</strong><strong>var number = 10;
</strong>var str = '10';
var boolean = true;</code></pre>

```cpp
// C++
int number = 10;
string str = '10';
bool boolean = true;
```

雖然在編寫上較方便，也容易去改變資料的型別，但這也會造成資料不如程式的預期任意轉換，比如說：數字轉字串、字串轉數字，導致效能損害。

### 基本型別(Primitive Type)

基本型別有六個：

* Boolean
* Null
* Undefined
* Number
* String
* Symbol
