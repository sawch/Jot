---
layout: post
title:  "Changelog 2023-09-23"
date:   2023-09-26 12:58:31.049
author: Josh
---
**Discord usernames:**
- The Jot has been updated to support the new username system that Discord has introduced - migrated users who have previously shown up as 'username#0' or 'username#0000' will now properly display as @username
- Note that old usernames in moderation logs cannot be changed and will still show the usernames from the time they occurred

**Legacy prefix commands:**
- Back in March 2022 the Jot introduced slash commands - the old **!prefix** command system has remained accessible for servers that were using the Jot before this update, however the old command system has now been removed

**Commands:**
- **/unban** now accepts an optional reason and unbans will now be added to user's moderation logs

**Auto-moderation:**
- The **Mute (deprecated)** auto-mod punishment setting has been removed as it can no longer be configured with the removal of the old **!prefix** command system
- Servers using the **Mute (deprecated)** auto-mod punishment setting have been automatically switched to **Timeout**

**Bug fixes:**
- Fixed the message link formatting in the hyperlink section of the moderation tips found in **/help**
- Fixed some instances of backslashes showing up incorrectly when usernames are written in the Jot's messages
