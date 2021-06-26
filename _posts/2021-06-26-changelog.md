---
layout: post
title:  "Changelog 2021-06-26"
date:   2021-06-26 20:42:03
author: Josh
---
**Commands:**
- **!info** now shows if the user is currently detained or banned in the footer
- **!ping** added information about the bot's current threads and tasks
- **!purgesince** now also accepts message links copied on the canary version of Discord (e.g. https://canary.discord.com/channels/123/456/789)

**Auto-mod:**
- Allowed time range for **message spam** filter increased from 2-8 seconds to 4-10 seconds, as 2 seconds between messages could be defeated by Discord's built in rate limiting
- Auto-mod quoting improved to collapse big empty space and stop text from going outside of the quote block

**Bug fixes:**
- Fixed an issue causing `!lockdown` to fail or not change connect permissions when encountering stage channels
