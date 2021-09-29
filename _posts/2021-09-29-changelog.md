---
layout: post
title:  "Changelog 2021-09-29"
date:   2021-09-29 14:03:05
author: Josh
---
**Commands:**
- A new utility command, **!gettime**, has been added which helps you generate timestamps easily

**Miscellaneous:**
- **!lockdown** now denies permission to add reactions
 - Auto-moderation no longer runs in channels or threads the bot can't send messages in, as it is unable to warn users
- Updated various command descriptions and error messages
- Fixed certain error messages referencing configuration commands that no longer exist

**Bug fixes:**
- Certain commands and functions were incorrectly relying on server-wide role permissions when they can be controlled per-channel, so some permission requirements have been relaxed throughout the bot
- Fixed certain functions throughout the bot silently failing when lacking certain permissions
- Fixed **!reply** showing the moderator's reply message in the DM relay channel if the DM failed with certain permission setups
- Fixed **!lockdown** failing when lacking certain thread permissions

**Threads and !lockdown:**

Since the release of threads on Discord, new permissions exist and you may want to update the Jot's role and grant it **Create Public Threads** and **Create Private Threads**. Both of these permissions are required for **!lockdown** to deny permission to create and send messages inside threads. Without these, lockdown will not affect threads, as the bot cannot control permissions it doesn't have.
