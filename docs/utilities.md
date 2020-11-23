# Utilities

Learn about our utility commands!

## Reminders
``s!remind/rm [delay] [message]``

Remind you about your message after your delay has passed. The bot will dm you with your message.

> Note that the user who used the command must be accepting DM's.

<br/><br/>
Required user permissions: ``None``

Required bot permissions: ``SEND_MESSAGES``

<br/><br/>

<!-- tabs:start -->

#### ** Create **

``s!rrcreate [messageID] [channelID] :emoji: [rolename/@role]``

Reacts to the message assosiated with the specified message ID with the specified emoji. When a user reacts with the same reaction the specified role will be added to them.

Currently custom emoji's are not supported.

Please provide the channel ID for the channel the target message is in. We know it seems unneccesary but without it the bot will take ages to add the reaction and will destory our server.

You can type the role name (even if the role has a space in it, like "Example Role" you can still type the exact name [Don't remove spaces]) or you can @mention the role.

#### ** Delete **

``s!rrdelete [messageID] :emoji:``

Remove the reaction role assosiated with the specified emoji on the specified message. The bot will unreact.

Currently error handling is very poor with this command and the bot may say it deleted the reaction role even if it didn't/there was no reaction role, the bot may say nothing or return the actual error.

<!-- tabs:end -->

## Avatar Fetcher
``s!avatar @target``

Get the avatar of the mentioned user, or yourself if no mentions are found.
<br/><br/>

Required user permissions: ``None``

Required bot permissions: ``SEND_MESSAGES``

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
<br/><br/>

Required user permissions: ``None``

Required bot permissions: ``SEND_MESSAGES``

<br/><br/>
## Afk

``s!afk [message]``

Toggle your afk.

If your AFK is off your afk will be turned on and set to the message you provided, or "AFK" if no message is provided.

If your AFK is on it will be turned off.

Your AFK will be displayed in your [user info](#user-info-fetcher) and will be shown when you are mentioned.
<br/><br/>

Required user permissions: ``None``

Required bot permissions: ``SEND_MESSAGES, MANAGE_NICKNAMES``

<br/><br/>
## Purge

``s!purge [quantity]``

Delete the specified number of messages in the current channel. 
<br/><br/>

Required user permissions: ``MANAGE_MESSAGES``

Required bot permissions: ``SEND_MESSAGES, MANAGE_MESSAGES``

<br/><br/>
## Snipe

``s!snipe``

Retrieve the last deleted message in the current channel
<br/><br/>

Required user permissions: ``VIEW_AUDIT_LOG``

Required bot permissions: ``SEND_MESSAGES, READ_MESSAGE_HISTORY, VIEW_CHANNEL``

<br/><br/>
## Edit Snipe

``s!esnipe``

Retrieve the content of the last edited message in the current channel, both before and after edits.
<br/><br/>

Required user permissions: ``VIEW_AUDIT_LOG``

Required bot permissions: ``SEND_MESSAGES, READ_MESSAGE_HISTORY, VIEW_CHANNEL``
