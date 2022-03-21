# FiveM-Discord-Status
 Updated Version of Live Status from my previous repo (https://github.com/Gravxd/FiveM-Server-Status-Bot)

**Note: Only members with administrator perms can setup the live status!** 


`Setup`

First, navigate to the channel you want to have the live status display into.
Then use !setup.

This will send a message from the bot into the channel you used the command in. 
Once the bot sends the message, right click this message and copy the id. This will be the `messageID` that we need for the `settings.json`.

Fill in all sections of the `settings.json` file.

Once this is done, go to `token.json` and put your discord bot token into it.
If you do not know how to get a bot token, go to https://discord.dev

Once the token is entered, the bot can be launched by opening the `startBot.bat` file!

**Any issues, please join the [support server.](https://discord.gg/ZYHxxba)**

`Example`

This is an example of how a completed `settings.json` file should look like:

{
    "ip": "45.85.194.174",
    "port": "30120",
    "serverID": "747117497060163666",
    "channelID": "799629722836402186",
    "messageID": "799645249718321212",
    "refreshTime": "5", 
    "color": "#035efc",
    "errorColor": "#035efc",
    "embedTitle": "GravHub",
    "embedErrorTitle": "GravHub",
    "enableChannelStatus": "Yes",
    "channelStatusID": "782616107584323584"
}

The last two options are for if you want a channel name to be updated with the player count.

If you set the enableChannelStatus to 'No.', then it will disable this.

channelID & channelStatusID do not have to the be the same.