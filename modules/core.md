
# Core

Core modules that are always loaded to the userbot

## Core Control

 - **Blacklist** 
[Syntax: `blacklist [chat id]`]

   Disables all userbot commands in that chat.

   The current chat is used when `[chat id]` is not given.

 - **Unblacklist** 
[Syntax: `unblacklist <chat id>`]

   Removes the chat from the blacklist.

 - **Set command prefix** 
[Syntax: `setprefix <command prefix>`]

   Sets the prefix to be used for commands.

 - **Add command alias** 
[Syntax: `addalias <alias> <command>`]

   The default command names too long for you? Set an alias for it using this command.

## Help and Support

 - **Getting help for commands** 
[Syntax: `help [command]`]

   Shows you the help text for the specified command name, or all commands if no name was given.

 - **Join support chat** 
[Syntax: `support`]

   Join the support chat for more help from the community.

## Loading and unloading modules

 - **Downloading modules** 
[Syntax: `dlmod [module name/URL]`]

   Downloads the specified module from the official modules repository. If no name or URL is given, you get a list of official modules available
   
   *PSST, did you know that you can load [Paperplane](https://github.com/MyPaperPlane/Telegram-UserBot) and [Uniborg](https://github.com/SpEcHiDe/UniBorg) modules too?*


 - **Module Presets** 
[Syntax: `dlpreset <preset name>`]

   Quickly change userbot "Profiles" according to your need. Note that these only apply after a restart.

   Available presets:
    - *Full:* `dlpreset full` 
loads all modules (default).

    - *Minimal:* `dlpreset minimal` 
loads a minimal set of modules.

    - *None:* `dlpreset none` 
loads only the core modules.

 - **Loading custom modules**
[Syntax: `loadmod <path to module file on host>` or reply to a module file with `loadmod`]

   Loads the 3rd party (external) module into your userbot.

   *PSST, did you know that you can load [Paperplane](https://github.com/MyPaperPlane/Telegram-UserBot) and [Uniborg](https://github.com/SpEcHiDe/UniBorg) modules too?*

 - **Unloading custom modules**
[Syntax: `unloadmod <module name>`]

   Unloads the modules loaded in the specified module name (found in help command).

## Anti Collisions

 - **Kill all other userbot sessions**
[Syntax: `cleanbots`]

   Terminates all other userbot sessions, to make sure that there's only one userbot running on your account. This is important, as otherwise commands will crash due to attempting to do them twice.

   The userbot session with the lowest ping is the one likely to be left alive for better experience.

## Userbot as a Python REPL

 - **Evaluate a Python expression**
[Syntax: `eval <your Python snippet>`]

   *Multi-line expressions work fine here, as well as asyncio and imports. Cool, isn't it?*

   Executes the Python snippet as if it were a Python script on your machine. The output of this expression is shown as an edited message.

 - **Execute a Python expression**
[Syntax: `exec <your Python snippet>`]

   *Multi-line expressions work fine here, as well as asyncio and imports. Cool, isn't it?*

   Same as the `eval` function above, except that it doesn't return the output of the expression in the chat.

   Note that the asynchronous expressions (like Telethon's methods) needs to be awaited, else it may not execute and just throw a warning at the logs.
   
## Testing tools.

 - **Ping :P**
[Syntax: `ping`]

   Pong, that's it.

 - **Dump raw data of message**
[Syntax: `dump` as a reply to the message]

   Returns the raw data of the message as a Python-structure-like string.

 - **Get userbot traceback logs**
[Syntax: `logs <log level>`]

   Uploads a text file with the userbot traceback data at the specified log level. Know more about the `log level` argument [here](https://docs.python.org/3/library/logging.html#logging-levels "The Python documentation").
   **Logs at level 20 or below may contain personal information**

 - **Suspend the userbot for a few seconds**
[Syntax: `suspend <time in seconds>`]

   Bots get tired too, give them a few seconds of sleep. It won't respond to anything while it's asleep, but when it wakes up, it will answer everything it missed.

## Userbot Updates

 - **Update your userbot**
[Syntax: `update`]

   Updates your userbot to the latest changes in the stable codebase.

 - **Restart your userbot**
[Syntax: `restart`]

   Restarts the userbot.
<!--stackedit_data:
eyJoaXN0b3J5IjpbLTIxMzQyODA4NTEsMTM2ODg2ODM5NCwtNj
cxMjIwMzMyLDY4MTE2MDI4Ml19
-->