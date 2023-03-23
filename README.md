# Flask-ChatGPT3.5-TelegramBot-Railway
# 一個使用Flask框架和GPT3.5 turbo模型官方API，創造一個TelegramBot，快速建置於平台Railway。


## [TelegramBot Vercel GPT3.5 turbo/ChatGPT版本部署](https://github.com/pyfbsdk59/Flask-official-ChatGPT-TelegramBot-Vercel)

<div align="center">
  <img src="demo/demo_351.png" width="500"/>
</div>


## [TelegramBot Render GPT3版本部署](https://github.com/pyfbsdk59/Flask-ChatGPT-TelegramBot-Render)

<div align="center">
  <img src="demo/link.png" width="700"/>
</div>

## [LineBot Django Vercel GPT3版本部署](https://github.com/pyfbsdk59/Django-ChatGPT-linebot-Vercel)

<div align="center">
  <img src="demo/link2.png" width="700"/>
</div>

## [TelegramBot Golang Render GPT3版本部署](https://github.com/pyfbsdk59/Golang-ChatGPT-TelegramBot-Render)

<div align="center">
  <img src="demo/link3.png" width="700"/>
</div>

<div align="center">
  <img src="demo/link3a.png" width="600"/>
</div>

## [LineBot Golang Render GPT3版本部署](https://github.com/pyfbsdk59/Golang-ChatGPT-linebot-Render)

<div align="center">
  <img src="demo/link4.png" width="700"/>
</div>

### [English](https://github.com/pyfbsdk59/Flask-GPT3.5-TelegramBot-Railway/blob/main/README_en.md)
### [日本語](https://github.com/pyfbsdk59/Flask-GPT3.5-TelegramBot-Railway/blob/main/README_jp.md)




#### GPT3 TelegramBot Vercel部署版本。程式猿影音教學參考。請支持且訂閱加按讚感謝他的辛勞。

https://www.youtube.com/watch?v=eKKEa6NhCd0

<div align="center">
  <img src="demo/demo0.png" width="800"/>
</div>



#### 0. Railway提供免費Starter Plan，每個月有5美元或500小時執行時間的免費額度。所以一個月大概可以用20天上下。不用時請刪掉專案。只要存活著就會計算時間。據官方網站說，服務不會沉睡。
<div align="center">
  <img src="demo/railway0.png" width="600"/>
</div>


#### 1. 註冊Railway帳號後，開啟新專案New Project，匯入import已經fork過來的本專案。
<div align="center">
  <img src="demo/demo0r.png" width="300"/>
</div>

<div align="center">
  <img src="demo/demo1r.png" width="600"/>
</div>


#### 2. 必須在Railway的Environment Variables設定兩個環境變數，分別是OPENAI_API_KEY和TELEGRAM_BOT_TOKEN。順便記下Railway給的網址，可以自己縮短一些。

<div align="center">
  <img src="demo/demo2.png" width="600"/>
</div>


#### 3. 若沒有出現網址，請到settings裡的Domains做設定，按下generate domain按鈕即可。

<div align="center">
  <img src="demo/demo5r.png" width="600"/>
</div>

#### 4. 打開瀏覽器，輸入以下網址，設定webhook為部屬完Railway的最後步驟，格式為：https://api.telegram.org/bot{$token}/setWebhook?url={$webhook_url}。

##### 故實際範例就像以下範例（非直接複製使用，請改用自己的telegram token和Railway專案的URL）：


https://api.telegram.org/bot606248605:AAGv_TOJdNNMc_v3toHK_X6M-dev_1tG-JA/setWebhook?url=https://xxx.Railway.app/callback


#### 5. 成功後會顯示以下文字：

{
  ok: true,
  result: true,
  description: "Webhook was set"
}
------
### 創建Telegram機器人和取得token，請參考： 
https://ithelp.ithome.com.tw/articles/10245264<br><br>
https://tcsky.cc/tips-01-telegram-chatbot/



