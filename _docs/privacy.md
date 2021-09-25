---
title: Permissions and Privacy
permalink: /docs/privacy/
image: /assets/img/logo_256.png
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
      <td>Kick Members</td>
      <td><code>!kick</code>, auto-mod kick punishment</td>
    </tr>
    <tr>
      <td>Ban Members</td>
      <td><code>!ban</code>, auto-mod ban punishment</td>
    </tr>
    <tr>
      <td>Manage Roles</td>
      <td>Assigning muted role via <code>!mute</code> & <code>!detain</code>, creating a new muted role inside the <code>!setup</code> procedure</td>
    </tr>
    <tr>
      <td>Manage Messages</td>
      <td>Deleting commands and errors, bulk-deleting from channels via <code>!purgesince</code>, allows bot to bypass slowmode</td>
    </tr>
    <tr>
      <td>Read Message History</td>
      <td>Fetching the collection of messages to bulk-delete via <code>!purgesince</code></td>
    </tr>
    <tr>
      <td>Voice Channels - Move Members</td>
      <td>Disconnecting users from voice channels via <code>!mute</code> & <code>!detain</code></td>
    </tr>
    <tr>
      <td>Manage Channels</td>
      <td><code>!slowmode</code>, modifying channel permissions via <code>!lockdown</code></td>
    </tr>
    <tr>
      <td>Manage Threads</td>
      <td><code>!slowmode</code> (for threads), allows logging messages in private threads</td>
    </tr>
    <tr>
      <td>Public / Private Threads</td>
      <td>Allows <code>!lockdown</code> to deny making or using threads</td>
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
    <h6>Each Discord server the bot is in has its own isolated database file. 'The database' refers to the database file for your server.<br/></h6>
    <h6>The following list details what data the bot will store in the database while in your server:<br/></h6>
    <ul>
      <li><h6>The user IDs, user names (e.g Name#0000), reason message and dates associated with moderation actions and notes in the log - the users being: the issuing moderator, the user issued to, and the pardoning moderator (if any)</h6></li>
      <li><h6>The IDs of the moderation log channel, server log channel and DM relay channel, if any are configured</h6></li>
      <li><h6>The IDs of the muted role and the moderation roles, if any are configured</h6></li>
      <li><h6>The configured settings for the auto-moderation filters (enabled, punishment, punishment duration, patience, threshold and time window)</h6></li>
      <li><h6>The IDs and permissions of channels visible to the bot, only after using the <code>!lockdown start</code> command - this data is then deleted upon <code>!lockdown end</code></h6></li>
      <li><h6>The IDs of linked servers, if any are configured</h6></li>
    </ul>
    <h6>The bot also maintains a separate, single 'global' database which contains the following:<br/></h6>
    <ul>
      <li><h6>The user ID, server ID, remaining uses and creation date of DM relays created when moderation actions occur in a server with the DM relay channel configured</h6></li>
      <li><h6>The Patreon and Discord user IDs, expiration dates and upgrade token amounts of users who donate and connect their Discord and Patreon accounts either through Patreon itself or by request</h6></li>
      <li><h6>The server ID, server name and the token owner's Discord user ID for each upgrade token that is currently applied to a server</h6></li>
      <li><h6>Various configuration variables which are not generated from or related to any specific servers</h6></li>
    </ul>
    <h6>The bot does not store message history on disk - it keeps a cache of the latest messages in each channel it can see, the cache is lost whenever the bot is shut down. You can view the database schema <a href="/jot/assets/database_schema.pdf">here</a> which shows how the database for each server is structured.</h6>
	</div>
</div>
