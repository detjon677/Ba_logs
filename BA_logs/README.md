  // THIS IS MADE BY DEJON
### Requirements
- A Discord Server
- FiveM FXServer

# Download & Installation

1. Download the files
2. Put the Ba_logs folder in the server resource directory
3. Add this to your `server.cfg`
```
ensure BA_logs
```

# Adding more logs

- Add the following code to your existing resource where you execude the code
```
exports.JD_logs:discord('MESSAGE_YOU_WANT_TO_POST_IN_THE_EMBED', PLAYER_ID, PLAYER_2_ID, 'DECIMAL_COLOR_CODE', 'WEBHOOK_CHANNEL')
```
- Create a discord channel with webhook and add this to the webhooks.
```
local webhooks = {
	all = "<DISCORD_WEBHOOK>",
	chat = "<DISCORD_WEBHOOK>",
	joins = "<DISCORD_WEBHOOK>",
	leaving = "<DISCORD_WEBHOOK>",
	deaths = "<DISCORD_WEBHOOK>",
	shooting = "<DISCORD_WEBHOOK>",
	resources = "<DISCORD_WEBHOOK>",
	<WEBHOOK_CHANNEL> = "<DISCORD_WEBHOOK>", <------
}
```

### My Discord: https://discord.gg/badass

