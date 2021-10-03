---
title: Utility Commands
permalink: /docs/cmds-util/
description: A list of the utility commands found in the Jot.
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
		<h3 class="panel-title" id="slowmode">!slowmode</h3>
	</div>
	<div class="panel-body">
    <h6>Sets the slowmode value on the specified channel (maximum 6 hours). Specify <code>off</code> or <code>0s</code> as the duration to disable slowmode. Duration format examples: <code>5s</code>, <code>10m</code>, <code>2h</code>.<br/><br/><code>!slowmode &lt;channel&gt; &lt;duration&gt;</code> usable by: <strong>Moderators</strong></h6>
	</div>
</div>
<div class="panel panel-primary">
	<div class="panel-heading">
		<h3 class="panel-title" id="gettime">!gettime</h3>
	</div>
	<div class="panel-body">
    <h6>Generate timestamps that you can copy and paste to show dates and times that are displayed in the local time of whoever sees it, such as <code>in 5 minutes</code> or <code>in a year</code>. Duration is optional and can be preceded by a <code>-</code> to get a time in the past. Duration format examples: <code>1h30m</code>, <code>-1d</code>, <code>3d</code>, <code>1w</code>.<br/><br/><code>!gettime &lt;duration&gt;</code> usable by: <strong>Moderators</strong></h6>
	</div>
</div>
<div class="panel panel-primary">
	<div class="panel-heading">
		<h3 class="panel-title" id="ping">!ping</h3>
	</div>
	<div class="panel-body">
    <h6>Check if the bot is alive.<br/><br/><code>!ping</code> usable by: <strong>Moderators</strong></h6>
	</div>
</div>
<div class="panel panel-primary">
	<div class="panel-heading">
		<h3 class="panel-title" id="help">!help</h3>
	</div>
	<div class="panel-body">
    <h6>Lists the commands available to you. The following categories are available:<br/><br/>
        <code>config</code><br/>
        <code>mod</code><br/>
        <code>info</code><br/>
        <code>util</code><br/>
        <br/><br/><code>!help &lt;category&gt;</code> usable by: <strong>Moderators</strong></h6>
	</div>
	<div class="panel-footer"><h6>The help command contains all the information regarding commands that you're reading here!</h6></div>
</div>
