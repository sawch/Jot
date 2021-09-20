---
title: Configuration Commands
permalink: /docs/cmds-config/
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
		<h3 class="panel-title" id="setup">!setup</h3>
	</div>
	<div class="panel-body">
    <h6>Runs a setup process where the bot will guide you through configuration. You can run this again at any point to change any settings.<br/><br/><code>!setup</code> usable by: <strong>Administrators</strong></h6>
	</div>
</div>
<div class="panel panel-primary">
	<div class="panel-heading">
		<h3 class="panel-title" id="automod">!automod</h3>
	</div>
	<div class="panel-body">
    <h6>Displays and configures auto-moderation settings.<br/><br/><code>!automod</code> usable by: <strong>Administrators</strong></h6>
	</div>
</div>
<div class="panel panel-primary">
	<div class="panel-heading">
		<h3 class="panel-title" id="prefix">!upgrade</h3>
	</div>
	<div class="panel-body">
    <h6>Manages upgrade tokens, used to unlock special features.<br/><br/><code>!upgrade</code> usable by: <strong>Moderators</strong></h6>
	</div>
</div>
<div class="panel panel-primary">
	<div class="panel-heading">
		<h3 class="panel-title" id="prefix">!buttonroles</h3>
	</div>
	<div class="panel-body">
    <h6>Create, modify and delete button roles. Button roles use buttons attached to messages that grant roles to users when they click on them, like reaction roles.<br/><br/><code>!buttonroles</code> usable by: <strong>Administrators</strong></h6>
	</div>
</div>
<div class="panel panel-primary">
	<div class="panel-heading">
		<h3 class="panel-title" id="prefix">!serverlink</h3>
	</div>
	<div class="panel-body">
    <h6>Manages linking servers together to share moderation logs and issue mutes, kicks and bans across multiple servers.<br/><br/><code>!serverlink</code> usable by: <strong>ServerOwner</strong></h6>
	</div>
</div>
