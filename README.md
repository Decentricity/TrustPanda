# TrustPanda
A chatbot I made that automagically puts everything you mention it in (on Telegram and Whatsapp) on Blockchain.
Load the json file in the http://nodered.org flow editor and you should see the following screenshots.
You can safely ignore Flow 2 since that is used for testing purposes (i.e., default responses, unrelated to Blockchain).
Flow 1 and Flow 3 finds any user input with a specified hashtag (#blockchainthis) and puts it on the Factom blockchain.

## Flow 1
![TrustPanda Screenshot](/TrustPanda1.png)
## Flow 2
![TrustPanda Screenshot](/TrustPanda2.png)
## Flow 3
![TrustPanda Screenshot](/TrustPanda3.png)

To get it to work, you have to replace "botxxxxx14:ReplaceWithYourBotTokenHere" with your own Telegram Bot token, and replace "https://stampd.io/api/v2/init?secret_key=SECRET&client_id=SECRETUSER" with your own Stampd token.

If you deploy correctly, you'll be able to interact with the bot, using the following hashtags:

## Sample 1
![TrustPanda Screenshot](/TrustPandaA.png)
## Sample 2
![TrustPanda Screenshot](/TrustPandaB.png)
## Sample 3
![TrustPanda Screenshot](/TrustPandaC.png)
