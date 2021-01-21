 # 單元測試的藝術 Meet up 07: 2021-01-20

第七次聚會的日期是 01月20日晚上八點

主講人： Chapter 8 好的單元測試的支柱 - @nukr


最後，會有大約 10 分鐘的 Retrospect，會討論一些關於聚會形式、討論方式


Chapter 8 好的單元測試的支柱
<details><summary>細節點我</summary>
<p>
  
- 8.1 撰寫可信任的測試
- 8.1.1 決定何時刪除或修改測試
- 8.1.2 避免測試中帶著邏輯
- 8.1.3 每次只測試一個關注點
- 8.1.4 把單元測試和整合測試分開
- 8.1.5 用程式碼審查確保程式碼覆蓋率
- 8.2 撰寫可維護的測試
- 8.2.1 測試私有或保護的方法
- 8.2.2 去除重複的程式碼
- 8.2.3 具可維護性的設計來使用Setup 方法
- 8.2.4 實作測試隔離
- 8.2.5 避免對不同的關注點進行多次驗證
- 8.2.6 物件比較
- 8.2.7 避免過度指定
- 8.3 撰寫可讀性高的測試
- 8.3.1 單元測試的命名
- 8.3.2 變數命名
- 8.3.3 有意義的驗證
- 8.3.4 驗證和操作分離
- 8.3.5 setup 和teardown
- 8.4 小結

</p>
</details>



 ---
 <- 以下為聚會紀錄 ->
 @ytyubox
  
Member
Author
ytyubox commented 21 hours ago • 
edited 
你下午8:06
8.1.1 過時的測試程式碼
https://www.notion.so/ca9038cfbdc14738b2236f9fd57d429c
你下午8:13
8.1.1 AutoFixtrue 跳過了
你下午8:14
8.1.1 5&6 不是必須的
你下午8:16
8.1.1 重覆測試的優缺點
你下午8:17
測試的程式碼太多重複而難以理解
你下午8:19
再小的邏輯都還是邏輯 是思考誤區
你下午8:21
8.1.3 每次只測試一個關注點
實驗組和對照組
你下午8:26
8.1.5 codecov.io 我自己實際使用下來是可以看到重構後沒有用到的code
Ralph Hsu下午8:29
js 我用 wallaby
https://dev.to/beggars/level-up-your-front-end-testing-game-with-wallaby-js-3ona
Ralph Hsu下午8:38
SetUp 相當於 jest 的 beforeEach & afterEach
你下午8:46
tearDownArray 在 fn tearDown() 做
for method in tearDownArrary {
method()
}
你下午8:47
tearDownArray 是 Array of callback
Ralph Hsu下午8:48
缺乏測試可靠度
你下午8:58
常見的精準的匹配器 ==、Array相等
不精準的匹配器 >= 、Set、Contain、hasPrefix
你下午9:01
Custom Assertion Failure message
主要是給 log 檔案，可以當作註解
