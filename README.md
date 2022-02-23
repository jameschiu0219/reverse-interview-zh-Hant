# 面試背後的面試

> * 原文：[Reverse interview](https://github.com/viraptor/reverse-interview)
> * 整合：[kkbruce](https://github.com/kkbruce)

以下清單裡的問題對於參加技術面試的人來說可能有些用途。清單裡的問題並不一定適用於某個特定的職位或者工作類型，內容沒有排序過，最開始的時候只是整理我自己的問題清單，但是慢慢地加入一些我覺得可能讓我對這家公司**亮紅牌**的問題。我也注意到被我面試的人向我提問的問題太少了，感覺他們挺浪費機會的。

如果你問過的問題沒有被列出來, 請提交一個 PR。

## 預期使用方式

* 檢查一下哪些問題你感興趣
* 檢查一下哪些是你可以自己在網上找到答案的
* 找不到的話就向面試官提問

絕對不要想把這個清單裡的每個問題都問一遍。

> 尊重面試官的時間，而且你可以通過搜尋已存在的答案來顯示你的積極性。

請記住事情總是要保持彈性，組織的結構調整也經常的發生。擁有一個錯誤追蹤系統[1]並不會保證有效處理錯誤。就算導入CI/CD[2]也不一定保證交付時間會變的很短。

> * [1] Bug tracking system
> * [2] Continuous Integration（持續整合）/Continuous Deployment（持續部署）或Continuous Delivery（或持續交付）

# 關於職責

* 值班（On-call）的計劃或者規定是什麼？
    * 值班或者遇到問題加班時有加班費嗎？
* 我的日常工作內容有那些？
* 有給我設定什麼具體目標嗎？
* 團隊裡面初階和資深工程師的比例是多少？（有計劃改變嗎）
* 到職時會是什麼樣子？
* 每個開發人員有多大的自由來做出決定？
* 每天預期/核心工作時間能有多少小時？
* 在你看來，對於這個職位成功的定義是什麼？
* 你期望我在最初的一～三個月能夠完成什麼目標？
* 試用期結束時，你會怎麼樣衡量我的績效？
* 這個職位的一天或一個禮拜是怎麼安排的？
* 對於我的申請你有什麼疑慮嗎？
* 在這份工作上，我將會和誰緊密合作？
* 我的直接主管和他們的上級都是什麼樣的管理風格？（事無巨細還是著眼宏觀）
* 我在這個職位該如何發展，會有什麼機會？

(簡體延伸)

* 我到職的職位是新增還是接替之前離職的同事？（是否有技術債需要還）？
* 入職之後在屬於專案團隊，專案是新成立還是舊有的？

# 關於技術

* 公司常用的技術組合[3]有什麼?
* 你們怎麼使用版本控制系統？
* 你們怎麼測試程式碼？
* 你們怎麼追蹤錯誤?
* 你們怎樣監控專案進度？
* 你們怎麼整合和部署程式碼異動？是使用CI/CD嗎？
* 你們的基礎設施搭建在版本管理系統裡嗎？或者是程式碼化的嗎？
* 你們的基礎設施建置方法有整合在版本管理系統裡嗎？
    * 或者有程式碼（指令碼）化來進行自動化作業嗎？
* 從計劃到完成一項任務的工作流程是什麼樣子？
* 你們如何準備故障恢複？
* 有標準的開發環境嗎？是強制的嗎？
* 你們需要花費多長時間來給産品建置一個本地端測試環境？（分鐘/小時/天）
* 你們需要花費多長時間來回應程式碼中或相依性裡的安全性問題？
* 所有的開發人員都可以使用他們本機電腦的管理員權限嗎？
* 介紹一下你們的技術原則或者願景。
* 你們的程式碼有開發文件嗎？有單獨提供給客戶的文件嗎？
* 你們有更高層次的討論文件嗎？比如說ER圖，資料庫結構描述等。
* 你們使用靜態程式碼分析嗎？
* 你們如何管理內部和外部的產出成品[4]？
* 你們如何管理依賴關係？

> * [3] Stacks
> * [4] Artifacts

(簡體延伸)

* 公司是否有技術分享交流活動？有的話，多久一次呢？
* 你們的資料庫是如何進行版本管理的？
* 商業需求有任何文件記錄嗎？是如何記錄的？

# 關於團隊

* 團隊的工作是怎麼組織整理的？
* 團隊內部或團隊之間的溝通交流通常如何運作？
* 你們使用什麼工具來做專案的組織整理？你的實際使用體會是什麼？
* 如果遇到不同的意見怎樣處理？
* 誰來設定優先等級或時程計劃？
* 如果持反對[5]意見會怎麼？（例如＂這個無法在專案預計時間內完成。＂）
* 當團隊錯過發行目標時會發生什麼事？
* 每周都會開什麼類型的會議？
* 我的主管會定期進行一對一談話嗎？
* 産品或服務是如何進行規劃的？（幾週發行的一次／持續部署／多發行流程...等等)
* 生産環境發生緊急事件怎麼辦？是否有"對事不對人"的團隊文化？
* 有沒有一些團隊正在經歷還尚待解決的挑戰？
* 你們如何追蹤進度？
* 預期和目標是如何設定的？誰來設定？
* 團隊裡的程式碼檢閱[6]如何實施？
* 介紹一下團隊裡一個典型的衝刺流程[7]
* 你們如何在技術和商業目標之間取得平衡？
* 你們如何共享知識？
* 目前團隊有多少人？

> * [5] Pushback
> * [6] Code Review
> * [7] Sprint

(簡體延伸)

* 公司技術團隊的架構和人員組成？
* 團隊內開發、産品、營運誰是主要需求端？哪一方擁有主導權？

# 關於未來可能的同事

* 開發人員傾向從哪裡學習？
* 你對在這裡工作最滿意的地方是？
* 最不滿意的呢？
* 如果可以的話，你會改變什麼？
* 團隊中年資最久的成員在這裡多久了？
* 在小團隊中，有沒有出現過成員個性互相衝突的情況？最後是如何解決的？

# 關於公司

* 公司為什麼在徵才？（産品發展／新産品／某種變動...)
* 有沒有會議/旅行預算？使用的規定是什麼？
* 晉升流程是怎樣的？要求／期望是如何溝通的？
* 績效評估流程如何進行的？
* 是否擁有單獨的技術和管理兩條職涯道路？
* 公司內是否有任何可用的學習資源，例如電子書訂閱或線上課程？
* 是否有考取專業證書的預算？
* 公司處於何種成熟度階段？（早期尋找方向／有特色的工作／維護階段／...)
* 我可以為開源專案[8]做貢獻嗎？是否需要批准？
* 我會被要求簽署任何競業條款[9]或保密協議[10]嗎？
* 你認為公司未來五年或者十年會如何發展？
* 公司大多數的開發人員是如何看待無瑕程式碼[11]這件事？
* 你上次注意到有人在這裡成長是什麼時候？他們在哪方面有所成長？
* 在這裡成功的定義是什麼？如何衡量成功？
* 有社團運動或者團隊建設活動嗎？？
* 有內部的黑客松[12]活動嗎？
* 公司有支援開源專案嗎？
* 團隊／公司有舉辦什麼樣的社交活動，每個人都需要參加嗎？
* 為什麼公司決定聘請外部人員而不是提拔內部員工？

> * [8] 自由及開放原始碼軟體（Free and open source software，縮寫為FOSS，或Free/Libre and open source software，縮寫為F/L/OSS，FLOSS）
> * [9] non-compete 
> * [10] non-disclosure 
> * [11] Clean Code；採用博碩文化對Clean Code一書的翻譯。
> * [12] Hackathon，也稱駭客松。

(簡體延伸)

* 您在這工作多久了？您覺得體驗如何？
* 大家為什麼會喜歡這裡？
* 公司的調薪制度如何？

# 關於社交問題

* 你們關於多元化招聘有什麼看法？
* 您認為公司文化的缺口在哪裡？（什麼是公司的文化？）
* 在這裡，工作與生活平衡意味著什麼？
* 公司是否對氣候變化持有任何立場嗎？

# 關於衝突

* 不同的意見會如何處理？
* 如果持反對意見會怎麼？（例如＂這個無法在專案預計時間內完成。＂）[註1]
* 當團隊面臨壓力並承諾超出他們的能力／速率時會如何處理？
* 如果有人確定流程/技術及其他方面還有改善空間，會如何處理？
* 當管理層的期望和工程師或團隊的績效之間存在差距的時候，會如何處理？
* 你能告訴我一個關於有害[13]情況的故事以及公司如何處理它嗎？

> * [註1] 前面是針對團隊提問，此處是針對衝突來提問。
> * [13] toxic

# 關於商業

* 你們現在有盈餘嗎？
* 如果沒有的話，還需要多久上軌道？
* 公司的資金從何而來？誰能影響高層的計劃或方向？
* 你們如何賺錢？
* 什麼阻止了你們賺更多的錢？
* 公司未來一年的發展計劃是什麼？五年呢？
* 你們認為什麼是你們的競爭優勢？
* 你認為即將到來的重大挑戰是什麼？
* 你認為什麼是你們的競爭優勢？

(簡體延伸)

* 公司未來的商業規劃是怎樣的？有上市的計劃嗎？(zh)

# 關於遠端工作

* 遠端工作和辦公室工作的比例是多少？
* 公司有提供硬體設備嗎？多能會更新一次？
* 您如何看待使用自己的硬體設備[14]來工作？是否已經有相關政策？
* 是否可以通過公司購買額外的配件/設備？公司有這方面的預算嗎？
* 是否有共享辦公空間或補助上網的預算嗎？
* 多久需要進去一次辦公室？
* 公司的會議室是否總是為視訊會議做好準備？

> * [14] BYOD，https://en.wikipedia.org/wiki/Bring_your_own_device

# 關於辦公室佈局

* 辦公室佈局如何？（開放式／小隔間／獨立辦公室）
* 有沒有支援／市場／或者其他需要大量打電話的團隊在我的團隊旁邊辦公？

# 直球對決

* 關於這個角色/此團隊/公司的工作，最好和最壞的方面是什麼？
* 最初是什麼讓你選擇這家公司？
* 是什麼讓你一直留在公司？

(簡體延伸)

* 該職位為何會空缺？

# 津貼

* 如果有獎金計劃的話，那麼獎金是如何分配的？
* 如果有獎金計劃的話，那麼過去幾年裡通常發放多少百分比？
* 你們有401k[註2]或其他退休計劃嗎？如果是，公司是否額外的補助計劃？
* 有其他醫療（保險）福利嗎？如果有，什麼時候生效？
* 如果需要更換工作地點，公司會付費嗎？

> * [註2] 美國401(k)退休金制度；在台灣可以問勞健保。

# 休假

* 帶薪休假[15]有多久？
* 病假和事假是分開的還是一起計算？
* 我可以提前使用假期時間嗎？也就是說有效地進入負的帶薪休假？
* 休假的延展策略[16]是如何？
* 育兒方面的政策如何？
* 無薪假的政策是如何？
* 年假的政策是如何？

> * [15] Paid Time Off (PTO)；正常的彈休、特休、國定假日等。
> * [16] 也就是說，未休完的假期能否累積到下一次

# 其他資源

在以下位置搜找更多問題的靈感：

* [約耳談測試：改進程式碼的12個步驟](https://www.joelonsoftware.com/2000/08/09/the-joel-test-12-steps-to-better-code/) 由Joel Spolsky撰寫。
* [我在面試中提問的問題](https://jvns.ca/blog/2013/12/30/questions-im-asking-in-interviews/) 由Julia Evans撰寫。

(繁中補充)

* [提問的智慧](https://github.com/ryanhanwu/How-To-Ask-Questions-The-Smart-Way) 一文也是經典。
* [面試笑話](Interview-Joke.md) 由網友提供。好好提問與不好好提問的結果。

# 譯者註

> * 原文整理了一些很不錯提問。原文裡也有簡中和繁中[註3]的連結，因為繁中沒有持續跟進，一時手癢，就翻了起來。如果你有提問過或碰過不錯的提問，也迎歡提交Issue或PR上來，讓我們豐富繁中的提問資料。
> * [反向面试（簡體）](https://github.com/yifeikong/reverse-interview-zh/blob/master/README.md)有補充幾條不錯的提問資料，有一併整合進來。
> * 標題「面試背後的面試」想法延伸自「[QBQ！問題背後的問題](https://www.books.com.tw/products/0010776691)」這本書。

---

> * [註3]在本文上傳公開之後，另一繁中作者也緊急更新內容，而補上內容和我的版本有高度相似。反正英文人人都能翻，尤其是這種短短的句子，翻出來就算長得一模一樣也沒有什麼好大驚小怪的。只能說，我們兩個時間點太近，此篇從頭到尾都是我自己翻譯，還好我公開的時間比對方早，在此聲明釋疑。

# 授權

<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="創用 CC 授權條款" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a><br />本著作係採用<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">創用 CC 姓名標示-相同方式分享 4.0 國際 授權條款</a>授權.
