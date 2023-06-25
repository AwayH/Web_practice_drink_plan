# Drink

此專案為授課專題，並非真正實體網站。

## Production

[Demo](https://demo.f2e.idv.tw/drink)

## Tree View
[Coggle](https://coggle.it/diagram/XsPWUM5mjkDPQret/t/%E7%99%AE%E5%92%96%E5%95%A1%E9%A6%96%E9%A0%81-index-html-reset-css%E3%80%81all-jquery-js%E3%80%81all-js%E3%80%81index-js/d50b4d3bbd30702dc6fcf67204e3b1e56ac0b4ade072d1a040b7644a6a30c9a3)

## Wireframe
| index | about-history | about-management | about-news |
|-|-|-|-|
| <img src="https://awayh.github.io/Web_practice_drink_plan/images/wireframe/index.jpg"> | <img src="https://awayh.github.io/Web_practice_drink_plan/images/wireframe/about-history.jpg"> | <img src="https://awayh.github.io/Web_practice_drink_plan/images/wireframe/about-management.jpg"> | <img src="https://awayh.github.io/Web_practice_drink_plan/images/wireframe/about-news.jpg"> |

| products-list | products-detail | stores |
|-|-|-|
| <img src="https://awayh.github.io/Web_practice_drink_plan/images/wireframe/products-list.jpg"> | <img src="https://awayh.github.io/Web_practice_drink_plan/images/wireframe/products-detail.jpg"> | <img src="https://awayh.github.io/Web_practice_drink_plan/images/wireframe/stores.jpg">


## Interface
| index | about-history | about-management | about-news |
|-|-|-|-|
| <img src="https://awayh.github.io/Web_practice_drink_plan/images/interface/index.jpg"> | <img src="https://awayh.github.io/Web_practice_drink_plan/images/interface/about-history.jpg"> | <img src="https://awayh.github.io/Web_practice_drink_plan/images/interface/about-management.jpg"> | <img src="https://awayh.github.io/Web_practice_drink_plan/images/interface/about-news.jpg"> |


| products-list | products-detail | stores |
|-|-|-|
| <img src="https://awayh.github.io/Web_practice_drink_plan/images/interface/products-list.jpg"> | <img src="https://awayh.github.io/Web_practice_drink_plan/images/interface/products-detail.jpg"> | <img src="https://awayh.github.io/Web_practice_drink_plan/images/interface/stores.jpg">

## Open Graph
```html
<meta property="og:url"                content="網址">
<meta property="og:type"               content="website">
<meta property="og:title"              content="標題">
<meta property="og:description"        content="描述">
<meta property="og:image"              content="特色圖片">
<meta property="og:locale"             content="zh_TW">
```

## CDN
- [Font Awesome](https://cdnjs.com/libraries/font-awesome)
- [jQuery](https://cdnjs.com/libraries/jquery)

## Resource
- HTML: Open Graph Protocol。
- CSS: Meyerweb Reset CSS。
- jQuery: 3.6.3。
- [Font Awesome](https://fontawesome.com/icons): 6.2.1。

## Analyze
- SEO 與社群的使用。
- 區分出共用與獨立的單元，並分配檔案的配置。
- 決定資源的使用。
- 色碼: 標準色、輔助色。
- 決定互動效果的製作方式要採用 CSS 或 jQuery。
- 標籤的使用(語意化、SEO)。

## Copy

### index.html

#### head

##### title, og:title
```text
癮咖啡 Drink Coffee
```

##### keywords
```text
咖啡, 咖啡, 蛋糕, 烘焙, 伴手禮
```

##### description, og:description
```text
從原產地的一株咖啡樹，最終成為送到手中的一杯咖啡。這段旅程，為咖啡的故事做了最佳的註解，同時也塑造出咖啡家族的獨特風味及口感特性。
```

#### body

##### Navigation
- 關於癮咖啡 about
  - 企業沿革 history
  - 經營理念 management
  - 最新消息 news
- 嚴選商品 products
  - 咖啡 coffee
  - 蛋糕 cake
  - 烘焙 bread
  - 伴手禮 gift
- 門市資訊 stores

##### Feature
- 咖啡 coffee
- 蛋糕 cake
- 烘焙 bread
- 伴手禮 gift

##### News
- 原住星希望公益募款活動開跑囉 邀請您熱情參與支持
- 原住星希望公益募款活動開跑囉 邀請您熱情參與支持
- 原住星希望公益募款活動開跑囉 邀請您熱情參與支持
- 原住星希望公益募款活動開跑囉 邀請您熱情參與支持
- 原住星希望公益募款活動開跑囉 邀請您熱情參與支持

##### Hot
- 黑森林 black forest cake
- 焦糖瑪奇朵 caramel macchiato
- 法國原味可頌 french croissant

---

### about.html

#### head

##### title, og:title
```text
關於癮咖啡 - 癮咖啡 Drink Coffee
```

##### keywords
```text
癮咖啡, 企業沿革, 經營理念, 最新消息
```

##### description, og:description
```text
關於癮咖啡描述
```

#### body

##### Sub-Navigation
- 企業沿革 history
- 經營理念 management
- 最新消息 news

##### Heading
```text
關於癮咖啡 About
```

##### Content
```text
企業沿革

" 癮咖啡 " 以「提供客戶好咖啡，創造本土咖啡文化」為企業目標，並以高品質咖啡的市場定位，歐洲風味的美術裝潢基調，開創出屬於自己的風格。

經營理念

以中深烘焙風格的咖啡豆做為基底，具有濃郁的口感且回甘強烈，並帶有葡萄酒般的微酸，更保存了優雅的花果香味。

最新消息

堅持「五星級品質」和「平實消費」，繼2011年9月首次被國際知名品牌鑑價單位Interbrand評選為台灣二十大國際品

```

---

### about-history.html

#### head

##### title, og:title
```text
企業沿革 - 癮咖啡 Drink Coffee
```

##### keywords
```text
癮咖啡, 咖啡, Arabica, 阿拉比卡
```

##### description, og:description
```text
生活，從遇見癮咖啡開始每杯香醇的咖啡，分享著不同的生活與故事，癮咖啡與您一同迎接生活的美好片刻。
```

#### body

##### Sub-Navigation
- 企業沿革 history
- 經營理念 management
- 最新消息 news

##### Heading
```text
企業沿革 History
```

##### Content
```text
生活 從遇見 "癮咖啡" 開始
每杯香醇的咖啡 分享著不同的生活與故事
"癮咖啡" 與您一同迎接生活的美好片刻

我們的熱情

"癮咖啡" 成立於 1998 年 12 月，秉持著二十年的咖啡製作經驗與品牌信譽，跨足餐飲服務業的首度嘗試，"癮咖啡" 只使用精選的 Arabica 豆，堅持每週適量烘焙新鮮咖啡豆。從創始店開始，"癮咖啡" 以「提供客戶好咖啡，創造本土咖啡文化」為企業目標，並以高品質咖啡的市場定位，歐洲風味的美術裝潢基調，開創出屬於自己的風格。

我們的使命

"癮咖啡" 專注於服務、環境、產品的完美呈現，消費者不管到哪間 "癮咖啡"，都可以享受到新鮮烘焙的咖啡，聽著舒適的音樂，再喝杯醇香的 "癮咖啡"，絕對是放鬆心靈的最佳選擇。
```

---

### about-management.html

#### head

##### title, og:title
```text
經營理念 - 癮咖啡 Drink Coffee
```

##### keywords
```text
癮咖啡, 咖啡, 烘焙
```

##### description, og:description
```text
針對產品、專業咖啡人員、專業咖啡器具、優質咖啡環境堅持四大原則並偕同理念相同的人與我們一同創造咖啡文化。
```

#### body

##### Sub-Navigation
- 企業沿革 history
- 經營理念 management
- 最新消息 news

##### Heading
```text
經營理念 Management
```

##### Content
```text
經營特色

中深烘焙配方

以中深烘焙風格的咖啡豆做為基底，具有濃郁的口感且回甘強烈，並帶有葡萄酒般的微酸，更保存了優雅的花果香味。搭配牛奶製作各種花式咖啡更覺香醇，比市場上流行焦苦的重烘焙口味更勝一籌。

餐點與咖啡結合

一般連鎖咖啡館只提供咖啡及甜點，無法兼顧到台灣消費者在咖啡館用正餐的特殊的需求。為此，癮咖啡貼心的在早餐、午晚餐及下午茶等時段，提供各式美味餐點，可滿足您不同的用餐需求。

異國風味餐點組合

以各種三明治、千層麵、義大利麵、排餐等純歐式餐點，以及融合中西口味的創新菜餚，區隔常見的中式簡餐，滿足消費者對美食的渴望。

高標準的衛生管理

嚴謹的店內管控為讓顧客能放心享受咖啡與美食，癮咖啡館以嚴謹的食物處理流程製作餐飲，並每日定時以酒精消毒環境與食器，確保餐飲品質安全無虞。 超越國家標準的檢驗規範癮咖啡擁有 GMP 食品廠及國家級食品檢驗室，定期抽驗供應商原物料，及店內飲用水、冰塊、食器及各類餐飲產品，檢驗標準高於國家標準，確保顧客用餐安全。

四大堅持

針對產品、專業咖啡人員、專業咖啡器具、優質咖啡環境堅持四大原則並偕同理念相同的人與我們一同創造咖啡文化。

最新鮮的咖啡

堅持每週現炒烘焙運送，保證每顆豆子都處在賞味的巔峰狀態！

最嚴謹的訓練

以三個月至半年的時間嚴謹的訓練專業的咖啡達人，從咖啡配方到專業的咖啡知 識外加領導統馭以及服務理念的貫徹，讓每杯咖啡都注入我們的熱情！

最專業的器具

使用義大利最專業的 Espresso Coffee 機，決不在任何一個專業的咖啡細節上有所怠慢！

最舒適的環境

癮咖啡館以最寬敞的座位空間搭配歐式風味的藝術裝潢基調，提供消費者最舒適的用餐環境！
```

---

### about-news.html

#### head

##### title, og:title
```text
最新消息 - 癮咖啡 Drink Coffee
```

##### keywords
```text
癮咖啡, 咖啡, 最新消息
```

##### description, og:description
```text
堅持「五星級品質」和「平實消費」，繼2011年9月首次被國際知名品牌鑑價單位Interbrand評選為台灣二十大國際品牌第11名，今年再次入圍並榮獲第十名。
```

#### body

##### Sub-Navigation
- 企業沿革 history
- 經營理念 management
- 最新消息 news

##### Heading
```text
最新消息 News
```

##### Content
- 賀！癮咖啡再次榮獲2012年台灣20大國際品牌獎第十名
  - 2012.09.25
  - 堅持「五星級品質」和「平實消費」，繼2011年9月首次被國際知名品牌鑑價單位Interbrand評選為台灣二十大國際品牌第11名，今年再次入圍並榮獲第十名。 台灣二十大國際品牌是中華民國對外貿易發展協會委託與美國《商業週刊》「全球100大品 牌調查」相同的品牌鑑價系統－英國品牌顧問公司Interbrand發展出的專業鑑價模式，從財 務、質化指標分析，了解台灣品牌在國際市場的競爭力。過去獲選廠商大都以電子產業為主，2011年85度C第一次參加就進入前20大，獲選第11名，品牌價值2.19億美金，也是歷年來首次入圍的餐飲服務業者。2012年再次入圍並擠入前十名，品牌價值2.72億美金，可見餐飲業在國際地位的重要性與日俱增。
- ...

---

### products.html

#### head

##### title, og:title
```text
嚴選商品 - 癮咖啡 Drink Coffee
```

##### keywords
```text
癮咖啡, 咖啡, 蛋糕, 烘焙, 伴手禮
```

##### description, og:description
```text
嚴選商品描述
```

#### body

##### Sub-Navigation
- 咖啡 coffee
  - 那堤 latte
  - 香草那堤 vanilla latte
  - 焦糖瑪奇朵 caramel macchiato
- 蛋糕 cake
  - 黑森林 black forest cake
  - 檸檬塔 lemon tart
  - 法式千層薄餅 mille crêpe
  - 可麗露 canelé
  - 蜜桃優格 peach yogurt cake
  - 洋梨輕奶油 pear cream cake
- 烘焙 bread
- 伴手禮 gift

##### Heading
```text
咖啡 coffee
```

##### Content
- 咖啡系列
- 蛋糕系列
- 烘焙系列
- 伴手禮系列

---

### products-list.html

#### head

##### title, og:title
```text
咖啡 - 癮咖啡 Drink Coffee
```

##### keywords
```text
癮咖啡, 咖啡, 那堤, 卡布奇諾, 美式, Latte, Cappuccino
```

##### description, og:description
```text
咖啡列表描述
```

#### body

##### Sub-Navigation
- 咖啡 coffee
  - 那堤 latte
  - 香草那堤 vanilla latte
  - 焦糖瑪奇朵 caramel macchiato
- 蛋糕 cake
  - 黑森林 black forest cake
  - 檸檬塔 lemon tart
  - 法式千層薄餅 mille crêpe
  - 可麗露 canelé
  - 蜜桃優格 peach yogurt cake
  - 洋梨輕奶油 pear cream cake
- 烘焙 bread
- 伴手禮 gift

##### Heading
```text
咖啡 coffee
```

##### Content
- 那堤
  - 那堤 Latte 是由牛奶和咖啡調配而成，沒有對苦味的褻瀆，卻注入純粹的奶香，攪亂咖啡的枯燥，在流動的黑與白之間游走，凝結甜與苦的孤單。
  - NT$ : 999
  - 詳細內容
- 那堤
  - 那堤 Latte 是由牛奶和咖啡調配而成，沒有對苦味的褻瀆，卻注入純粹的奶香，攪亂咖啡的枯燥，在流動的黑與白之間游走，凝結甜與苦的孤單。
  - NT$ : 999
  - 詳細內容



### products-detail.html

#### head

##### title, og:title
```text
那堤 Latte - 癮咖啡 Drink Coffee
```

##### keywords
```text
癮咖啡, 咖啡, 那堤, Latte, 牛奶
```

##### description, og:description
```text
那堤 Latte 是由牛奶和咖啡調配而成，沒有對苦味的褻瀆，卻注入純粹的奶香，攪亂咖啡的枯燥，在流動的黑與白之間游走，凝結甜與苦的孤單。
```

#### body

##### Sub-Navigation
- 咖啡 coffee
  - 那堤 latte
  - 香草那堤 vanilla latte
  - 焦糖瑪奇朵 caramel macchiato
- 蛋糕 cake
  - 黑森林 black forest cake
  - 檸檬塔 lemon tart
  - 法式千層薄餅 mille crêpe
  - 可麗露 canelé
  - 蜜桃優格 peach yogurt cake
  - 洋梨輕奶油 pear cream cake
- 烘焙 bread
- 伴手禮 gift

##### Content
```text
那堤 latte

NT$ : 850

85 折 NT$ : 999

那堤 latte 是由牛奶和咖啡調配而成，沒有對苦味的褻瀆，卻注入純粹的奶香，攪亂咖啡的枯燥，在流動的黑與白之間游走，凝結甜與苦的孤單。

那堤 latte 是意大利濃縮咖啡與牛奶的經典混合，意大利人也很喜歡把它作為早餐的飲料。意大利人早晨的廚房裡，照得到陽光的爐子上通常會同時煮著咖啡和牛奶。喝那堤 Latte 的意大利人，與其說他們喜歡意大利濃縮咖啡，不如說他們喜歡牛奶，也只有咖啡才能給普普通通的牛奶帶來讓人難以忘懷的味道。

```

- 商品規格
  - 產品名稱：【Gustare caffe】精選西達摩咖啡豆
  - 產品規格：半磅(227g)
  - 產品數量：1包
  - 商品型號：DOF-cafe02
  - 產品成份：西達摩咖啡豆
  - 產品產地：衣索比亞-西達摩
  - 保存期限：1年
  - 保存方式：拆封後立即使用，避免陽光直射及高溫潮濕之場所
  - 注意事項： 本產品不包含照片中其他盤飾擺設。
- 商品保證
  我們所提供為全新產品，並提供以下保證：
  - 保固期限：1年
  - 保固範圍：新品瑕疵
  - 顧客諮詢服務中心：本站客服中心
- 商品運送
  部分特殊商品某些配送地點需加收運費(將於網頁標示說明)，其它商品不另收運費。

  我們所提供的產品配送區域僅限於台灣本島（外島地區的朋友請利用台灣親友地址做為收貨地址）。 在確認交易條件無誤且有庫存後，商品將於您付款完成後約2-5個工作天內送達您指定的地址。 雜誌/預購/訂製等特殊商品依網頁說明時間出貨，特殊商品如與廠商約定送貨日，送貨日期需於訂購完成30天內。

  本網站配合環保署廢四機回收服務 :

  - 廢四機回收專線:0800-085717。
  - 購物中心廢四機回收諮詢專線:02-77238585。
- 購買說明
  發票寄送 由於商品配送皆由廠商直接寄出，發票會在付款完成、出貨後開立，並儲存為電子檔供您查看，您若需要正本可至訂單查詢直接索取 (已捐贈、已索取的發票除外)，詳情請參考「發票託管流程說明」。

  三聯式發票、索取發票將會在廠商完成出貨後10個工作天寄出，約2-7個工作天內送達，如遇國定假日將順延寄送。如您於收到訂購商品後20天仍未收到發票，請通知客服中心。

  發票金額是扣除您使用購物金或福利金折抵後的自付額。若您使用信用卡紅利或福利金後訂單金額全額折抵，將不另行開立發票。 售後服務 若您收到的商品有瑕疵或異常問題，想更換商品(限相同商品)，請參照換貨詳細辦法。 您所購買的商品依法享有十天內無條件退貨的權利，請參考退貨詳細辦法。 大型商品 廢四機回收說明：「新購公告指定規格之電視機、洗衣機、電冰箱或冷、暖氣機時，販賣業者應提供同項目、數量、時間及同送達地址之廢四機回收（搬、載運）無償服務。但不包含為搬運、拆卸而動用大型機具、工程或危險施工等。請於交付廢四機時向業者索取回收聯單，憑單參加抽獎活動。消費者本人簽名確認已被口頭告知或知悉上述權益」。更多說明請參考廢四機回收辦法。

  本網站配合環保署廢四機回收服務 :

  - 廢四機回收專線:0800-085717。
  - 購物中心廢四機回收諮詢專線:02-77238585。
  
  客服中心 有關購買、付款及運送方式的更多說明，請參考服務說明，如仍有問題歡迎聯繫客服中心。



### stores.html

#### head

##### title, og:title
```text
門市資訊 - 癮咖啡 Drink Coffee
```

##### keywords
```text
癮咖啡, 咖啡, 門市, 台北, 新北, 桃園, 中壢
```

##### description, og:description
```text
癮咖啡門市遍佈全台，讓您隨時隨地可以享用
```

#### body

##### Heading
```text
門市資訊 Stores
```

##### Content
- 站前癮 / 台北
- 東區癮 / 台北
- 板橋癮 / 新北
- 中壢癮 / 桃園
