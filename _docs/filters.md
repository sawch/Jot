---
title: Auto-Moderation Filters
permalink: /docs/filters/
---
<div class="panel panel-info">
	<div class="panel-heading">
		<h3 class="panel-title" id="warn">Quick Note!</h3>
	</div>
	<div class="panel-body">
    <h6>The auto-mod filters are crafted by the developer and do not allow inputting custom regular expressions or inputs, at least at this time. However every filter <em>is</em> configurable. You can configure the following properties:</h6>
    <ul>
        <li><h6>Punishments (nothing, mute, kick or ban)</h6></li>
        <li><h6>Patience (amount of verbal warnings before punishment, if any)</h6></li>
        <li><h6>Time windows (for time-based filters: how many seconds between messages, etc.)</h6></li>
        <li><h6>Thresholds (how many emojis, duplicate letters, etc. are considered spam)</h6></li>
    </ul>
	</div>
</div>
<div class="panel panel-primary">
	<div class="panel-heading">
		<h3 class="panel-title" id="warn">Offensive Words</h3>
	</div>
	<div class="panel-body">
    <h6>This filter matches some very common offensive/derogatory words and racial slurs. It's fairly robust in the sense that it will match letter and emoji replacements like &#x1f1f3;, arbitrary spaces or repeated letters.
    <br/><br/>Word filters can always be defeated with little to no effort but this will catch the majority of common uses, if someone tries to defeat the filter in your chat they typically won't last long anyways.
    <br/><br/><span class="label label-danger">Messages deleted when caught</span>
    </h6>
	</div>
</div>
<div class="panel panel-primary">
	<div class="panel-heading">
		<h3 class="panel-title" id="warn">Invite Links</h3>
	</div>
	<div class="panel-body">
    <h6>This filter matches any Discord server invite links, like <a href="https://discord.gg/U3Wfuw7CwS" target="_blank">https://discord.gg/U3Wfuw7CwS</a>. (That's the Discord server for the bot!)
    <br/><br/><span class="label label-danger">Messages deleted when caught</span>
    </h6>
	</div>
</div>
<div class="panel panel-primary">
	<div class="panel-heading">
		<h3 class="panel-title" id="warn">Malicious Links</h3>
	</div>
	<div class="panel-body">
    <h6>This filter matches an internally maintained list of links that are encountered by the developer and moderators in the development server by random, usually malicious users. It's not exhaustive, but any new links encountered are added to the bot pretty fast.
    <br/><br/>It includes links like IP grabbers, redirects into <em><strong>fullscreen are you sure you want to leave this page max volume jump scare</strong></em> and misleading links like:
    <br/><br/>
    <ul>
      <li><code>claim.discordofficial.com</code> (That is <em>not</em> official!)</li>
      <li><code>steanncommunity.ru/</code> (We've encountered a ton of these)</li>
    </ul>
    If your server encounters a spam link you think should be caught, come report it in the <a href="https://discord.gg/U3Wfuw7CwS" target="_blank">Jot Discord server</a>! You should also <a href="https://support.discord.com/hc/en-us/requests/new" target="_blank">report spammers to Discord</a>.
    <br/><br/><span class="label label-danger">Messages deleted when caught</span>
    </h6>
	</div>
</div>
<div class="panel panel-primary">
	<div class="panel-heading">
		<h3 class="panel-title" id="warn">Mass Mentions</h3>
	</div>
	<div class="panel-body">
    <h6>This filter matches messages that mass-ping people like <a class="btn btn-primary btn-xs">@everyone</a> <a class="btn btn-success btn-xs">@Moderators</a> <a class="btn btn-danger btn-xs">@Artists</a> <a class="btn btn-info btn-xs">@Helpers</a>
    <br/><br/><span class="label label-danger">Messages deleted when caught</span>
    </h6>
	</div>
</div>
<div class="panel panel-primary">
	<div class="panel-heading">
		<h3 class="panel-title" id="warn">Emoji Spam</h3>
	</div>
	<div class="panel-body">
    <h6>This filter matches messages that use an excessive amount of emotes/emojis like <img style="display:inline" src="/jot/assets/img/partycat3.gif" alt="Emote"><img style="display:inline" src="/jot/assets/img/partycat3.gif" alt="Emote"><img style="display:inline" src="/jot/assets/img/partycat3.gif" alt="Emote"><img style="display:inline" src="/jot/assets/img/partycat3.gif" alt="Emote"><img style="display:inline" src="/jot/assets/img/partycat3.gif" alt="Emote"><img style="display:inline" src="/jot/assets/img/partycat3.gif" alt="Emote">
    <br/><br/><span class="label label-danger">Messages deleted when caught</span>
    </h6>
	</div>
</div>
<div class="panel panel-primary">
	<div class="panel-heading">
		<h3 class="panel-title" id="warn">Duplicate Spam</h3>
	</div>
	<div class="panel-body">
    <h6>This filter matches messages that repeat letters or phrases like "omg omg omg omg omg omg omg omg omg omg", "aaaaaaaaaaaaaaaaaaaaaaaaa", or repeated empty lines.
    <br/><br/><span class="label label-primary">Messages only deleted when repeating empty lines</span>
    </h6>
	</div>
</div>
<div class="panel panel-primary">
	<div class="panel-heading">
		<h3 class="panel-title" id="warn">Message Spam</h3>
	</div>
	<div class="panel-body">
    <h6>This filter matches messages that are sent in quick succession, like 10 messages with less than 2 seconds between each message.</h6>
	</div>
</div>
<div class="panel panel-primary">
	<div class="panel-heading">
		<h3 class="panel-title" id="warn">Capital Letter Spam</h3>
	</div>
	<div class="panel-body">
    <h6>This filter matches messages that are at least a reasonable size and consist of roughly >70% capital letters.</h6>
	</div>
</div>
