# Moderation

<!-- tabs:start -->

#### ** English **

Hello!

#### ** French **

Bonjour!

#### ** Italian **

Ciao!

<!-- tabs:end -->

Learn about our moderation commands!

## Warns

``s!warn @target [reason]``

Warn the target user for the specified reason. They will be notified in DM's and the warn will be added to their list.


> Note that the target must have DM's on in order to be notified of the ban.

<br/><br/>
Required user permissions: ``VIEW_AUDIT_LOG``

Required bot permissions: ``SEND_MESSAGES``
<br/><br/>

``s!warns @target``

Retrieve all warns from the mentioned user, or yourself if nobody is mentioned.

<br/><br/>
Required user permissions: ``VIEW_AUDIT_LOG`` (This permission is only needed if somebody is trying to view warns that do not belong to them.)

Required bot permissions: ``SEND_MESSAGES``
<br/><br/>

``s!clearwarns @target``

Clear all warns from the mentioned user, or yourself if nobody is mentioned.

<br/><br/>
Required user permissions: ``VIEW_AUDIT_LOG``

Required bot permissions: ``SEND_MESSAGES``

## Bans

``s!ban @target [reason]``

Ban the mentioned member. The member will be notified and will see the reason. The reason will also be put in the audit log.


> Note that the target must have DM's on in order to be notified of the ban.

<br/><br/>
Required user permissions: ``BAN_MEMBERS``

Required bot permissions: ``SEND_MESSAGES, BAN_MEMBERS``

## Kicks

``s!kick @target [reason]``

Ban the mentioned member. The member will be notified and will see the reason. The reason will also be put in the audit log.


> Note that the target must have DM's on in order to be notified of the kick.

<br/><br/>
Required user permissions: ``KICK_MEMBERS``

Required bot permissions: ``SEND_MESSAGES, KCIK_MEMBERS``


