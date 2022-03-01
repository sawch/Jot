---
title: Moderation Commands
permalink: /docs/cmds-mod/
description: A list of the moderation commands found in the Jot.
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
		<h3 class="panel-title" id="warn">/warn</h3>
	</div>
	<div class="panel-body">
    <h6>Warn a user (user is notified via DM).<br/><br/><code>/warn &lt;user&gt;</code> usable by: <strong>Moderators</strong></h6>
	</div>
</div>
<div class="panel panel-primary">
	<div class="panel-heading">
		<h3 class="panel-title" id="timeout">/timeout</h3>
	</div>
	<div class="panel-body">
    <h6>Timeout a user for a certain amount of time (user is notified via DM).<br/><br/><code>/timeout &lt;user&gt; &lt;duration&gt;</code> usable by: <strong>Moderators</strong></h6>
	</div>
</div>
<div class="panel panel-primary">
	<div class="panel-heading">
		<h3 class="panel-title" id="untimeout">/untimeout</h3>
	</div>
	<div class="panel-body">
    <h6>Remove a timeout from a user.<br/><br/><code>/untimeout &lt;user&gt;</code> usable by: <strong>Moderators</strong></h6>
	</div>
</div>
<div class="panel panel-primary">
	<div class="panel-heading">
		<h3 class="panel-title" id="kick">/kick</h3>
	</div>
	<div class="panel-body">
    <h6>Kick a user from the server (user is notified via DM).<br/><br/><code>/kick &lt;user&gt;</code> usable by: <strong>Moderators</strong></h6>
	</div>
</div>
<div class="panel panel-primary">
	<div class="panel-heading">
		<h3 class="panel-title" id="ban">/ban</h3>
	</div>
	<div class="panel-body">
    <h6>Ban a user from the server (user is notified via DM).<br/><br/><code>/ban &lt;user&gt; &lt;duration&gt;</code> usable by: <strong>Moderators</strong></h6>
	</div>
</div>
<div class="panel panel-primary">
	<div class="panel-heading">
		<h3 class="panel-title" id="unban">/unban</h3>
	</div>
	<div class="panel-body">
    <h6>Unban a user.<br/><br/><code>/unban &lt;user&gt;</code> usable by: <strong>Moderators</strong></h6>
	</div>
</div>
<div class="panel panel-primary">
	<div class="panel-heading">
		<h3 class="panel-title" id="reply">/reply</h3>
	</div>
	<div class="panel-body">
    <h6>Reply to a user who has responded to a moderation action via a DM relay.<br/><br/><code>/reply &lt;user&gt; &lt;message&gt;</code> usable by: <strong>Moderators</strong></h6>
	</div>
</div>
<div class="panel panel-primary">
	<div class="panel-heading">
		<h3 class="panel-title" id="lockdown">/lockdown</h3>
	</div>
	<div class="panel-body">
    <h6>Lock down public channels to help mitigate a raid.<br/><br/><code>/lockdown &lt;start/end&gt;</code> usable by: <strong>Moderators</strong></h6>
	</div>
</div>
