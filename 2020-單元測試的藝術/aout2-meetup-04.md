 # 單元測試的藝術 Meet up 04: 2020-12-30

第三次聚會的日期是 12月30日晚上八點
主講人： Chapter 5 隔離（模擬）框架  by @sonorous-lester

這次的聚會有時長 35 分鐘以上的小組討論

分為 2 組
1. JavaScript 組：Ralph、羅韋(Luo Wei)、Louis、Gill、Pual
2. Swift 組： Yu、Jerry、Miguel、Wang、Lester

要討論由 JS/Jest 與 Swift/TestSpy 的如何達到第五章節的測試注入，JS 由 Ralph 帶領、Swift 由 Yu 帶領，我們會在下禮拜實作以下2個案例：
1. P.116：使用隔離框架產生假物件
2. P.119：使用隔離框架價物件回傳值
---
下下週會有另外兩個案例
3. P.123：使用隔離框架同時使用Mock與Fake假物件
5. P.127：使用隔離框架模擬事件與單獨的模擬物件

Jest：https://jestjs.io
TestSpy： https://github.com/f-meloni/TestSpy

最後，會有大約 10 分鐘的 Retrospect，會討論一些關於聚會形式、討論方式




Chapter 5 隔離（模擬）框架
<details><summary>細節點我</summary>
<p>

- 5.1 為什麼要使用隔離框架
- 5.2 動態產生假物件
- 5.2.1 在測試中使用NSubstitute
- 5.2.2 用動態假物件來取代手刻假物件
- 5.3 模擬回傳值
- 5.3.1 同時使用模擬物件和虛設常式物件
- 5.3.1.1 驗證物件是帶著某些屬性的情況
- 5.4 測試事件相關的活動
- 5.4.1 測試事件監聽者
- 5.4.2 測試事件是否觸發
- 5.5 現有的.NET 隔離框架
- 5.6 隔離框架的優缺點
- 5.6.1 使用隔離框架時應避免的陷阱
- 5.6.2 測試程式可讀性變差
- 5.6.3 驗證了錯誤的東西
- 5.6.4 一個測試中有多個模擬物件
- 5.6.5 過度指定的測試
- 5.7 小結


</p>
</details>



 ---
 <- 以下為聚會紀錄 ->
 
members:  <!-- @ytyubox, @louis222220, @gannasong @nukr, @RaphaHsu, @aa08666, @WangWang0226, @sonorous-lester, @ishida624 -->
duration(mins): <!-- 60 min -->
