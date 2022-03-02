---
layout: post
title:  "Changelog 2022-03-01"
date:   2022-03-01 06:04:40.063
author: Josh
---
This update features some major internal redesigns and updates. Primarily, the start of a transition to slash commands.

If you type / do you see my commands? If not, click my name, hit 'Add to Server', pick your server and press authorize to enable them. You can still use the commands with your custom prefix like always, but you should get used to using slash commands over time.

Lastly, you may have noticed a new timeout feature on Discord. It eliminates the hassle of muted role permissions and you can now use it through the Jot. In short, **/timeout** is the new slash command version of **!mute**. You can still use **!mute** for now, but it will eventually be removed when fully transitioning to slash commands.

**Commands:**
- A new command, **/reasonpresets**, has been added which lets you create preset reasons you can select when using **/warn**, **/timeout**, **/kick** and **/ban**
- **!purgesince** can now be done by right clicking a message → Apps → Purge messages since
- **!detain** is transitioning to using timeouts and can be done by right clicking a user → Apps → Quick timeout
- **/warn**, **/timeout**, **/kick** and **/ban** have been given 'Edit' and 'More' buttons allowing editing and controlling additional settings like denying DM relays or purging messages when banning, without retyping the command
- **/editlog** combines all the functions of modifying the moderation log for a user (previously **!logdelete** and **!pardon**/**!unpardon**)
- Added **/note** edit to allow editing notes without deleting and remaking them

**Auto-moderation:**
- Timeouts can now be used (and are the default) for punishments
- **/automod** now lets you pick which filters you want to run in a channel with the 'Channel overrides' button (for example, you can allow people to spam in a bot channel)
- Duplicate spam filter now deletes all large messages that match the filter, instead of only deleting messages with many empty lines
- Invite links filter now code blocks when quoting to prevent accidentally clicking the links
- Scam detection filter is now slightly more strict and should detect more messages

**Miscellaneous:**
- Units of time are more user friendly to read, for example `/ban @user 30d` used to say '4 weeks, 2 days' but will now say '30 days'
- Reason for **/warn** is now optional
- Removed restriction of kicking and banning bots
- **/buttonroles** no longer disallows making button role messages inside threads
- DM relays now code block any messages with links in them to further prevent scam links being clickable