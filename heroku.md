# Heroku hosting support

Heroku is fully supported. Setup is extremely simple

Run:
```
(. <($(which curl>/dev/null&&echo curl -Ls||echo wget -qO-) https://git.io/JeOXn) --heroku)
```
to automatically push to heroku with a one-liner. If using Android to set up, use Termux.

You will be asked to enter your API ID and API HASH. After that, enter your Telegram phone number and you will receive a code from Telegram. After entering this code you will then be asked to enter you Heroku API (you'll find this in Heroku account settings, scroll down to the very bottom). Copy the API Key and paste it in Termux. After that, Heroku should deploy on its own (though you should always check the logs!)  

Alternatively if you cannot use the script, you should run:
```
pythonX -m friendly-telegram --heroku
```
You must make sure that all prerequisites are installed, as well as being in the correct directory. It is recommended to use the script whereever possible. On Windows however, you must run the script and the heroku setup command separately, because Powershell has restrictions on how parameters are passed, meaning you cannot do it in one line.

