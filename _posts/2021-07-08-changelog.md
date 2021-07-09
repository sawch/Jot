---
layout: post
title:  "Changelog 2021-07-08"
date:   2021-07-09 00:54:54
author: Josh
---
**Commands:**
- **!logdelete** now allows specifying `all` instead of a log # to delete all logs for a user
- **!note remove** now allows specifying `all` instead of a note # to delete all notes for a user
- **!info** now has a convenient button to show logs (essentially doing the **!log** command for you)

**Miscellaneous:**
- "User joined the server and has X on record" also given the convenient button to show logs
- Fixed some grammar issues in "something went wrong" error messages
- Changed ambiguous "you do not have authority over &lt;user&gt;" phrasing to explicitly state the issue is the role positions
- Messages sent in rules and announcement channels in community servers will be ignored by the bot

**Bug fixes:**
- Fixed **!detain** and **!mute** throwing errors when lacking the **Voice Channel Move Members** permission
- Fixed issue where **!purgesince** wouldn't function correctly when purging in the same channel the command was issued in
- Fixed issue in **!purgesince** where certain messages could be out of order in the log
- Fixed issue in **!setup** where moving to the mod log channel would show a non-functional back button when it says "successfully set mod log channel to #channel"

This update features a fair bit of internal changes, if you encounter any bugs or weird behavior, come report it the [Jot Discord server](https://discord.gg/xmPMufUF9N)! ![:jotheart:](/jot/assets/img/emotes/jotheart.png)
