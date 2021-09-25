---
title: Information Commands
permalink: /docs/cmds-info/
image: /assets/img/logo_256.png
description: A list of the information commands found in the Jot.
---
<div class="panel panel-info">
	<div class="panel-heading">
		<h3 class="panel-title" id="warn">Quick Note!</h3>
	</div>
	<div class="panel-body">
    <table class="table table-striped table-hover ">
    <thead>
      <h6>The bot only permits moderators to do what their roles allow. For example, the bot will not let moderators who do not have the <strong>Ban Users</strong> permission to ban users through the bot - you can design your moderators roles to permit what you want, and this bot will take care of the rest!</h6>
      <tr>
        <th>Usable by</th>
        <th>Who can use it</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>ServerOwner</td>
        <td>Only the owner of the server can use these commands.</td>
      </tr>
      <tr>
        <td>Administrators</td>
        <td>Only users with the <strong>Administrator</strong> or <strong>Manage Server</strong> permission can use these commands.</td>
      </tr>
      <tr>
        <td>Moderators</td>
        <td>Users with any of the defined moderator roles can use these commands.</td>
      </tr>
    </tbody>
    </table>
	</div>
</div>
<div class="panel panel-primary">
	<div class="panel-heading">
		<h3 class="panel-title" id="note">!note</h3>
	</div>
	<div class="panel-body">
    <h6>Add or remove notes for a user. Actions are <code>add</code> or <code>remove</code>. The <code>note</code> is either your note text, the number displayed next to a note, or <code>all</code> (to delete all notes).<br/><br/><code>!note &lt;action&gt; &lt;user ID&gt; &lt;note&gt;</code> usable by: <strong>Moderators</strong></h6>
	</div>
</div>
<div class="panel panel-primary">
	<div class="panel-heading">
		<h3 class="panel-title" id="notes">!notes</h3>
	</div>
	<div class="panel-body">
    <h6>View notes for a user.<br/><br/><code>!notes &lt;user ID&gt;</code> usable by: <strong>Moderators</strong></h6>
	</div>
</div>
<div class="panel panel-primary">
	<div class="panel-heading">
		<h3 class="panel-title" id="logdelete">!logdelete</h3>
	</div>
	<div class="panel-body">
    <h6>Delete an entry in a user's log of moderation actions. The <code>log #</code> is the number displayed next to moderation actions in the log for a user, specify <code>all</code> to delete all logs for the user. <strong>This cannot be undone.</strong><br/><br/><code>!logdelete &lt;user ID&gt; &lt;log #&gt;</code> usable by: <strong>Administrators</strong></h6>
	</div>
</div>
<div class="panel panel-primary">
	<div class="panel-heading">
		<h3 class="panel-title" id="notes">!pardon</h3>
	</div>
	<div class="panel-body">
    <h6>Pardon a moderation action that was issued to a user, showing it as pardoned in the log. Does not notify the user. The <code>log #</code> is the number displayed next to moderation actions in the log for a user.<br/><br/><code>!pardon &lt;user ID&gt; &lt;log #&gt;</code> usable by: <strong>Moderators</strong></h6>
	</div>
</div>
<div class="panel panel-primary">
	<div class="panel-heading">
		<h3 class="panel-title" id="unpardon">!unpardon</h3>
	</div>
	<div class="panel-body">
    <h6>Remove a pardon for a moderation action that was issued to a user. Does not notify the user. The <code>log #</code> is the number displayed next to moderation actions in the log for a user.<br/><br/><code>!unpardon &lt;user ID&gt; &lt;log #&gt;</code> usable by: <strong>Moderators</strong></h6>
	</div>
</div>
<div class="panel panel-primary">
	<div class="panel-heading">
		<h3 class="panel-title" id="timers">!timers</h3>
	</div>
	<div class="panel-body">
    <h6>Displays the active timers for temporary bans and mutes, if any. <code>type</code> is optional, specify <code>mutes</code> or <code>bans</code> to only show the desired timers.<br/><br/><code>!timers &lt;type&gt;</code> usable by: <strong>Moderators</strong></h6>
	</div>
</div>
<div class="panel panel-primary">
	<div class="panel-heading">
		<h3 class="panel-title" id="info">!info</h3>
	</div>
	<div class="panel-body">
    <h6>Displays a summary of user info like number of warnings, bans, dates, etc.<br/><br/><code>!info &lt;user ID&gt;</code> usable by: <strong>Moderators</strong></h6>
	</div>
</div>
<div class="panel panel-primary">
	<div class="panel-heading">
		<h3 class="panel-title" id="modstats">!modstats</h3>
	</div>
	<div class="panel-body">
    <h6>Displays the moderation actions issued by the given user. Omit the <code>user ID</code> to display stats for yourself.<br/><br/><code>!modstats &lt;user ID&gt;</code> usable by: <strong>Administrators</strong></h6>
	</div>
</div>
<div class="panel panel-primary">
	<div class="panel-heading">
		<h3 class="panel-title" id="serverinfo">!serverinfo</h3>
	</div>
	<div class="panel-body">
    <h6>Displays information about the server and its moderation.<br/><br/><code>!serverinfo</code> usable by: <strong>Moderators</strong></h6>
	</div>
</div>
