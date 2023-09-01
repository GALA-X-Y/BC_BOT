# BC BOT

<a href="https://bcbot.fun/#"><img src="https://images-ext-2.discordapp.net/external/aD9TfvjABl1C4qWmebxhPTjLCJgb2UN0E-YdO0TfbD4/%3Fsize%3D1024/https/cdn.discordapp.com/avatars/987288451110019082/fa555a86323d6e0781d4d2ba5df220c4.png?width=676&height=676" alt="BC BOT icon" width="100"></a>

## 專案簡介 Repository Info
此專案主要目的為記錄公測版本之更新並與正式版區分，負責紀錄更新資訊及官方文件，如果你希望開始使用或瞭解更多，請前往[官方網站](https://bcbot.fun/#)。  
- 不會上傳源代碼
- 只上傳每一版更新（主要是**公測**）的文件，有關格式參考"**更新文件格式及内容**"。  
- 官方文件如公測調研結果，服務與隱私條款等亦會於此上傳。

This repository records only update info and official documents. If you hope to start using BC BOT or find out more, please visit our [website](https://bcbot.fun/#).  
- No source code will be uploaded here. 
- Only update documents (mostly **beta bersions**) will be uploaded here, the format of these documents will be mentioned in "**Update Doc Format & Content**".  
- Official documents like Privacy and Services Terms will be uploaded here.

## 關於公測 About Beta Testing
以往開發者會在内部進行測試程才發放到主賬號，但往往無法短時間進行更新甚或推遲更新時間，爲填充之間空隙及不打擾主賬號的運作而開設另一個公測賬號持續更新公測版本的系統。[按此]()邀請公測機器人賬號。  

Developers tended to finish Alpha tests before releasing new versions. Always updates cannot be delivered in short period of time or even delay. Therefore, a new account for "Beta Testing" will be set up soon to gradually update. [Press this]() to invite the Beta Testing Bot.

### 公測賬號運作 Operation of Beta Account
- 24/7不停機運作，但會按需要**無預警停機**。
- 資料和主賬號**不互通**，情況許可可以手動同步。
- 資料架構更新會按照 [私隱權和服務條款](https://bcbot.fun/#elements) 中的**個人資料的蒐集、處理及利用方式**為根據進行轉型處理，但**未必會事前通知**。
- 公測賬號僅上架未正式發佈之功能及系統。 

資料一旦在存儲在公測賬號便**默認你同意**進行相關處理。

- Beta account will operate 24/7, but there may be **sudden shut without pre-notice**.
- Data between Beta and Main is **not auto-synced**, admins can copy from Main to Beta manually. 
- When transforming your data, we will follow the guildlines of **Collection, Processing and Usage of Personal Data** in [Privacy and Services Terms](https://bcbot.fun/#elements).
- There may **not be pre-notice** before the transforming. 
- On Beta account we will only upload pre-release functions.

Once you store data in the Beta account, you then **agree** we handle your data. 

### 正式發佈之資料處理 Transformation of Data of New Releases
正式發佈將優先使用**公測版本資料**，即便向下兼容支持原來的資料架構，正式版發佈前會提早開放 **放棄公測資料** 機制供希望保留正式版資料的伺服器使用。 
届時操作流程為：
1. 正式版資料架構轉型（非向下兼容版本）
2. 資料合并（開啓機制會自動覆寫）

When Beta tests ended, The data remain in **Beta account** will be **priorly** used, even we did backward compatible. A institution of "**Beta Data Give-Up**" will be introduced before the release for those who want to keep data in Main account.
The flow of release will be:
1. Transforming the data in Main account (For non-backward compatible releases)
2. Intersect of data files (Turning on the instituation will overwrite Beta data)

### 公測更新 Updates of Beta Account
公測版本的更新資訊會於此專案以文件的方式公佈，有關格式參考"**更新文件格式及内容**"。GitHub上的Release版本號(e.g. v2.1.1b)也會更改，公測版本號以**b**(beta)結尾。另外會於 `log.md` 會記錄該次更新。新套件或功能會於使用手冊 `instruction.md` 加入使用方法。 

The update info of Beta account will be uploaded as a update doc here. About the format please read "**Update Doc Format & Content**". The Release Version of this repository will also be updated. Version of Beta testing will be ended with character '**b**'. In `log.md` records will be taken, while tutorial of new plugins and functions will be given in `instruction.md`.

### 公測開始時間 Startup of Beta Account 
預計待10月份反應身份組套件斜綫化進程達一半及完成伺服器機臺調試後開始，稍後通知。

It will begin after 50% of "Reaction Role" Slash-Update is finished, around October. Details will be noticed later.

## 更新文件格式及内容 Update Doc Format & Content
開發團隊會於小段更新後（通常是一個功能上的修改）編寫並上傳簡短的Markdown文件作爲更新文件，裏面會包含:
1. 該次更新的版本號
2. 該次更新涉及的套件/全新的套件
3. 該次更新設計的功能/全新的功能
4. 該次更新的全新使用方法(`instruction.md`的頁數和行數)

Developers will uploaded a short markdown file for update document after a fine-tuning or new elements added. The document will contain:
1. New version code
2. Plugins involved or added
3. Functions involved or added
4. Tutorial of new functions (Lines and page in `instruction.md`)

## 使用手冊 Tutorial
`instruction.md`是BC BOT的使用手冊，裏面會包含各系統的功能（包括背景作業）的使用方法及場景。裏面**不會**提及功能是否上架於正式版，請參考`log.md`以得知實際上架的賬號。該文件會根據更新過的功能逐步編寫，至於已經完成斜綫化的套件或功能會之後在補完。

`instruction.md` is BC BOT's tutorial file. It contains guidelines of functions (including background tasks) of different plugins. It will **not** mention whether the functions are already **released in Main account**, please check `log.md` for this.  

## 更新記錄冊 Update Log
`log.md`是BC BOT的更新記錄冊。因爲BC BOT及公測版本不會於此上傳，因此需要通過文件記錄更新的内容。如只是小調整不足以更新為新版本，會在`log.md`中提及，格式如下:

`log.md` is BC BOT's official update log. As source code will not be uploaded, this log will take part of recording updates. If there is a small fine-tune, a log will be recorded like:

```
2023/XX/XX - 標題 Title
1. xxxxxx
2. xxxxxx
```
如果當日進行了版本更新，格式如下：

If a version update is posted, a log will be recorded like:
```
2023/XX/XX - v2.X.Xb
更新文件 Update Doc : 鏈接 Link
```

## 聯絡我們 Contact Us
<p align="left"> 
  <a href="https://discord.gg/nTxrYyUAQu" target="_blank"> <img src="https://img.icons8.com/color/48/000000/discord.png" width=48 /> </a>
  <a href="mailto:bcbot.team@gmail.com" target="_blank"> <img src="https://cdn.discordapp.com/emojis/1003661260015022142.webp?size=96&quality=lossless" width=48 /> </a>
</p>
