 # 單元測試的藝術 Meet up 08: 2021-01-27

 第七次聚會的日期是 01月27日晚上八點

 主講人： ***沒有人，這個章節要自己看完***
一開始會由 @ytyubox 提供 10 分鐘的大綱介紹。

 最後，會有大約 10 分鐘的 Retrospect，會討論一些關於聚會形式、討論方式


PART IV 設計與流程
> 介紹如何在一個組織內進行變革以及如何修改現有的程式碼

Chapter 9 在組織中導入單元測試

 <details><summary>細節點我</summary>
 <p>
- 9.1 逐步成為導入變革的領頭羊
- 9.1.1 準備好面對各種質疑
- 9.1.2 說服組織內成員：支持者和反對者
- 9.1.3 找到可能的切入點
- 9.2 成功之道
- 9.2.1 游擊式的進行（從下而上）
- 9.2.2 說服高層（從上而下）
- 9.2.3 引入外援
- 9.2.4 讓進度可見
- 9.2.5 設定具體目標
- 9.2.6 應對阻礙
- 9.3 失敗原因
- 9.3.1 缺乏驅動力
- 9.3.2 缺乏政策支援
- 9.3.3 糟糕的實現和第一印象
- 9.3.4 缺少團隊支持
- 9.4 影響因素
- 9.5 質疑和回答
- 9.5.1 現有流程加入單元測試需增加多少時間
- 9.5.2 單元測試是否會搶了QA 飯碗
- 9.5.3 證明單元測試確實有效的方式
- 9.5.4 單元測試有用的證據
- 9.5.5 QA 部門還是能夠找到bug 的原因
- 9.5.6 我們有大量未經測試的程式碼，應該從哪裡開始
- 9.5.7 我們使用了多種程式語言：單元測試是否可行
- 9.5.8 軟硬體結合的開發
- 9.5.9 確保測試中沒有bug 的方式
- 9.5.10 偵錯器已經證明我的程式沒問題，但還需要測試的原因
- 9.5.11 測試驅動開發的必要性
- 9.6 小結

 </p>
 </details>



  ---
  <- 以下為聚會紀錄 ->



* 232 9.1.1 準備好面對各種質疑：如果你能夠回答自己提出的難題，應該也能回答別人的質疑
* 233 反對者 - 如果你去找這些人，高談闊論哪些事情他們應該可以做得更好，通常是不會有效果的。人們不喜歡別人告訴* 他們有哪些事情做得不好。相反，你可以請這些人在過程中提供幫助。
* 233 9.1.3 可能的切入點：4點條列
* 237 9.2.4 讓進度可見：9-1 圖
* 238 9.2.4 讓進度可見：向兩個族群傳達訊息
* 239 設定具體目標 - 提高程式碼覆蓋率並不能解決所有問題。你可以很容易地用無意義的糟糕測試來達到 100 % 程式* 碼覆蓋率。
* 240 減少重複出現的 bug 和 降低修復 bug 的平均時間
* 241 9.2.6 應對阻礙 ：Tottinge 推文 
* 242 9.3.3 糟糕的實現和第一印象
* 243 六個影響因素，理解為什麼事情不如計畫般的進行。
* 244 9.5 質疑與問答：條列出對自己的質疑
* 246 表 9-1 進行和不進行單元測試的團隊，其進度和產出數據。
* 247 9.5.4 證明單元測試確實有效的方法: 😭書上的連結失效
* 248 9.5.6 我們有大量未經測試的程式碼，應該從哪裡開始


---

issue tracker 要有可以追蹤的指標, 來向經理證明導入 unit test 有效.
1. 減少回歸,
2.  減少 fix 需要的 time 
3.   crash free rate


## 閱讀清單
1. 單元測試正夯，但你知道其實還有更多選擇嗎？- Vincent Ke https://progressbar.tw/posts/72
2. 將自動化測試引入無經驗團隊的第一步 Devin Deving https://devindeving.blogspot.com/2020/03/first-step-of-introducing-auto-testing-to-inexperienced-team.html
3. 筆記 - 自動化測試與 TDD 實務開發 兩大類的部落格 https://marco79423.net/articles/筆記-自動化測試與-tdd-實務開發/
4. 為了推動自動化測試，你付出了多少？- Zen K.C. https://www.slideshare.net/oreo0725/ss-205850683
5. How to get your team to start unit testing Mattias Petter Johansson https://medium.com/humans-create-software/how-to-get-your-team-to-start-unit-testing-d45417d53667
6. I think the best approach to introduce unit tests is to just write them. - Robert Gummesson  https://medium.com/@RobertGummesson/i-think-the-best-approach-to-introduce-unit-tests-is-to-just-write-them-18e9bf8ddfd2
7. Unit testing newbie team needs to unit test
 https://softwareengineering.stackexchange.com/questions/10849/unit-testing-newbie-team-needs-to-unit-test
8. So.. I need to train the team on Unit Testing - could use C&C on lesson plan
 https://stackoverflow.com/questions/1891466/so-i-need-to-train-the-team-on-unit-testing-could-use-cc-on-lesson-plan
9. TDD 0 to 60: How to Introduce TDD to Your Team With No Unit Testing Experience - Ryan Hayes https://ryanhayes.net/how-to-introduce-tdd-to-your-team-with-no-unit-testing-experience/