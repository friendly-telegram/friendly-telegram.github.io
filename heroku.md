# Heroku hosting support

Heroku is fully supported. Setup is extremely simple

Run:
```
(. <($(which curl>/dev/null&&echo curl -Ls||echo wget -qO-) https://git.io/JeOXn) --heroku)
```
to automatically push to heroku with a one-liner

Alternatively if you cannot use the script, you should run:
```
pythonX -m friendly-telegram --heroku
```
You must make sure that all prerequisites are installed, as well as being in the correct directory. It is recommended to use the script whereever possible. On Windows however, you must run the script and the heroku setup command separately, because Powershell has restrictions on how parameters are passed, meaning you cannot do it in one line.
