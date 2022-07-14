---
title: "我從Mercari畢業了!"
lang: zh
tags:
  - mercari
  - 事業
---

上個月，剛剛從我工作差不多5年的Mercari畢業了！

![](/assets/images/2022-07-14/1.jpg)
*Mercari是一個像Craigslist或者Ebay的網購app.*

我2017年11月1日加入了Mercari。是我在日本的第一份工，當時不知道會留在日本多長時間所以打算暫時留一年半兩年左右。完全沒想過會留在差不多5年啊！在公司經歷了4年9個月，6月14日，終於去了辦公室最後的一次。

感覺上好像走了很長的路，成長了很多。能説加入Mercari時候的我跟現在的我已經是兩個不同的人！作爲這幾年的retrospective，我寫了這篇文章。

# 時間綫

## 2017年11月 - 2018年10月: SET和自動化測試時代

當初我是作爲負責做自動化測試的Software in Test (SET)加入Mercari的。

當時用的技術棧：
- iOS: XCUITest, Swift, Earl Grey
- Android: Ruby, Appium
- API: JMeter, Postman

主要的成果：
- 把iOS自動化測試加入了development repository和CI build pipeline
- 建立了iOS nightly build
- 改善了自動化測試後果報告的format
- 作了一個 [fastlane plu gin](https://github.com/gmgchow/fastlane-plugin-retry)，把它open-source

## 2018年10月 - 2019年7月: Testdeck時代

Mercari開始轉去microservice architecture的時候，我就加入了爲了作一個microservice自動化測試的社内tool的新project。我們作的叫 [Testdeck](https://github.com/mercari/testdeck)，後期把它open-source了。我以前在 [這篇文章](https://engineering.mercari.com/en/blog/entry/20200930-testdeck/)介紹了一下。

主要的成果：
- 爲了參加這個project和後期做Testdeck的lead，獨立學習了microservices，Kubernetes，GCP，Golang等等
- 跟microservice工程師們一起工作。幫助他們導入自動化測試和troubleshoot，還有收集了關於Testdeck的feature request和改善了Testdeck

## 2019年7月 - 2019年9月: Web自動化測試和改變職業時代

這幾個月，我一邊做Mercari web app的自動化測試，一邊考慮事業的將來。認真的開始學習security和正式收到轉去security team的offer都是這個時段。

主要的成果：
- 幫助維持了web自動化測試 (Typescript與Mocha)
- 作了一個社内tool，每晚自動尋找Mercari web application的錯誤鏈接
- 考上了CompTIA Security+資格

## 2019年10月 - 2022年6月: Security Team時代

雖然我當初作爲SET加入Mercari，結果我在Security Team的時間比我在SET的時間長。

因爲我是沒有經驗，除了CompTIA Security+以外沒有其他security的知識加入Security Team的，其實，當初覺得很辛苦。初半年，我把工作外的時間全部都用來學習security，因爲我想快一點catch up。關於改變職業，我以前寫了 [這篇文章](https://engineering.mercari.com/blog/entry/2020-05-14-121008)。

我永遠會感謝我的team因爲他們一直都沒有放棄我，給我一個能成長到堂堂正正一位Security Engineer的溫暖環境。大家應該知道吧，security這個行業是非常難入的。每個公司都要求有很多經驗的Security Engineer，但是如果沒有地方願意訓練junior的話，那怎麽會有經驗呢?是因爲我能在一個鼓勵我的team内，能跟一些非常優秀的前輩們一起工作，才能成長到現在的我。

主要的成果：
- 改善Testdeck成爲一個security和QA test的tool，那後把它open-source了
- 把威脅模型分析導入了development process
- Co-lead了Security Champions，給社内工程師提供的security知識訓練班

# 這幾年看見的變化

我在Mercari變了很多，但是同時Mercari也有變了很多。我加入的時候是IPO和國際化之前。那時候，Mercari還是一個很典型的日本startup。

![](/assets/images/2022-07-14/2.png)
*大概88%的員工是我加入公司以後加入的。因爲我比其他同事在公司比較長，有時候被叫古株！*

## 國際化

當初加入公司的時候，Slack上的通告，email，對話，文章，會議的幻燈片等等，**全部**都是日文的。那時候只有20幾位外國人吧，所以大家都是互相認識的。

現在，Mercari是日本公司之中比較國際化的。工程部門大概一半是外國人，其實很多team工作上只會用英文。我加入的時候工作上只用日文，但是後期變了差不多只用英文。現在的社内通告等等全部都有英文和日文，而且一些All-Hands會議是全英文舉行的。對不會講日文的外國人來説，工作環境變了舒服很多。在日本找到優秀的工程師已經是非常難的，如果需要日文的話，一定找不到好人所以對公司來説，這是一個很好的變化。

## 多元化與包容性 (D&I)

我加入的時候，當時完全沒有外國人的manager(Engineering Manager和以上)。女性的manager也沒有。這幾年，非常高興能看到management和leadership層越來越多外國人和女性。雖然現在高層還是沒有那麽多minority的人（大部分還是日本人的男性），但是我很期待Mercari會繼續强化D&I。

## YOUR CHOICE

雖然以前一直都有WFH這個選擇（要得了manager的認可），因爲COVID-19疫情，Mercari宣佈了一個全remote，全flex-time的制度叫 [YOUR CHOICE](https://about.mercari.com/en/press/news/articles/20210901_yourchoice/). 很多同事們都離開東京，搬去物價比較便宜而且好住的城市了。但是，當我尋找工作的時候，發現原來還有很多日本公司强求hybrid制度，要求員工定期去辦公室（每個禮拜一兩次）。現在世界是慢慢的回復正常的生活，但是我還是希望越來越多公司會宣佈好像Mercari YOUR CHOICE的制度。

# 成果和美麗的回憶

## 第一次寫博客

加入Mercari之前我完全沒有寫過博客，還是沒有興趣試寫。當我給Mercari的[Engineering Blog](https://engineering.mercari.com/en/blog/)寫了幾片文章之後，發現原來很好玩，成爲了我開始這個個人網站的一個原因。

我寫的文章：
- [Threat Modeling at Mercari](https://engineering.mercari.com/en/blog/entry/20220426-threat-modeling-at-mercari/)
- [How is Security Testing Different from Typical Software Testing?](https://engineering.mercari.com/en/blog/entry/20211210-how-is-security-testing-different-from-typical-software-testing/)
- [DevSecOps: What Is It and Why Is It Gaining Momentum in the Industry?](https://engineering.mercari.com/en/blog/entry/20201214-devsecops-what-is-it-and-why-is-it-gaining-momentum-in-the-industry/)
- [Introducing Testdeck, an Open Source Tool for Microservices QA & Security Testing](https://engineering.mercari.com/en/blog/entry/20200930-testdeck/)
- [The Road to Becoming a Security Engineer: My Story of Career Change](https://engineering.mercari.com/blog/entry/2020-05-14-121008/)
- [Mercari AQA Pop Talk #4: The Future of QA & Test Automation](https://engineering.mercari.com/blog/entry/2018-12-21-123830/)
- [Three Things I Learned at STARWEST, One of the Largest Conferences for Software Testing](https://engineering.mercari.com/blog/entry/2018-11-01-124027/)
- [I Got Certified in ISTQB Advanced Level - Test Automation Engineering!](https://engineering.mercari.com/blog/entry/2018-08-23-184237/)

## 第一次給Open-Source貢獻

加入Mercari以前，沒有給Open-Source貢獻過，還是沒有想過會想貢獻。結果，我在Mercari做的project之中有兩個open-source了！

- [gmgchow/fastlane-plugin-retry](https://github.com/gmgchow/fastlane-plugin-retry)：把XCUITest的自動化測試自動retry的fastlane plugin。現在已經停止維持了。
- [mercari/testdeck](https://github.com/mercari/testdeck)：用Golang做gRPC microservice的自動化測試的tool（細節在上邊的Testdeck項目寫了）。

## 第一次在event演講

從小時候我一直很不喜歡給大觀衆説話。如果沒有加入Mercari的話，我應該一世都不會想象在tech event演講。Mercari在tech community内相當活法的，常常舉行meetup（疫情以前在辦公室舉行，但是現在大概是online的）。很多員工會參加event，演講自己特別有知識的話題，分享最近做的project，等等。結果，我在兩個event演講了。那時候覺得很不舒服在那麽多人前説話，但是現在覺得成爲了一個好經驗。唯一的後悔是，我沒有機會用日文演講了。我覺得用日文演講一定會是一個好挑戰，而且可以試一試自己的日文能力。希望裝來會有這個機會。

我演講的event：
- 2018年12月：[Mercari AQA Pop Talk #4: The Future of QA & Test Automation](https://engineering.mercari.com/blog/entry/2018-12-21-123830/)
  - [From Agile to DevOps: The Rise of 'Continuous Testing'](https://www.slideshare.net/secret/wmEiwlBUtlXSH9)
- 2022年4月：[Mercari’s Approach to Modern Day Threats #2](https://mercari.connpass.com/event/244594/)
  - [Diving Into Threat Modeling at Mercari](https://speakerdeck.com/gmgchow/diving-into-threat-modeling-at-mercari)

## 第一次出差

疫情以前，我運氣很好，能去了兩次海外出差！

- [倫敦，英國（2018年7月）](https://engineering.mercari.com/blog/entry/2018-08-23-184237/)：我爲了上ISTQB Advanced Level - Test Automation Engineering的訓練班和考試去了倫敦。這是我第一次出差，第一次去歐洲，第一次一個人來到外國就掉了錢包（這個事件可以下一次再解釋哈哈），所以成爲了一個很難忘的經驗！
- [加州，美國（2018年10月）](https://engineering.mercari.com/blog/entry/2018-11-01-124027/)：我跟同事們一起去加州參加了STARWEST自動化測試的大會。這是我第一次去tech conference，覺得好新鮮和得了一些新知識。

## 事業外的活動

### 社内俱樂部

在Mercari工作很喜歡的一方面是社内俱樂部。覺得什麽都有俱樂部！因爲我很積極的參加了很多不同的俱樂部，能跟平時不能遇到的同事們交流了。

我參加的俱樂部的例：
- 料理部，福岡茶部，香港部，比薩部，多語言聊天部，Costco部，Ghibli部，麥當勞部，新加波部，台灣部，美國部，加拿大部，水果部，中文部

![](/assets/images/2022-07-14/3.jpg)
*2018年的冬季，我在水果部吃了很多種類的日本草莓！*

### 資格

在Mercari工作發現的一個好處是continuous learning這個想法。很多同事們都常常挑戰自己，去考資格和積極的學習新東西。我加入之前差不多沒有資格，還是沒有什麽特別興趣努力去學習新東西。但是，當我跟好有上進心的人一起工作，開始自己也想再努力一點。結果，我也考上了很多資格，愛上了學習tech和其他的課目。Mercari有時候會提供資格學習的支持，但是有些是我用自己的錢和時間去考的。

我在Mercari的時候考上的資格：
- ISTQB: Advanced Level - Test Automation Engineering, Advanced Level - Security Tester
- CompTIA: Security+
- (ISC)2: SSCP, CSSLP, CISSP
- 日文: JLPT N1, BJT J2
- 中文: HSK 5, HSKK Intermediate

### 語言學習

在Mercari工作另一個好處是因爲公司是比較有多元化的，所以能跟好多不同背景的人交友。這是對我語言學習有很大的影響，領導我更加想練好我的日文和中文。因爲工作環境慢慢得變成需要英文的，幾位朋友們都感興趣練英文。結果，爲了互相提高語言能力，我們常常做了語言交換的1on1會議。

# 辭職的理由

以下是我宣佈離職時候跟我team説的話：

> It's not that I hate it here or anything. This is the best team that I have worked with in my whole career so far. It's just that I've been here for way too long. I think it'll be good for me to see more of the world outside. （不是因爲我討厭了這理。這條team是到現在工作過之中，最棒的。只是，我覺得我已經留在這理太長了。去經歷一下外邊的世界會對我好。）

Mercari是我第二家公司（除了internship的公司），還是我作爲Security Engineer的第一家。對我事業將來來説，去外邊逛逛一下，收一下新刺激，看看其他公司怎麽樣子才能繼續學習新東西和成長。

所以我選擇進入人生下一個階段。我在Mercari的時間經歷了好的和壞的，當然有時候覺得一切都不順利。但是，大概是拿著好的回憶離開的。

{% twitter https://twitter.com/gmgchow/status/1536729941358055424 %}
*最後再看一次Mori Tower。我不知道爲什麽，但是Mercari員工辭職的時候總會拍一拍這樣的照片。*

# 下一步

這個月，我會作爲Senior Security Engineer加入 [Japan Computer Vision](https://www.japancv.co.jp/en/)，Softbank集團的AI startup。我完全沒有關於AI的知識，還沒有Mercari以外的security經驗，而且不太會講普通話（工作上是需要的），所以應該是一個好機會當爲事業和個人的成長。很期待。

雖然我會進入人生下一個階段，我不會忘記我在Mercari過的時間。在這理我認識了最優秀的工程師，交了能談心事的好朋友，比我想象中成長了多。如果我沒有加入Mercari的話，可能已經不在日本了。公司和工作上認識的大家在我心目中是那麽重要的。

謝謝Mercari給我最棒的（差不多）5年！希望我們在未來能再見。:)

![](/assets/images/2022-07-14/4.jpg)
*這是我同事給我手作的禮物，一隻MerPaca!*

![](/assets/images/2022-07-14/5.jpg)
*拜拜，Mercari!*
