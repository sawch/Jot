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
	<div class="panel-footer"><h6>The setup command replaces all the following commands! You can use this instead of them.</h6></div>
</div>
<div class="panel panel-primary">
	<div class="panel-heading">
		<h3 class="panel-title" id="prefix">!prefix</h3>
	</div>
	<div class="panel-body">
    <h6>Set the prefix for commands. The default is <code>!</code>, it can be a maximum 10 characters long and the accepted characters are: <code>A-Z</code>, <code>0-9</code>, <code>.</code>, <code>,</code>, <code>!</code>, <code>?</code>, <code>$</code>, <code>+</code>, <code>%</code>, <code>^</code>, <code>&amp;</code>.<br/><br/><code>!prefix &lt;text&gt;</code> usable by: <strong>Administrators</strong></h6>
	</div>
</div>
<div class="panel panel-primary">
	<div class="panel-heading">
		<h3 class="panel-title" id="modroles">!modroles</h3>
	</div>
	<div class="panel-body">
    <h6>Modify the roles that the bot considers as moderators. Users with those roles can use moderation commands. Actions are: <code>add</code>, <code>remove</code> & <code>list</code>.<br/><br/><code>!modroles &lt;action&gt; &lt;role ID&gt;</code> usable by: <strong>Administrators</strong></h6>
	</div>
</div>
<div class="panel panel-primary">
	<div class="panel-heading">
		<h3 class="panel-title" id="mutedrole">!mutedrole</h3>
	</div>
	<div class="panel-body">
    <h6>Set the role that users will be given with the mute &amp; detain commands.<br/><br/><code>!mutedrole &lt;role ID&gt;</code> usable by: <strong>Administrators</strong></h6>
	</div>
</div>
<div class="panel panel-primary">
	<div class="panel-heading">
		<h3 class="panel-title" id="logmodhere">!logmodhere</h3>
	</div>
	<div class="panel-body">
    <h6>Moderation messages (mute/ban expiry, previously banned users joining server, etc.) from the bot will be logged in the channel this command is used in.<br/>
        Specify <code>stop</code> after the command to disable the moderation log.<br/><br/><code>!logmodhere &lt;stop&gt;</code> usable by: <strong>Administrators</strong></h6>
	</div>
</div>
<div class="panel panel-primary">
	<div class="panel-heading">
		<h3 class="panel-title" id="logserverhere">!logserverhere</h3>
	</div>
	<div class="panel-body">
    <h6>Server events such as message edits, deletions, etc. will be logged in the channel this command is used in.<br/>
        Specify <code>stop</code> after the command to disable the server log.<br/><br/><code>!logserverhere &lt;stop&gt;</code> usable by: <strong>Administrators</strong></h6>
	</div>
</div>
<!--
<div class="panel panel-primary">
	<div class="panel-heading">
		<h3 class="panel-title" id="dbbackuphere">!dbbackuphere <a href="/jot/docs/upgrade/" class="btn btn-danger btn-xs">Requires upgrade token</a></h3>
	</div>
	<div class="panel-body">
    <h6>The bot will periodically upload backups of the database to the channel this command is used in.<br/>
        Specify <code>stop</code> after the command to disable database backups.<br/><br/><code>!dbbackuphere &lt;stop&gt;</code> usable by: <strong>Administrators</strong></h6>
        
	</div>
</div>
<div class="panel panel-primary">
	<div class="panel-heading">
		<h3 class="panel-title" id="dbrequestbackup">!dbrequestbackup <a href="/jot/docs/upgrade/" class="btn btn-danger btn-xs">Requires upgrade token</a></h3>
	</div>
	<div class="panel-body">
    <h6>Request a database backup to me made immediately.<br/><br/><code>!dbrequestbackup</code> usable by: <strong>Administrators</strong></h6>
	</div>
</div>
<div class="panel panel-primary">
	<div class="panel-heading">
		<h3 class="panel-title" id="dbrequestbackup">!dbrestorebackup <a href="/jot/docs/upgrade/" class="btn btn-danger btn-xs">Requires upgrade token</a></h3>
	</div>
	<div class="panel-body">
    <h6>Restore the bot's database to the given backup. The <code>message link</code> must be to a message with a database uploaded by this bot.<br/><br/><code>!dbrestorebackup &lt;message link&gt;</code> usable by: <strong>Administrators</strong></h6>
  </div>
</div>
-->
<div class="panel panel-primary">
	<div class="panel-heading">
		<h3 class="panel-title" id="dmrelayhere">!dmrelayhere</h3>
	</div>
	<div class="panel-body">
    <h6>When users are warned or muted, their DM replies will be temporarily relayed to the channel this command is used in.<br/>
        Specify <code>stop</code> after the command to disable DM relays.<br/><br/><code>!dmrelayhere &lt;stop&gt;</code> usable by: <strong>Administrators</strong></h6>
	</div>
</div>
<div class="panel panel-primary">
	<div class="panel-heading">
		<h3 class="panel-title" id="anonymousactions">!anonymousactions</h3>
	</div>
	<div class="panel-body">
    <h6>Set whether or not moderation actions issued to users will contain the name of the issuing moderator in the DM sent to the user. Options are <code>yes</code> (to hide/anonymize) or <code>no</code> (to show).<br/><br/><code>!anonymousactions &lt;yes/no&gt;</code> usable by: <strong>Administrators</strong></h6>
	</div>
</div>
<div class="panel panel-primary">
	<div class="panel-heading">
		<h3 class="panel-title" id="changelogpings">!changelogpings</h3>
	</div>
	<div class="panel-body">
    <h6>Set whether or not bot update changelogs should ping the moderators. Options are <code>yes</code> or <code>no</code>.<br/><br/><code>!changelogpings &lt;yes/no&gt;</code> usable by: <strong>Administrators</strong></h6>
	</div>
</div>
