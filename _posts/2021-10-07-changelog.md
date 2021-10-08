---
layout: post
title:  "Changelog 2021-10-07"
date:   2021-10-07 22:51:16
author: Josh
---
**Auto-moderation changes:**
- Auto-moderation now requires the moderation log channel to be defined, to prevent it from silently running and doing things without you knowing
- If the bot lacks **Manage Roles** (muting), **Kick Users** or **Ban Users** permissions when auto-mod punishments are attempted, it will report an error and be disabled rather than continuing verbal warnings without punishment 

**Miscellaneous:**
- **!setup** now allows un-setting the muted role
- The amount of moderator roles allowed to be set in **!setup** has been limited to 15, rather than as many as you can fit into a single message
- **!warn** no longer undetains users if the DM fails
- Corrected typo in **!buttonroles** error message when replying with an invalid role ID
- Corrected **!lockdown** and **!reply** error messages mentioning config commands that no longer exist

**Bug fixes:**
- Fixed DM failed embeds being detached from the 'Action Issued' embeds
- Fixed "user was detained and is now..." footers in embeds being possibly out of date when a moderation action is confirmed
- Fixed situation where auto-mod quotes would format incorrectly with code blocks
- Fixed **!upgrade** displaying an incorrect expiration date for upgrade tokens in certain situations
- Fixed issue where mute and temporary ban timers would silently expire and not unmute or unban if the bot lacked **Manage Roles**/**Ban Users** permissions, instead it will now give periodic warnings until the issue is resolved
- Fixed issue where **!lockdown** would not work if the bot did not have an integrated role
- Fixed scam detection auto-mod filter waiting until all detected scam messages were deleted before muting the user
