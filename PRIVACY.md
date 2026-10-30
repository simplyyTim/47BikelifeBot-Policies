# 47Bikelife Discord Bot — Privacy Policy

Last updated: October 30, 2026

This policy describes data handled by the 47Bikelife Discord Bot in the
47Bikelife Discord community.

## Operator and contact

The bot is operated by the 47Bikelife community team. For privacy questions or
requests, contact the team through the
[official Discord server](https://discord.gg/47Bikelife).

## Data the bot handles

- **Discord interactions:** Discord user, server, and channel identifiers and
  message text needed to process bot commands and interactions. The bot uses
  Discord's message-content access and reads recent channel messages when
  maintaining its rules, vote, honeypot, changelog, and leaderboard messages.
- **Server verification:** The bot assigns the configured verification role
  after a user accepts the server rules. Successful verification events include
  the Discord username in the bot's operational output.
- **AI and translation requests:** The text submitted to `!ai`, `!translate`,
  or `!translateto` is sent to Groq or MyMemory, respectively, to provide the
  requested response. Using these commands as a reply can also send the
  referenced message's text, including text written by another person. The
  translation command may send an initial text excerpt for language detection
  and then the full text for translation. Avoid including sensitive or
  confidential information, and do not submit another person's private text
  without authorization.
- **Map votes:** The bot temporarily uses a Discord user ID to prevent duplicate
  votes and update a vote. Vote IDs are cleared when the vote ends; the bot
  does not save them in its persistent leaderboard cache.
- **Moderation events:** If a non-administrator posts in the configured
  honeypot channel, the bot processes the account ID, display name, message
  text, and event time. It may delete messages through the configured
  ban/unban action and posts an event notice to the configured warning channel.
- **MX Bikes leaderboard:** The bot reads rider names and lap times from the
  game server's result files. It caches leaderboard data on its host and posts
  leaderboard results in the configured Discord channel. Its cache also tracks
  processed result filenames. A separate local file stores server IDs and the
  IDs of leaderboard messages so the bot can update its existing messages.
- **Operational data:** The bot and its hosting provider may create technical
  logs needed to operate and troubleshoot the service.

## Storage and sharing

The bot stores leaderboard cache data locally on its host. It does not keep
map-vote user IDs in that persistent cache. Discord messages, moderation
records, and requests handled by third-party providers are subject to those
providers' own storage and retention practices.

Data is shared only as needed to operate the bot:

- Discord receives the bot's messages and interactions as part of the Discord
  service.
- Groq receives text submitted to the AI command.
- MyMemory receives text submitted to translation commands.
- The bot host and MX Bikes server host process technical data needed to run
  the bot and retrieve game results.

The bot does not set tracking cookies or operate a separate user account
system.

## Retention and requests

Vote IDs are held only while a vote is active. Leaderboard cache and operational
logs may remain on their respective hosts according to the bot's operation and
the host's retention settings; this bot does not define a fixed deletion
schedule for them.

Removing the bot from a Discord server does not automatically delete existing
Discord posts, game-server result files, or the host's leaderboard cache.

You may contact the community team through the
[official Discord server](https://discord.gg/47Bikelife) with questions or
privacy requests. Where applicable, you may also have rights under data
protection law, including the right to complain to your local supervisory
authority.

## Changes

This policy may be updated when the bot's features or data handling change.
The date at the top identifies the latest revision.

