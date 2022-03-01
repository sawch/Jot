---
title: Permissions and Privacy
permalink: /docs/privacy/
description: An overview of the permissions and information used and stored by the Jot.
---
<div class="panel panel-primary">
	<div class="panel-heading">
		<h3 class="panel-title" id="permissions">Permissions</h3>
	</div>
	<div class="panel-body">
    <table class="table table-striped table-hover ">
  <thead>
    <h6>The following table details what permissions the bot uses, and each of the functions that require it.</h6>
    <tr>
      <th>Permission</th>
      <th>Purpose</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Timeout Members</td>
      <td><code>/timeout</code>, auto-mod timeout punishment</td>
    </tr>
    <tr>
      <td>Kick Members</td>
      <td><code>/kick</code>, auto-mod kick punishment</td>
    </tr>
    <tr>
      <td>Ban Members</td>
      <td><code>/ban</code>, auto-mod ban punishment</td>
    </tr>
    <tr>
      <td>Manage Roles</td>
      <td>Assigning roles via button roles, modifying channel permissions via <code>/lockdown</code></td>
    </tr>
    <tr>
      <td>Manage Messages</td>
      <td>Auto-mod deleting caught messages, bulk-deleting messages in channels via <code>Purge messages since</code></td>
    </tr>
    <tr>
      <td>Read Message History</td>
      <td>Fetching the collection of messages to bulk-delete via <code>Purge messages since</code></td>
    </tr>
    <tr>
      <td>Manage Channels</td>
      <td><code>/slowmode</code> for text channels</td>
    </tr>
    <tr>
      <td>Manage Threads</td>
      <td><code>/slowmode</code> for threads, allows logging messages in private threads</td>
    </tr>
    <tr>
      <td>Create Public / Private Threads</td>
      <td>Allows <code>/lockdown</code> to deny users from creating or talking in threads</td>
    </tr>
    <tr>
      <td>Embed Links</td>
      <td>Enables the bot to use fancy embed messages (the bot won't function without this)</td>
    </tr>
  </tbody>
</table>
	</div>
</div>
<div class="panel panel-primary">
	<div class="panel-heading">
		<h3 class="panel-title" id="privacy">Privacy</h3>
	</div>
	<div class="panel-body">
    <h6><strong>Definitions:</strong></h6>
    <ul>
    <li><h6>"The bot" refers to the Jot Discord bot.</h6></li>
    <li><h6>"The database" refers to the database file for your Discord server. Each Discord server the bot is in has it's own isolated database file for server-specific data storage.</h6></li>
    </ul>
    <hr/>
    <h6>The following list details what data the bot will store in the database while in your server. You can view the database schema <a href="/jot/assets/database_schema.pdf">here</a> which shows precisely how the data is stored for each server.</h6>
    <ul>
      <li><h6>The user IDs, user names (e.g Name#0000), reason message and dates associated with moderation actions and notes in the log - the users being: the issuing moderator, the user issued to, and the pardoning moderator (if any)</h6></li>
      <li><h6>The IDs of the moderation log channel, server log channel and DM relay channel, if any are configured</h6></li>
      <li><h6>The IDs of the muted role and the moderation roles, if any are configured</h6></li>
      <li><h6>The configured settings for the auto-moderation filters (enabled, punishment, punishment duration, patience, threshold and time window)</h6></li>
      <li><h6>The IDs and permissions of channels visible to the bot, only after using the <code>/lockdown start</code> command - this data is then deleted upon <code>/lockdown end</code></h6></li>
      <li><h6>The IDs of linked servers, if any are configured</h6></li>
    </ul>
    <h6>The bot also maintains a separate, single 'global' database which contains the following:<br/></h6>
    <ul>
      <li><h6>The user ID, server ID, remaining uses and creation date of DM relays created when moderation actions occur in a server with the DM relay channel configured</h6></li>
      <li><h6>The Patreon and Discord user IDs, expiration dates and upgrade token amounts of patrons who connect their Discord and Patreon accounts together either through Patreon itself or by request</h6></li>
      <li><h6>The server ID, server name and the token owner's Discord user ID for each upgrade token that is currently applied to a server</h6></li>
      <li><h6>Various configuration variables which are not generated from or related to any specific servers</h6></li>
    </ul>
    <h6>The bot does not save any messages it sees to disk. It keeps a cache of the latest messages in each channel it can see, in RAM, which is lost whenever the bot is shut down.</h6>
    <h6>The bot does not disclose any information or data, including but not limited to the data listed above, to any third party services, business or individuals. Any data received from Discord and Patreon is kept confidential and only used for the functions of the bot stated on this website.</h6>
	</div>
</div>
