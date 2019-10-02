# Heroku hosting support

Heroku is fully supported. Setup is extremely simple

Run:
```
(. <($(which curl>/dev/null&&echo curl -Ls||echo wget -qO-) https://git.io/JeOXn) --heroku)
```
to automatically push to heroku with a one-liner. If using Android to set up, use Termux.

You will be asked to enter you API ID AND API HASH. After that you must enter you Telegram phone number and will receive a code from Telegram. After entering this code You will then be asked to enter you Heroku API (you'll find this in Heroku account settings, scroll down to the very bottom. Copy the API Key and paste in Termux. After that, Heroku should deploy on its own (always check the logs!)  

Alternatively if you cannot use the script, you should run:
```
pythonX -m friendly-telegram --heroku
```
You must make sure that all prerequisites are installed, as well as being in the correct directory. It is recommended to use the script whereever possible. On Windows however, you must run the script and the heroku setup command separately, because Powershell has restrictions on how parameters are passed, meaning you cannot do it in one line.

