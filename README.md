# 12 year old simulator (IRC Bot)
Simulates an annoying 12 year old kid on the internet.


## To-do list

* Have the bot construct cancerous messages/sentences, rather than already created.
* Have the bot simulate an angry 12 year old, with the ability to get angry.
* RAGEQUITS!
* Have the bot spam lenny faces periodically.
* Actually finishing the fucking bot.
* Code improvements and cleanup

## Configuration

botnick: The nick the bot will use on IRC.
server: The IRC server the bot will connect.
port: The IRC server port the bot will use when connecting.
main_channel: The main bot channel, the bot will join this.
channels: The channels the bot will join.
join_on_invite: Once enabled, the bot will join when someone automatically invites the bot to a channel.
ssl_enabled: When enabled, the bot will use SSL when connecting to the server. (Make sure the port is also an SSL port, too.)
sasl: The bot will use SASL authentication when enabled.
enforce_sasl: If enabled, the bot will quit if sasl fails.
nickserv_login: The bot will identify to NickServ once connected, unnecessary to use this if you're using SASL already.
account_username: What you enter here will be used to identify with SASL or NickServ.
account_password: What you enter here will be used to identify with SASL or NickServ.
server_password: The password that will be used to connect to the IRC server (if needed.)
main_channel_only_mode: If enabled, the bot will only join the main channel, listed in main_channel.
respond_by: If set to "nick," it will only respond when it has been highlighted. If set to "all", it will respond on every message sent in the channel(s).
