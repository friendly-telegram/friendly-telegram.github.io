# Translations

Friendly-Telegram supports translation of most [strings](https://techterms.com/definition/string "definition"). Currently, there is not a very easy way to make translations packs, but it is possible. This is a guide on how to do so.

1. Set up locally
   You can't create a translation pack if you are using Heroku. This is due to restrictions placed on apps by Heroku itself, and is not fixable, nor a bug. 

   You can read more on local setup in [the docs](/installing "Installation")
2. Open the web interface
   On whatever device is hosting friendly-telegram, visit [this link](http://localhost:8080). It will open the friendly-telegram sign-in page. This page is secure, as the data inputted never leaves your device. 
3. On this page, click the blue button (if there are multiple, it doesn't matter which you click). Enter the authentication code found in your saved messages. You will be presented with the welcome page.
4. From the welcome page, click the hamburger menu button located in the top left. Choose the `Translations` option from the list, and proceed to the next step.
5. Enter the ISO 639-1 language code into the textbox (pre-filled with `en`)
6. Click the link for the module you want to translate
7. Change the strings
8. Click the purple button in the bottom right to return to the top of the page
9. Click `Export Data`
10. Save the file somewhere on your hard disk
11. Create a Telegram channel. Name it however you want
12. Upload the file you downloaded to this channel. You **must** put a caption of `#ftgtrnsl1` on the file.
13. Find the ID of the channel by typing `.exec message.edit(str(message.to_id))`
14. In your saved messages, or a testing group, type `.add
<!--stackedit_data:
eyJoaXN0b3J5IjpbMTA2ODk1OTYyNCwtMTA2NDkwMTA4XX0=
-->