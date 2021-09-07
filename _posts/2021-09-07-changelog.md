---
layout: post
title:  "Changelog 2021-09-07"
date:   2021-09-07 11:19:01
author: Josh
---
The Jot has received some fancy features this time around. It now has a Patreon integration that allows upgrading some functionality via [upgrade tokens](https://sawch.github.io/jot/upgrade/)!

**New features**:
- **Button roles** are reaction roles, but stronger, created via **!buttonroles**.  You can create an unlimited amount of them for free! Full customization requires an upgrade token mentioned above.
- **Server links** allow you to link servers together to share moderation logs and issue mutes, kicks and bans across multiple servers, use **!serverlink** to set them up. This feature requires an upgrade token mentioned above.

**Miscellaneous**:
- Replaced most timestamps with fancy formatting which displays in your local time
- Malicious links auto-mod filter will now put the message in a code block to make malicious links unclickable when being quoted by the bot
- Auto-mod now no longer checks messages made by moderators, administrators or server owners
- Various text adjustments
- The [permissions and privacy page on the website](https://sawch.github.io/jot/docs/privacy/) has been updated to reflect new thread permissions and what the bot uses them for, if they are granted, and the new data stored in association with the Patreon integration.

**Bug fixes:**
- Fixed issue in **!purgesince** where the first deleted message in the log would write the wrong author ID
- Fixed DM relays showing a blank message when stickers are sent
- Fixed issue where **!lockdown** would fail to modify channels with certain thread permission combinations
- Fixed **!setup** and **!mutedrole** accepting bot integration roles which would not work
- Fixed existing DM relays persisting when users get kicked or banned which normally closes the relay
