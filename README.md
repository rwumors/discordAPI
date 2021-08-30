# discord api methods

----------------------------------------------------------------------------------

url : https://discord.com/api/v8/guilds/server-id/bans/ 

method : Get

info : returns all bans in json format including username, id, tag, and flags

----------------------------------------------------------------------------------

url : https://discord.com/api/v8/guilds/server-id/bans/user-id

method : Delete

info : unbans the user based on the user ID

----------------------------------------------------------------------------------

url : https://discord.com/api/v8/channels/channel-id/messages

method : Get

info : returns messages in json format includes id, type, content, attachements, embeds, mentions, pinned (bool), tts (bool), and timestamp

----------------------------------------------------------------------------------

url : https://discord.com/api/v8/channels/channel-id/messages

method : Post

info : sends a message/embed if json data is {"content":"hi"}

----------------------------------------------------------------------------------

url : https://discord.com/api/v8/auth/login

method : Post

info : correct logins respond with authorization token

----------------------------------------------------------------------------------

url : https://discord.com/api/v8/experiments

method : Get

info : returns website fingerprint most info is currently unknown

----------------------------------------------------------------------------------

url : https://discord.com/api/v8/auth/register

method : Post

info : used to register a user with json data {"username":"username here"}

----------------------------------------------------------------------------------

url : https://discord.com/api/v8/users/@me/billing/trials/user-id/eligibility

method : Get

info : returns the eligibility of billing

----------------------------------------------------------------------------------

url : https://discord.com/api/v8/users/@me/affinities/guilds

method : Get

info : returns all servers in json includes server ids and affinity

----------------------------------------------------------------------------------

url : https://status.discord.com/api/v2/scheduled-maintenances/upcoming.json

method : Get

info : returns current timezone of user and page id

----------------------------------------------------------------------------------

url : https://discord.com/api/v8/applications/detectable
method : Get
info : returns in json format the current buyable games/applications

----------------------------------------------------------------------------------

url : https://discord.com/api/v8/users/@me/affinities/users

method : Get

info : returns all friends user IDs

----------------------------------------------------------------------------------

url : https://discord.com/api/v8/applications/public?application_ids=APP ID

method : Get

info : returns friends current public game status if any

----------------------------------------------------------------------------------

url : https://discord.com/api/v8/users/@me/relationships

method : Get

info : returns all friends in list includes user id, usernames, avatar hashes, tag, and public flags

----------------------------------------------------------------------------------

url : https://discord.com/api/v8/invites/inviteLink?with_counts=true

Method : Get

info : returns invite code, server ID, server name, banner/splash hashes, icon hash, features, verification level, vanity url, and welcome screen if any

----------------------------------------------------------------------------------

url : https://discord.com/api/v8/channels/channel-id/follower-stats

method : Get

info : returns the current number of members that have seen the message, webhook source, and server ID

----------------------------------------------------------------------------------

url : https://discord.com/api/v8/discoverable-guilds

method : Get

info : responds with the current public servers including server name, id, banner hash, and invite

----------------------------------------------------------------------------------

url : https://discord.com/api/v8/discovery/valid-term?term=TERM TO SEARCH

method : get

info : validates if search term is valid

----------------------------------------------------------------------------------

url : https://discord.com/api/download?platform=PLATFORM

method : Get

info : downloads the current version of the program

----------------------------------------------------------------------------------

url : https://discord.com/api/v8/guilds

method : Post

info : Creates a server when json data includes {"name":"SERVER NAME"}

----------------------------------------------------------------------------------

url : https://discord.com/api/v8/guilds/server-id/premium/subscriptions

method : Get

info : returns the current server boosters to a server includes server id 

----------------------------------------------------------------------------------

url : https://discord.com/api/v8/guilds/server-id/regions

method : Patch

info : changes the server region 

----------------------------------------------------------------------------------

url : https://discord.com/api/v8/guilds/server-id

method : Patch

info : send a post request including {"splash":"data:image//imagetype;BASE64 ENCODING OF IMAGE"} changes the background of server invite

----------------------------------------------------------------------------------

url : https://discord.com/api/v8/guilds/server-id/emojis

method : Get

info : returns server emojis including ids, names, and time of added

----------------------------------------------------------------------------------

url : https://discord.com/api/v8/channels/channel-id/webhooks

method : Post

info : creates a webhook

----------------------------------------------------------------------------------

url : https://discord.com/api/v8/guilds/server-id/invites

method : Get

info : returns invite codes

----------------------------------------------------------------------------------

url : https://discord.com/api/v8/guilds/server-id/integrations/ID

method : Delete

info : deletes a integration

----------------------------------------------------------------------------------

url : https://discordapp.com/__development/source_maps

method : Get

info : Returns the source map with in discord

----------------------------------------------------------------------------------

url : https://discordapp.com/__development/create_build_override_link

method : Patch

info : creates a build overide link 

----------------------------------------------------------------------------------

url : https://discordapp.com/api/v8/sticker-packs

method : Get

info : development will respond 403 without permision

----------------------------------------------------------------------------------

url : https://discordapp.com/api/v8/users/@me/sticker-packs

method : Get

info : trys to return a sticker pack not yet made 403 responce

----------------------------------------------------------------------------------

url : http://127.0.0.1:3435/rpc?log

method : Get

info : discord opens a port on your pc for rpc and its gay responds with a authorization token if logged into client or webapp

----------------------------------------------------------------------------------
