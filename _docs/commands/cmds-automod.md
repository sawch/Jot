---
title: Auto-Moderation Commands
permalink: /docs/cmds-automod/
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
		<h3 class="panel-title" id="automodinfo">!automodinfo</h3>
	</div>
	<div class="panel-body">
    <h6>Display the current auto-moderation settings.<br/><br/><code>!automodinfo</code> usable by: <strong>Moderators</strong></h6>
	</div>
</div>
<div class="panel panel-primary">
	<div class="panel-heading">
		<h3 class="panel-title" id="automod-setall">!automod setall</h3>
	</div>
	<div class="panel-body">
    <h6>Enables or disables all auto-moderation filters without altering their settings. Options are <code>enabled</code> or <code>disabled</code>.<br/>Specify <code>help</code> to see the available options.<br/><br/><code>!automod setall &lt;enabled/disabled&gt;</code> usable by: <strong>Administrators</strong></h6>
	</div>
</div>
<div class="panel panel-primary">
	<div class="panel-heading">
		<h3 class="panel-title" id="automod-offensivewords">!automod offensivewords</h3>
	</div>
	<div class="panel-body">
    <h6>When enabled, messages containing common offensive words/racial slurs will be deleted and the author will be punished, once patience is exceeded.<br/>Specify <code>help</code> to see the available options.<br/><br/><code>!automod offensivewords &lt;options&gt;</code> usable by: <strong>Administrators</strong></h6>
	</div>
</div>
<div class="panel panel-primary">
	<div class="panel-heading">
		<h3 class="panel-title" id="automod-invitelinks">!automod invitelinks</h3>
	</div>
	<div class="panel-body">
    <h6>When enabled, messages containing invite links to Discord servers will be deleted and the author will be punished, once patience is exceeded.<br/>Specify <code>help</code> to see the available options.<br/><br/><code>!automod invitelinks &lt;options&gt;</code> usable by: <strong>Administrators</strong></h6>
	</div>
</div>
<div class="panel panel-primary">
	<div class="panel-heading">
		<h3 class="panel-title" id="automod-messagespam">!automod messagespam</h3>
	</div>
	<div class="panel-body">
    <h6>When enabled, message spam exceeding the configured threshold and time window will punish the user for spamming, once patience is exceeded.<br/>Specify <code>help</code> to see the available options.<br/><br/><code>!automod messagespam &lt;options&gt;</code> usable by: <strong>Administrators</strong></h6>
	</div>
</div>
<div class="panel panel-primary">
	<div class="panel-heading">
		<h3 class="panel-title" id="automod-capspam">!automod capspam</h3>
	</div>
	<div class="panel-body">
    <h6>When enabled, reasonably large messages containing mostly capital letters will punish the user for spamming, once patience is exceeded.<br/>Specify <code>help</code> to see the available options.<br/><br/><code>!automod capspam &lt;options&gt;</code> usable by: <strong>Administrators</strong></h6>
	</div>
</div>
<div class="panel panel-primary">
	<div class="panel-heading">
		<h3 class="panel-title" id="automod-duplicatespam">!automod duplicatespam</h3>
	</div>
	<div class="panel-body">
    <h6>When enabled, messages containing large amounts of blank lines or duplicate words/letters such as "hi hi hi hi hi hi hi hi" or "aaaaaaaaaaa" will punish the user for spamming, once patience is exceeded.<br/>Specify <code>help</code> to see the available options.<br/><br/><code>!automod duplicatespam &lt;options&gt;</code> usable by: <strong>Administrators</strong></h6>
	</div>
</div>
<div class="panel panel-primary">
	<div class="panel-heading">
		<h3 class="panel-title" id="automod-emojispam">!automod emojispam</h3>
	</div>
	<div class="panel-body">
    <h6>When enabled, messages containing many emojis will be deleted and punish the user for spamming, once patience is exceeded.<br/>Specify <code>help</code> to see the available options.<br/><br/><code>!automod emojispam &lt;options&gt;</code> usable by: <strong>Administrators</strong></h6>
	</div>
</div>
<div class="panel panel-primary">
	<div class="panel-heading">
		<h3 class="panel-title" id="automod-massmentions">!automod massmentions</h3>
	</div>
	<div class="panel-body">
    <h6>When enabled, users who mass-ping many users or roles in a single message will be punished, once patience is exceeded.<br/>Specify <code>help</code> to see the available options.<br/><br/><code>!automod massmentions &lt;options&gt;</code> usable by: <strong>Administrators</strong></h6>
	</div>
</div>
