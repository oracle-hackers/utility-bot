# utility bot
Utility is a discord bot written using a custom library that makes using Discord User Tokens easy.

To minimize the risk of accounts being flagged, all requests are performed via a selection of HQ rotating residential proxies, custom written headers, as well as complete json (all extra parameters). These and other security features make the request seem as they come from a selection of device types, resolutions, app/browser/mobile etc; ultimately making them ultra utltra realistic.

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

- `setbio <user token> <bio>`

    example: `>setbio OTQxNzYxKMNU1MTA4NTczMTg0.YiwqMM.rFh46A8_Y7MAQKqw9pOriwYuL_B i am very smart`
    returns:
    
    <img width="243" alt="Screen Shot 2022-05-22 at 6 28 02 PM" src="https://user-images.githubusercontent.com/105528391/169681920-08b03c3f-e6ad-41de-b55e-708ce6dc6852.png">

​​
​​

- `pfp <user token> [.png or .jpg image link]` if no image link given, a random image will be used

    example: `>pfp OTQxNzYxKMNU1MTA4NTczMTg0.YiwqMM.rFh46A8_Y7MAQKqw9pOriwYuL_B`
    example: `>pfp OTQxNzYxKMNU1MTA4NTczMTg0.YiwqMM.rFh46A8_Y7MAQKqw9pOriwYuL_B https://upload.wikimedia.org/wikipedia/commons/thumb/6/6e/Golde33443.jpg/440px-Golde33443.jpg` 
    returns:
    
    <img width="411" alt="Screen Shot 2022-05-22 at 6 54 27 PM" src="https://user-images.githubusercontent.com/105528391/169682872-d92e57ba-478c-4015-a2a3-8d761b07dcfb.png">

​​
​​

- `join <user token> <server invite (https://discord.gg/, discord.com/invite/, discordapp.com/invite/)>`

    example: `join OTQxNzYxKMNU1MTA4NTczMTg0.YiwqMM.rFh46A8_Y7MAQKqw9pOriwYuL_B https://discord.gg/`
    returns:
    
    <img width="265" alt="Screen Shot 2022-05-22 at 7 45 29 PM" src="https://user-images.githubusercontent.com/105528391/169684496-6b7af0dc-7f8e-4951-b6c9-f3be5ed07ca9.png">
    
​​
​​

## bug reporitng
[make an issue](https://github.com/oracle-hackers/utility-bot/issues)

## feature suggestions
[make an issue](https://github.com/oracle-hackers/utility-bot/issues)

## questions and support
[github discussions](https://github.com/oracle-hackers/utility-bot/discussions)
