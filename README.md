
# telegram-echo-bot
A Python Telegram Bot made with Flask Framework

It can be deployed on Heroku. Currently it has some problem which can  be corrected easily.
The bot.setWebhook is Not Working so you have to set Webhook Manually .

To do that , in your browser make a call to Telegra API by opening the url :-

[https://api.telegram.org/bot**TOKEN**/setwebhook?url=https://**APP-NAME**.herokuapp.com/verify](https://api.telegram.org/bot<TOKEN>/setwebhook?url=https://<your-app-name>.herokuapp.com/verify)


**TOKEN** => Replace with TOKEN

Response Should be "ok" .

