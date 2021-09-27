---
layout: post
title:  "Changelog 2021-09-19"
date:   2021-09-19 21:54:55
author: Josh
---
**Auto-Moderation:**
- A new command, **!automod**, has replaced all of the existing auto-mod commands and allows you to fully customize all the filters with fancy buttons and dropdown boxes.
- An experimental scam detection auto-mod filter has been added - it's purpose is to detect scam bots or compromised accounts who spam your server with messages like "free nitro giveaway! &lt;insert scam website here&gt;". It's disabled by default but if your server encounters these bots, you can give this filter a try.

**Miscellaneous:**
- Added years to the accepted letters for duration formats (the letter `y`)
- Mutes and bans now have a maximum duration of 1 year and 5 years respectively
- The buttons in the **!setup** command have been re-ordered to avoid moving buttons to where the next button was, so you can spam the next button without fear of another button jumping into it's place
- Individual config commands have now been removed as the **!setup** procedure handles all of the settings
- **!info** no longer shows "Joined server: Unknown" if the user is not in the server
- Fixed **!pardon** and **!unpardon** using the old timestamp formatting instead of the new formatting
- Fixed embeds for server logs (message deleted, user joined, etc.) using slightly different colors than the rest of the bot embeds
- Various minor text adjustments

**Bug fixes:**
- Fixed certain instances of a formatting issue with the malicious links auto-mod filter punishment quoting (quoted messages would sometimes not correctly display `code blocks` on mobile)
