# 注音倉頡輸入法非官方版 #

## 停止維護 ##

理由很簡單，有以下幾個：
  * 我換手機了，新手機沒有實體鍵盤。本來這個專案就是強化鍵盤支援，現在的鍵盤機已經退潮流了，就更沒必要了。
  * 有更多更強的智慧注音輸入法：IQQI、超注音、觸寶輸入法，都具有自動學習、甚至輸入字音就可以快速輸入。我自己也改用觸寶輸入法了。
  * 開放原始碼，代表有更多人可以自己拿去改。我至少收到兩三個來信有繼續開發意願的，不管是學校專題，還是個人意願。

感謝大家支持與愛戴，也特別感謝捐款給我的朋友們。沒記錯的話應該剛好補了 USD$25 這個洞。

## 已上架 ##

為了維護大家的手機安全，避免從未知來源取得安裝軟體造成問題，
我付了 USD$25 入場費了，請大家到 Android Market 搜尋下載。

[Market 頁面](https://market.android.com/details?id=com.googlecode.tcime.unofficial)

![http://chart.apis.google.com/chart?cht=qr&chs=230x230&chl=market%3A%2F%2Fsearch%3Fq%3Dpname%3Acom.googlecode.tcime.unofficial&nonsense=something.png](http://chart.apis.google.com/chart?cht=qr&chs=230x230&chl=market%3A%2F%2Fsearch%3Fq%3Dpname%3Acom.googlecode.tcime.unofficial&nonsense=something.png)

## 樂捐 ##

如果您覺得這個軟體不錯，請幫忙我負擔 Android Market 的開發者費用。
金額不限，請自由樂捐。十分感謝您的贊助。

[![](http://www.paypal.com/zh_XC/i/btn/btn_donate_LG.gif)](http://scribe.chkkk.idv.tw/donate.htm)

## 簡介 ##

衍生自開放原始碼的[注音倉頡輸入法](http://code.google.com/p/android-traditional-chinese-ime/)。

注音倉頡輸入法因為輕薄短小且符合需要，讓相當多人喜愛。可惜後來並無更新。且許多地方不太順手 (最具代表性的是標點符號鍵盤逗號、句號和頓號問題)，著手修改部分細節並嘗試加入實體鍵盤支援。

## 修改重點 ##

Version 3.1 (預定)
  * 修正因 Android 預設主題設定使鍵盤的字變黑看不清的問題 [Issue #14](http://code.google.com/p/android-traditional-chinese-ime/issues/detail?id=14)
  * 嘗試加入隱藏軟體鍵盤的功能
    * 其實官方版有「手勢下滑」隱藏鍵盤的功能，在鍵盤上往下撥或者按下返回鍵皆可。但是不太直覺方便。
  * 改變特殊符號的輸入方式 (網友建議)
  * 改變輕聲輸入的方式 (網友建議)
  * 平板鍵盤大一點
    * 不過我自己沒有平板，很難測試，Sorry。這個優先權可能後面一點。

Version 3.0
  * 新增 Motorola Milestone 3 印刷注音鍵盤鍵位支援 (在設定裡啟用)
  * 支援 Milestone 3 的 "A|中" 語言切換鍵功能
  * (alpha 實驗功能暫時隱藏，有許多問題無法解決，未能成為正式功能)

Version 3.0 (alpha)
  * 強化長按選項功能表
  * 新增實驗性輸入功能：QR 碼輸入、語音輸入 (需裝置支援)

Version 2.41
  * 新增中文長按選單，可快速設定輸入法/切換輸入法
  * 修正回報取得使用者字典可能錯誤的問題

Version 2.4
  * 修正實體鍵盤中文輸入時按下 Alt 隨即切換到英文輸入再切回來時狀態仍保留的問題
  * 新增更多中文標點符號 (書名號甲乙式、雙引號和參照符號)

Version 2.32
  * 修正 [Issue#1](https://code.google.com/p/android-tcime-unofficial/issues/detail?id=#1) Motorola Milestone/Droid 2 的硬體鍵盤對應問題

Version 2.31
  * 修正回報問題
    * 當使用硬體鍵盤輸入第一個字時，候選字無法出現但可選取，這時選取會發生 Force Crash。研判可能是當時候選字視窗尚未出現而發生此問題。

Version 2.3
  * 新增五排英文鍵盤配置
    * 此功能為對此討論串的回應: [android 作5-row software keyboard會很難嗎？](http://www.mobile01.com/topicdetail.php?f=423&t=2079909)
    * 注意：5-row QWERTY 極度壓縮鍵盤配置，容易誤觸。可到設定選擇使用或關閉。

Version 2.21
  * 修正實體鍵盤沒有打開的提示訊息

Version 2.2
  * 倉頡輸入法支援硬體鍵盤對應 (按 Alt 切換速成模式)
  * 英文軟體鍵盤的 Del 鍵更換位置，使其與大多數軟體鍵盤實作相同

Version 2.1
  * 支援使用者字典候選字功能

Version 2.0
  * 標點符號問題 (逗號、句號對調；新增頓號、間隔號)
![http://android-tcime-unofficial.googlecode.com/svn/wiki/comma.png](http://android-tcime-unofficial.googlecode.com/svn/wiki/comma.png)
  * 英文小寫鍵盤新增長按以輸入大寫字元
  * 注音輸入法硬體鍵盤支援 (對應標準鍵盤鍵位，另針對 Motorola Milestone 修改)
  * 預設一聲注音如果沒有對應字，會找尋其他聲節的字
    * 例如 ㄋㄧ 在原本的輸入法是沒有字的，現在會去找"尼"等字輸出
  * 候選字支援手勢換頁
  * 候選字支援 D-PAD 選擇

## 已知問題 ##

  * 在硬體鍵盤打開的情況選用此輸入法，需要 **合上鍵盤並等軟體鍵盤出現** 才可再度打開硬體鍵盤並使用
    * 完全無法找出問題點，只能提示使用者這樣做
    * 在不換用其他輸入法下，只需作一次
    * 谷歌拼音、注音台都無此問題
  * 軟體鍵盤出現有點慢
    * 原版就這樣了 (純軟體載入字庫，需要時間)
  * 部分倉頡字碼對應有問題
    * 金月廿山 找不到 鋼 [Issue #3](http://code.google.com/p/android-traditional-chinese-ime/issues/detail?id=3)
    * 金中 找不到 丫 (不是注音的ㄚ，是丫頭的丫) [Issue #5](http://code.google.com/p/android-traditional-chinese-ime/issues/detail?id=5)
    * 因為 dat 字庫檔沒有公開編碼原理，所以沒辦法針對字庫修正。未來會嘗試理解編碼原理並作修正。

## 硬體鍵盤支援 (倉頡/注音皆支援) ##

![http://android-tcime-unofficial.googlecode.com/svn/wiki/hkb_milestone.png](http://android-tcime-unofficial.googlecode.com/svn/wiki/hkb_milestone.png)

![http://android-tcime-unofficial.googlecode.com/svn/wiki/hkb_ms3.jpg](http://android-tcime-unofficial.googlecode.com/svn/wiki/hkb_ms3.jpg)

![http://android-tcime-unofficial.googlecode.com/svn/wiki/hardkb.png](http://android-tcime-unofficial.googlecode.com/svn/wiki/hardkb.png)

  * 以 PC 標準注音鍵盤鍵位對應為主，在 SDK 模擬器用鍵盤直接敲完全對應正確
  * 有鍵盤的手機支援以 Motorola Milestone 系列對應為主
    * 因為我只有這隻 (MS1 使用中)
    * 看起來每隻硬體鍵盤手機按鍵配置都不太一樣，我猜在 Desire Z 會有點問題
      * Desire Z 主要是 ㄦ、ㄥ、ㄤ 這幾個音少了對應鍵 (特殊符號)
      * ~~Milestone 2 應該只有 ㄤ 沒有對應~~ 2.32 已對應完成，使用 Alt + , 對應 ㄤ
      * 我再看看要不要用軟體修正
  * 注音鍵盤對應的設計和基本上注音台類似都是標準鍵位 (但不太一樣)
    * 1 - 0 第一排字需要按 Alt + Q, W, ... 選擇 (可以先按 Alt 再按 Q，也可以按住 Alt 同時按 Q)
      * 但不支援注音台的長按選擇 (輸入法實作方式不同)
    * "ㄦ" 用 @ 鍵替代
    * 注音台不必輸入音調，注音倉頡輸入法要
      * Alt + E (3) = ˇ
      * Alt + R (4) = ˋ
      * Alt + Y (6) = ˊ
      * Alt + U (7) = ˙
    * 標準鍵位，應該能很快上手，除了硬體鍵盤按鍵較少需要搭配 Alt 變的很難用以外
  * 倉頡鍵盤則是標準的 26 英文鍵對應，沒有 Z (重) 鍵
    * 要使用速成倉頡請按 Alt 鍵切換
  * Shift + Space 空白鍵可快速切換中/英輸入
    * Milestone 3上面有一顆很神奇的 "A|中" 按鈕，是非正式規範的。不過此輸入法也支援了這個方式切換。

## 其他 ##

  * ~~不會新增語音輸入辨識 (需 Android 2.2+)~~
    * 已列入實驗功能，但滿不順利的。Android 內建的語音辨識和 Indent Broadcast 部分怪怪的
  * ~~字庫部份不懂規則，無法修改~~
    * 會列入修改目標，一旦了解編碼規則後
  * 不會新增其他鍵盤鍵位 (如許氏等)
  * 可能不會再更新
    * 由於已經全心花了好幾天研究輸入法框架並修改原始碼，目前也已符合我的需求
    * 歡迎有志人士繼續拿原始碼去強化
    * 你知道嗎，這是我第一次接觸 Android 程式開發 XDD
  * 感謝 Android Developer Reference 和谷歌拼音輸入法讓我能夠研究，當然更要感謝注音倉頡輸入法的開發者