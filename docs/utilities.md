# Utilities

## Ping

``s!ping``

Get the bot and DiscordAPI ping.

Required Permissions: NONE
<br/><br/>

## Reminders
``s!remind/rm [delay] [message]``

Remind you about your message after your delay has passed. The bot will dm you with your message.

Required Permissions: NONE
<br/><br/>

## Avatar Fetcher
``s!avatar @target``

Get the avatar of the mentioned user, or yourself if no mentions are found.

Required Permissions: NONE
<br/><br/>

## User Info Fetcher
``s!userinfo @target``

Gets the following info about the mentioned user:

+ User ID

+ User nickname in current guild

+ User status

+ User [AFK](utilities.md#Afk) Info

+ Is user a bot?

+ Server join date

+ Account creation date

+ All roles in current server

Required Permissions: NONE
<br/><br/>

## Afk

``s!afk [message]``

Toggle your afk.

If your AFK is off your afk will be turned on and set to the message you provided, or "AFK" if no message is provided.

If your AFK is on it will be turned off.

Your AFK will be displayed in your [user info](#user-info-fetcher) and will be shown when you are mentioned.

Required Permissions: NONE
<br/><br/>

## Purge

``s!purge [quantity]``

Delete the specified number of messages in the current channel. 

Required Permissions: MANAGE_MESSAGES
<br/><br/>

## Snipe

``s!snipe``

Retrieve the last deleted message in the current channel

Required Permissions: VIEW_AUDIT_LOG
<br/><br/>

## Edit Snipe

``s!esnipe``

Retrieve the content of the last edited message in the current channel, both before and after edits.

Required Permissions: VIEW_AUDIT_LOG
