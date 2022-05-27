# utility bot made with [Utilities API](https://bit.ly/utilitiesapifromutilitybotgithubreadme)
Utility is a discord bot written using a custom library that makes using Discord User Tokens easy.

To minimize the risk of accounts being flagged, all requests are performed via a selection of HQ rotating residential proxies, custom written headers, as well as complete json (all extra parameters). These and other security features make the requests seem as they come from a selection of device types, resolutions, app/browser/mobile etc; ultimately making them ultra utltra realistic. **However**, there is no guarantee your accounts are 100% safe; even if you are a real user, changing things too fast/setting off the sus-o-meter of an account will get it locked.

# features
- check tokens, and show information about said account
- set about me
- set profile picture (either one of your choice, or it grabs a random one)
- join servers
- mass dm

# coming soon
- gift buyer
- mass ping
- api

# how to use
1. [invite the bot](https://discord.com/oauth2/authorize?client_id=975381232374403092&amp;scope=bot%20applications.commands&amp;permissions=8)
2. try `>help`, `>info`
3. enjoy!

## command details
<> is required, [] is optional

​​
- `check <user token>`

    example: `>check OTQxNzYxKMNU1MTA4NTczMTg0.YiwqMM.rFh46A8_Y7MAQKqw9pOriwYuL_B` 

    returns:

    <img width="605" alt="Screen Shot 2022-05-22 at 5 42 54 PM" src="https://user-images.githubusercontent.com/105528391/169680717-c459dbee-18b9-495d-8492-a46ab13f75d7.png">

​​
​​
​​

- `setbio <user token> <bio>`

    example: `>setbio OTQxNzYxKMNU1MTA4NTczMTg0.YiwqMM.rFh46A8_Y7MAQKqw9pOriwYuL_B i am very smart`

    returns:
    
    <img width="243" alt="Screen Shot 2022-05-22 at 6 28 02 PM" src="https://user-images.githubusercontent.com/105528391/169681920-08b03c3f-e6ad-41de-b55e-708ce6dc6852.png">

​​
​​
​​

- `pfp <user token> [.png or .jpg image link]` if no image link given, a random image will be used

    example: `>pfp OTQxNzYxKMNU1MTA4NTczMTg0.YiwqMM.rFh46A8_Y7MAQKqw9pOriwYuL_B https://i.imgur.com/4xB15OG.png` 

    returns:
    
    <img width="411" alt="Screen Shot 2022-05-22 at 6 54 27 PM" src="https://user-images.githubusercontent.com/105528391/169682872-d92e57ba-478c-4015-a2a3-8d761b07dcfb.png">

​​
​​
​​

- `join <user token> <server invite>` 

    example: `join OTQxNzYxKMNU1MTA4NTczMTg0.YiwqMM.rFh46A8_Y7MAQKqw9pOriwYuL_B discord.gg/pornhub`

    returns:
    
    <img width="265" alt="Screen Shot 2022-05-22 at 7 45 29 PM" src="https://user-images.githubusercontent.com/105528391/169684496-6b7af0dc-7f8e-4951-b6c9-f3be5ed07ca9.png">

​​
​​
​​

- `send <discord webhook url> <message to send>`

    example: `>send https://discord.com/api/webhooks/392759374855243196/pY5oDkfmyV7f9qsQFdXSgE158191KmdkMkKtC Ai hello monkeys`
    
    returns:
    
    <img width="286" alt="image" src="https://user-images.githubusercontent.com/72248782/169989083-619fc464-85c3-4678-a5cb-f227f8d74d89.png">

    
​​
​​
​​

- `clear`

    example: `>clear` removes the bot's messages within the last 100 messages in the channel

​​
​​


## bug reporitng
[make an issue](https://github.com/oracle-hackers/utility-bot/issues)

## feature suggestions
[make an issue](https://github.com/oracle-hackers/utility-bot/issues)

## questions and support
[github discussions](https://github.com/oracle-hackers/utility-bot/discussions)

