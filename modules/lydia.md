# Lydia (AI Chat)

## Acquiring an API key

1. Go to [the CoffeeHouse website](https://coffeehouse.intellivoid.info "the website") and register for an account.

2. Join [the group](https://t.me/IntellivoidDev "the group") and type #activateapi

3. Follow the instructions sent in the group

4. Visit [the website](https://coffeehouse.intellivoid.info "the website") again. Now, your API key should be visible. Copy it to your clipboard

5. Enter [the configurator](/web/configuration#configuring-modules). Select: Modules -> Lydia Anti-PM -> CLIENT_KEY and paste the key from your clipboard. Exit the configurator and type `.restart` in Telegram.

## Commands

- **Enable**
[Syntax: `enlydia [user id]`]

   Enables Lydia AI for the specified user ID, or for the user you are messaging

 - **Disable**
[Syntax: `dislydia [user id]`]

   Disables Lydia for the specified user, or the user you are messaging

 - **Enable in Groups**
[Syntax: `forcelydia [user id]`]

   Forcibly enables Lydia for that user. If sent in a group, Lydia will be enabled for that user in the group.

 - **Remove all active sessions**
[Syntax: `cleanlydiasessions`]

   Resets all conversations that are ongoing with Lydia. It will lose all state and context and restart the conversation.

 - **Remove all allowed users**
[Syntax: `cleanlydiadisabled`]

   Re-enables Lydia for everyone. This will not override `IGNORE_NO_COMMON`.

## Configuration

 - **API Key**
[Key: `friendly-telegram.modules.lydia.CLIENT_KEY`, Type: `str`]

   This is the API key, see [here](#acquiring-an-api-key "here")

 - **Ignore users with no common chats**
[Key: `friendly-telegram.modules.lydia.IGNORE_NO_COMMON`, Type: `boolean`]

   If set to `True`, users who find you by username/search will not have Lydia enabled. Lydia will only apply for users who have groups in common with you. Note that `forcelydia` can still override this.
<!--stackedit_data:
eyJoaXN0b3J5IjpbLTE5MDg0ODA2ODksLTk4MzI0MDg2MF19
-->
