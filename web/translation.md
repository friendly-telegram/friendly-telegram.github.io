# Translations

Friendly-Telegram supports translation of most [strings](https://techterms.com/definition/string "definition").

## Creating a pack

1. Follow the instructions in [the docs](auth) to log in
2. From the welcome page, click the hamburger menu button located in the top left. Choose the `Translations` option from the list, and proceed to the next step.
3. Enter the ISO 639-1 language code into the textbox (pre-filled with `en`)
4. Click the link for the module you want to translate
5. Change the strings
6. Click the purple button in the bottom right to return to the top of the page
7. Click `Export Data`
8. Save the file somewhere on your hard disk
9. Create a Telegram channel. Name it however you want
10. Upload the file you downloaded to this channel. You **must** put a caption of `#ftgtrnsl1` on the file.
11. Set a username on the channel, so that you can apply it in the next section

## Applying a pack

1. First, you have to know the username of the pack to add. If you don't know one, maybe you want to [create a pack](#creating-a-pack)? Alternatively, you can use the invite link of the pack (you must already be a member), or the channel ID.
2. Type in any chat, `.addtrnsl <pack username>`
3. Type `.restart` to apply the changes
<!--stackedit_data:
eyJoaXN0b3J5IjpbLTQxNzg5MDY0MV19
-->