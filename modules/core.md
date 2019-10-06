# Core

Core modules that are always loaded to the userbot

## Core Control

 - **Blacklist** [Syntax: `blacklist <chat id>`]

   Disables all userbot commands in that chat.

   NOTE: the current chat is used when `<chat id>` is not given.

 - **Unblacklist** [Syntax: `unblacklist <chat id>`]

   Removes the chat from the blacklist.

   NOTE: the current chat is used when `<chat id>` is not given.

 - **Set command prefix** [Syntax: `setprefix <command prefix>`]

   Sets the prefix to be used for commands.

 - **Add command alias** [Syntax: `addalias <alias> <command>`]

   The default command names too long for you?

   Set an alias for it using this command.

## Help and Support

 - **Getting help for commands** [Syntax: `help <command>`]

   Shows you the help text for the specified command name.

 - **Join support chat** [Syntax: `support`]

   Join the support chat for more help from the community.

## Loading and unloading modules

 - **Downloading modules** [Syntax: `dlmod <module name>`]

   Downloads the specified module from the official modules repository.

 - **Module Presets** [Syntax: `dlpreset <preset name>`]

   Quickly change userbot "Profiles" according to your need.

   Available presets:
    - *Full:* `dlpreset full` loads all modules (default).
    - *Minimal:* `dlpreset minimal` loads a minimal set of modules.
    - *None:* `dlpreset none` loads only the core modules.

 - **Loading custom modules**

   [Syntax: `loadmod <path to module file>` (or) reply to a module file with `loadmod`]

   Loads the 3rd party (external) module into your userbot.

   *Did you know that this feature also loads Paperplane and UniBorg modules too?*

 - **Unloading custom modules**

   [Syntax: `loadmod <path to module file>` (or) reply to a module file with `loadmod`]

   Loads the 3rd party (external) module into your userbot.

   *Did you know that this feature also loads Paperplane and UniBorg modules too?*
