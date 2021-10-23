---
layout: post
title:  "Changelog 2021-10-22"
date:   2021-10-22 15:47:17
author: Josh
---
**Miscellaneous:**
- **!unban** now prompts you for confirmation and gives you a choice to unban the user in linked servers or just the current one
- Moderation actions issued by auto-mod now write the user ID in the footer so mobile users can easily copy them for follow up actions
- Adjusted auto-mod code-blocked quotes to collapse empty lines to avoid breaking formatting
- Corrected **!purgesince** and **!slowmode** requiring moderators to have server-wide role permissions when it only matters if they have permission in the target channel
- Corrected duplicate spam filter incorrectly stating that the user had been repeatedly warned when they were only warned once

**Bug fixes:**
- Fixed issue where mutes would not occur in linked servers if the target user was not in the linked server, they will now be muted if they join a linked server after being muted elsewhere
- Fixed permanent bans issued by auto-mod having a 0 second timer rather than being actually permanent
