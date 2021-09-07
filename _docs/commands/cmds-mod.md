---
title: Moderation Commands
permalink: /docs/cmds-mod/
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
		<h3 class="panel-title" id="warn">!warn</h3>
	</div>
	<div class="panel-body">
    <h6>Warn a user. Warns are logged and the user is notified via DM.<br/><br/><code>!warn &lt;user ID&gt; &lt;warn message&gt;</code> usable by: <strong>Moderators</strong></h6>
	</div>
</div>
<div class="panel panel-primary">
	<div class="panel-heading">
		<h3 class="panel-title" id="mute">!mute</h3>
	</div>
	<div class="panel-body">
    <h6>Gives a user the muted role for the specified duration of time, with an optional reason. User is notified via DM. Re-muting an already muted user changes the duration. Duration format examples: <code>1h30m</code>, <code>24h</code>, <code>3d</code>, <code>1w</code>.<br/><br/><code>!mute &lt;user ID&gt; &lt;duration&gt; &lt;reason&gt;</code> usable by: <strong>Moderators</strong></h6>
	</div>
</div>
<div class="panel panel-primary">
	<div class="panel-heading">
		<h3 class="panel-title" id="unmute">!unmute</h3>
	</div>
	<div class="panel-body">
    <h6>Unmutes the given user.<br/><br/><code>!unmute &lt;user ID&gt;</code> usable by: <strong>Moderators</strong></h6>
	</div>
</div>
<div class="panel panel-primary">
	<div class="panel-heading">
		<h3 class="panel-title" id="kick">!kick</h3>
	</div>
	<div class="panel-body">
    <h6>Kicks a user from the server. Reason is optional. User is notified via DM.<br/><br/><code>!kick &lt;user ID&gt; &lt;reason&gt;</code> usable by: <strong>Moderators</strong></h6>
	</div>
</div>
<div class="panel panel-primary">
	<div class="panel-heading">
		<h3 class="panel-title" id="ban">!ban</h3>
	</div>
	<div class="panel-body">
    <h6>Bans a user from the server. Both duration and reason are optional. User is notified via DM. Banning an already banned user will change the duration.<br/>
        Duration format examples: <code>1h30m</code>, <code>24h</code>, <code>3d</code>, <code>1w</code>.<br/>
        Full examples:<br/><br/>
        <code>ban 123456789 24h Rule #1</code> <em>(temporary + reason)</em><br/>
        <code>ban 123456789 Too many warnings.</code> <em>(permanent + reason)</em><br/>
        <code>ban 123456789</code> <em>(permanent)</em><br/><br/><code>!ban &lt;user ID&gt; &lt;duration&gt; &lt;reason&gt;</code> usable by: <strong>Moderators</strong></h6>
	</div>
</div>
<div class="panel panel-primary">
	<div class="panel-heading">
		<h3 class="panel-title" id="unban">!unban</h3>
	</div>
	<div class="panel-body">
    <h6>Unbans a user with the given ID.<br/><br/><code>!unban &lt;user ID&gt;</code> usable by: <strong>Moderators</strong></h6>
	</div>
</div>
<div class="panel panel-primary">
	<div class="panel-heading">
		<h3 class="panel-title" id="detain">!detain</h3>
	</div>
	<div class="panel-body">
    <h6>Silently gives a user the muted role which persists if users leave and rejoin, giving you time to type up a punishment command such as a mute or ban. Users are automatically un-detained upon warning, muting, kicking or banning.<br/><br/><code>!detain &lt;user ID&gt;</code> usable by: <strong>Moderators</strong></h6>
	</div>
</div>
<div class="panel panel-primary">
	<div class="panel-heading">
		<h3 class="panel-title" id="detainees">!detainees</h3>
	</div>
	<div class="panel-body">
    <h6>Displays the list of detained users.<br/><br/><code>!detainees</code> usable by: <strong>Moderators</strong></h6>
	</div>
</div>
<div class="panel panel-primary">
	<div class="panel-heading">
		<h3 class="panel-title" id="undetain">!undetain</h3>
	</div>
	<div class="panel-body">
    <h6>Un-detains a user, removing the muted role from them.<br/><br/><code>!undetain &lt;user ID&gt;</code> usable by: <strong>Moderators</strong></h6>
	</div>
</div>
<div class="panel panel-primary">
	<div class="panel-heading">
		<h3 class="panel-title" id="reply">!reply</h3>
	</div>
	<div class="panel-body">
    <h6>Reply to users who have responded to a moderation action via a DM relay.<br/><br/><code>!reply &lt;user ID&gt; &lt;message&gt;</code> usable by: <strong>Moderators</strong></h6>
	</div>
</div>
<div class="panel panel-primary">
	<div class="panel-heading">
		<h3 class="panel-title" id="purgesince">!purgesince</h3>
	</div>
	<div class="panel-body">
    <h6>Deletes all messages in a channel that were sent after the linked message, including the linked message (max 100).<br/><br/><code>!purgesince &lt;message link&gt;</code> usable by: <strong>Moderators</strong></h6>
	</div>
</div>
<div class="panel panel-primary">
	<div class="panel-heading">
		<h3 class="panel-title" id="lockdown">!lockdown</h3>
	</div>
	<div class="panel-body">
    <h6>Locks down public channels, for use during a raid situation. The bot will deny permission for roles below the lowest moderator role to send messages or connect to voice in any channels they can view (excluding Administrator and bot integration roles). Specify <code>start</code> or <code>end</code> after the command to start or stop the lockdown.<br/><br/><code>!lockdown &lt;start/end&gt;</code> usable by: <strong>Moderators</strong></h6>
	</div>
</div>
