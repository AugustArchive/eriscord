# eriscord

> This repository is a tutorial of how to implement Eris into your discord bot!

# Why Eris?

> discord.js v11 is bloated, let's get out of the way... Eris is bit more lightweight and the main purpose of the library is to use Discord's shard implementation when a Discord bot is over 2,500 guilds while discord.js uses the [`ShardingManager`](https://github.com/discordjs/discord.js/tree/stable/src/sharding/ShardingManager.js) while discord.js v12 tries to be unbloated like v11 but still isn't worth it. Most discord.js bots weight about ~200MB with a couple hundred guilds and 1.5GB with 2 shards compacted with the bot. Eris uses like ~30MB owith a couple hundred guilds and ~500MB with 2 shards compact; it's based on Memory Usage and not how the bot performs successfully.

## Tutorial

### Getting Started

- [Creating your bot](https://github.com/auguwu/eriscord/tree/master/tutorial/getting-started/creating-your-bot.md)
- [Creating basic commands](https://github.com/auguwu/eriscord/tree/master/tutorial/getting-started/creating-basic-commands.md)
- [Using events](https://github.com/auguwu/eriscord/tree/master/tutorial/getting-started/using-events.md)

### Beginner

- [Creating commands in folders and seperate files](https://github.com/auguwu/eriscord/tree/master/tutorial/beginner/creating-commands-in-seperate-files.md)

### Advanced

- [Creating a command handler](https://github.com/auguwu/eriscord/tree/master/tutorial/advanced/creating-command-handler.md)
