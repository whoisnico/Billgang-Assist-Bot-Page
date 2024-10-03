# Commands & Features

## Basic Conmmands

### /serverinfo

> usage: `/serverinfo` 

Get following Information from the guild:
```
  Server Name
  Server ID
  Owner
  Creation Date
  Verification Level (High/Medium/Low)
  Member Count
  Server Features
  ```

### /userinfo

> usage: `/serverinfo (Member[Optional])` 

If Member = None is Member = Author  
Get following Information from the Member:
```
Username
Displayname
Status
Online
User ID
Account Created Date
Joined Server Date
Activity (Playing:Name/Streaming:Name[URL]/Listening:Song[Artist][Album])
Profile Badges (staff/partner/hypesquad/bug_hunter/hypesquad_bravery/hypesquad_brilliance/hypesquad_balance/early_supporter/system/bug_hunter_level_2/verified_bot/verified_bot_developer/early_verified_bot_developer/moderator_programs_alumni/discord_certified_moderator/http_interactions_bot/spammer/active_developer/bot)
  ```

### /botinfo

> usage: `botinfo` 

Get following Information from the Bot:
```
UpTime (Days, Hours, Minutes)
Displayname
User ID
Status (Online/Dnb/Idle/Offline)
Ping
Servers
Last Update
Importants Links
  ```
## Billgang Intergration

### /setup

> usage: `/setup (logchannel)` 

Set up the bot for your server

### /delete

> usage: `/delete` 

Delete all your Bot Data from our Database

### /set_customerrole

> usage: `/set_customerrole (role)` 

Set up the customer role feature for your server


### /claim

> usage: `/claim (order_id)` 

Let the use claim the customer role

### /order

> usage: `/order (order_id)` 

Get information about a order id


### /send_faqs

> usage: `/send_faqs (title) (channel)` 

Send your sellpass faq to a channel
