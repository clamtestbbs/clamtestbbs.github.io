# [Clam-Test BBS](https://www.clam.moe/bbs/)

This is a site for terminal [BBS](//goo.gl/2KAMG) based on "Current Ptt" Project.

基於 PttBBS 原始程式碼為基礎架設的[電子布告欄系統](https://goo.gl/2KAMG)站台

[![](https://i.imgur.com/iKESXcE.png)](https://www.clam.moe/bbs/)


## Browse Links for This site

您可透過以下連結瀏覽本站公開看板、精華區文章:

You can view our website for BBS posts:

<https://www.clam.moe/bbs/>

或是透過以下連結加密連線初步體驗本站:

or try this link for experience term-based BBS interface:

<https://term.clam.moe>

---

若想獲得更完整的 BBS 體驗，

For more comfortable experience,

您還可下載 [PCman](https://pcman.ptt.cc/) 最近新增的 Websocket 支援版本：

you can get some apps for BBS , such as [PCman](https://pcman.ptt.cc/) with websocket+TLS supported:

[https://github.com/pcman-bbs/pcman-windows/releases](https://github.com/pcman-bbs/pcman-windows/releases)

並輸入： 

and enter:

```
wss://ws.clam.moe/bbs
```

to visit my site

來進入本站瀏覽內容

---

若您是用工作站或其他需要終端機的環境瀏覽本站，這邊也提供了 ssh 加密連線的服務，連線指令為：`ssh bbsu@clam.moe` (假設您的終端機使用 **UTF-8** 編碼) ，本站提供的 ssh server 指紋如下：

```
3072 SHA256:HcXb9jdEp/5ZjJqqfQpRyeRNxW526XfaZaz6N/rq3uI (RSA)
256 SHA256:JKPUek7UX4NBbGa2rPLUG4r+5wI4aydGlW6Qc5kaT5w (ECDSA)
256 SHA256:JHGTKuBHt6aMDELfALf2MERBb8LmHRJOJPw4xOXsEVU (ED25519)
```

若初次登入提示訊息顯示之指紋內容與以上不符，*請勿連線至本站*，並請協助回報至本站，您可以在[這邊](https://github.com/clamtestbbs/clamtestbbs.github.io/issues)提 issue。

## Other Information

其他相關實用資訊：

* [Other exsisting terminal BBS site in Chinese](https://bbslist.github.io)
  - 其他已知現存中文電子布告欄站台

+ Install your own [PttBBS](https://github.com/ptt/pttbbs/wiki) ([UserGuide](PttManual))
  - 只要有心，人人都能自己架一個 [Ptt](https://github.com/ptt/pttbbs/wiki)。

+ Install your own [PttWeb](https://github.com/ptt/pttbbs/wiki)
  - 只要有心，人人都能自己架一個 [PttWeb](https://github.com/ptt/pttweb/wiki)。

+ MapleBBS 3.10-itoc Basic Installation [Documentation](https://holishing.github.io/maplebbs-itoc) (UTF-8 encoding)
  - MapleBBS itoc版本 安裝手冊

+ Download MapleBBS 3 Reader: [here](https://clamtestbbs.github.io/test/BBSReader.zip) (by visor@WindTop)
  - BBS文章閱讀器 ( 僅適用 MapleBBS 3，不適用於 Maple 2.36 , SOB , Ptt , Firebird 等版本 )

+ MapleBBS-itoc experimental fork test: [MapleBBS-clam](https://github.com/clamtestbbs/maplebbs-clam)
  - MapleBBS 分支開發相關實驗專案

+ [OpenPtt](https://github.com/clamtestbbs/openptt/wiki) - pttbbs v1.0.2. : Open the history, Open your mind.
  - 重新發掘 OpenPtt 專案 ，了解 PttBBS 程式發展的歷史。
