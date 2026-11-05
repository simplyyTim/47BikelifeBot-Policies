# 47Bikelife Discord Bot — Privacy Policy

Last updated: November 5, 2026

This policy describes data handled by the 47Bikelife Discord Bot in the
47Bikelife Discord community.

## Operator and contact

The bot is operated by the 47Bikelife community team. For privacy questions or
requests, contact the team through the
[official Discord server](https://discord.gg/47Bikelife).

## Data the bot handles

- **Discord interactions:** Discord user, server, and channel identifiers and
  message text needed to process bot commands and interactions. The bot uses
  slash-command options, explicit bot mentions and user-selected message
  actions. It does not request privileged Message Content, Members or Presence
  intents. It reads its own recent channel messages when maintaining its rules,
  vote, honeypot, changelog and leaderboard messages.
- **Server verification:** The bot assigns the configured verification role
  after a user accepts the server rules. Successful verification events include
  the Discord username in the bot's operational output.
- **AI and translation requests:** Text submitted to `/ai`, `/translate`,
  `/translateto`, their bot-mention equivalents, or the AI/translation message
  actions is sent to Groq to provide the requested response. Selecting a
  message can include text written by another person; the AI action also sends
  the question entered in its form. MyMemory is no longer used. Avoid including
  sensitive or confidential information, and do not submit another person's
  private text without authorization. Context-menu responses are private to
  the requesting user; slash/mention responses appear in the invoking channel.
- **Map votes:** The bot temporarily uses a Discord user ID to prevent duplicate
  votes and update a vote. Vote IDs are cleared when the vote ends; the bot
  does not save them in its persistent leaderboard cache.
- **Moderation events:** If a non-administrator posts in the configured
  honeypot channel, the bot processes the account ID, display name,
  channel/message identifiers, event time, and message text only when
  Discord supplies it. It may delete messages through the configured ban/unban
  action and posts an event notice to the configured warning channel. An
  authorized moderator may also explicitly select a message to record its
  text, author, moderator and source link in that channel.
- **MX Bikes leaderboard:** The bot reads rider names and lap times from the
  game server's result files. It caches leaderboard data on its host and posts
  leaderboard results in the configured Discord channel. Its cache also tracks
  processed result filenames. A separate local file stores server IDs and the
  IDs of leaderboard messages so the bot can update its existing messages.
- **Permission maintenance:** The bot reads server roles and channel permission
  overrides to restrict mass mentions by ordinary members. It may fetch an
  individual member to assess an existing permission exception. Changes are
  recorded in Discord's audit log; this does not require a full member list.
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
- Groq receives text explicitly submitted for AI answers and translation.
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

