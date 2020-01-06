# How To Host FTG on [Heroku](https://www.heroku.com)

Friendly Telegram UserBot fully supports Heroku!
Setting up on Heroku is extremely simple! Just follow the steps below.

1. Run the following on a terminal:
   If using Android to set up, use [Termux](https://play.google.com/store/apps/details?id=com.termux)
```
(. <($(which curl>/dev/null&&echo curl -Ls||echo wget -qO-) https://git.io/JeOXn) --heroku)
```

2. You will be asked to enter your API ID and API HASH, which you can get from [Telegram](https://my.telegram.org) 

3. After that, enter your Telegram phone number and you will receive a OTP from Telegram, put the same.

4. After that you will be asked to enter you Heroku API. Copy the API Key and paste it in Terminal
   (Get this in Heroku account settings, scroll down to the very bottom). 

5. Now Heroku will start building and deploying the bot for you. When the command finishes, you can type `.help` on Telegram to check the status

   Alternatively if you cannot use the script, you should run the following:
```
pythonX -m friendly-telegram --heroku
```
   You must make sure that all prerequisites are installed, as well as that you are in the correct directory. It is recommended to use the script wherever possible. 
   On Windows however, you must run the script and the heroku setup command separately, because Powershell has restrictions on how parameters are passed, meaning you cannot do it in one line.

