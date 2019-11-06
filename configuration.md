# Configuration

The configuration interface is really easy! Just read this document

## Entering configuration

```
python -m friendly-telegram --setup
```

## Configuring modules

This userbot is highly modular and each module can be configured individually, or disabled entirely.
If you disable a module, it will not be loaded at startup. To re-enable it, you have to edit the configuration and restart the userbot.

Module settings are stored **inside your Telegram account**. To debug this, search for a chat named `friendly-{id}-data`. It contains a JSON dump of the database. **Do not delete it!**. This includes config as well as other data such as your AFK status. **You should never share this message or add anyone to that chat**. It contains personal data such as API keys. 

To set a module config, first enter the configurator. Select Modules. Choose the module you want to set an API key for, and press return. Scroll down to the entry for the api key and enter the value, pressing enter when done.

Note that if you change the config on one computer while hosting on another, you need to restart the bot for it to apply.
<!--stackedit_data:
eyJoaXN0b3J5IjpbLTE2NzQ1MDkzNzVdfQ==
-->