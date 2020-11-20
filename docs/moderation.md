# Moderation

Learn about our moderation commands!

## Mutes

<!-- tabs:start -->

#### ** Mute **

``s!warn @target [reason]``

Add the muted role to the target user for the specified reason.

If there is no muted role you can create one with the Create muterole command.

<br/><br/>
Required user permissions: ``MANAGE_ROLES_OR_PERMISSIONS``

Required bot permissions: ``SEND_MESSAGES, MANAGE_ROLES_OR_PERMISSIONS``

#### ** Unmute **

``s!unmute @target [reason]``


Remove the muted role to the target user for the specified reason.

If there is no muted role you can create one with the Create muterole command.

<br/><br/>
Required user permissions: ``MANAGE_ROLES_OR_PERMISSIONS``

Required bot permissions: ``SEND_MESSAGES, MANAGE_ROLES_OR_PERMISSIONS``

#### ** Create muterole **

``s!createmuterole``

Create a role called "Muted" with a black color. The role will be placed directly under the bot's highest role and all channels the bot has access to will have a permission override that prevents users with the Muted role from speaking. If any new channels are created after the muted role is made, permission overrides must be manually added.

<br/><br/>
Required user permissions: ``MANAGE_ROLES_OR_PERMISSIONS``

Required bot permissions: ``SEND_MESSAGES, MANAGE_ROLES_OR_PERMISSIONS``

<!-- tabs:end -->

## Slowmode Manager

``s!slowmode [duration]``

Set the slowmode of the current channel to the specified duration.

Input should be an integer which will get interpreted as seconds.

<br/><br/>
Required user permissions: ``MANAGE_CHANNELS``

Required bot permissions: ``SEND_MESSAGES``

## Warns

<!-- tabs:start -->

#### ** Warn **

``s!warn @target [reason]``


Warn the target user for the specified reason. They will be notified in DM's and the warn will be added to their list.


> Note that the target must have DM's on in order to be notified of the ban.

<br/><br/>
Required user permissions: ``VIEW_AUDIT_LOG``

Required bot permissions: ``SEND_MESSAGES``

#### ** Get Warns **

``s!warns @target``

Retrieve all warns from the mentioned user, or yourself if nobody is mentioned.

<br/><br/>
Required user permissions: ``VIEW_AUDIT_LOG`` (This permission is only needed if somebody is trying to view warns that do not belong to them.)

Required bot permissions: ``SEND_MESSAGES``

#### ** Clear Warns **

``s!clearwarns @target``

Clear all warns from the mentioned user, or yourself if nobody is mentioned.

<br/><br/>
Required user permissions: ``VIEW_AUDIT_LOG``

Required bot permissions: ``SEND_MESSAGES``

<!-- tabs:end -->
## Bans

``s!ban @target [reason]``

Ban the mentioned member. The member will be notified and will see the reason. The reason will also be put in the audit log.


> Note that the target must be accepting DM's in order to be notified of the ban.

<br/><br/>
Required user permissions: ``BAN_MEMBERS``

Required bot permissions: ``SEND_MESSAGES, BAN_MEMBERS``

## Kicks

``s!kick @target [reason]``

Ban the mentioned member. The member will be notified and will see the reason. The reason will also be put in the audit log.


> Note that the target must be accepting DM's in order to be notified of the kick.

<br/><br/>
Required user permissions: ``KICK_MEMBERS``

Required bot permissions: ``SEND_MESSAGES, KCIK_MEMBERS``


