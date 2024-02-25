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
## Sellpass Intergration

### /setup

> usage: `/setup (token) (logchannel)` 

Set up the bot for your server

### /delete

> usage: `/delete` 

Delete all your Bot Data from our Database

### /set_customerrole

> usage: `/set_customerrole (role)` 

Set up the customer role feature for your server

### /shopinfo

> usage: `/shopinfo` 

See your shop information

### /claim

> usage: `/claim (order_id)` 

Let the use claim the customer role

### /order

> usage: `/order (order_id)` 

Get information about a order id

### /password

> usage: `/password (password / Null)` 

Set or delete a shop password

### /maintenance

> usage: `/maintenance (True/False)` 

Put your store into maintenance

### /coupons

> usage: `/coupons` 

See all your coupons code

### /create_coupon

> usage: `/create_coupon (name) (discount)` 

Create a coupon code
- Type the discount without % at the end only the number

### /delete_coupon

> usage: `/delete_coupon (coupon_id)` 

Delete a coupon code
- You can see the coupon id with the /coupons command

### /send_faqs

> usage: `/send_faqs (title) (channel)` 

Send your sellpass faq to a channel

### /check_faqs

> usage: `/check_faqs` 

Check your FAQs

### /create_faq

> usage: `/check_faq (question) (answer)` 

Create a FAQ

### /delete_faq

> usage: `/delete_faq (faq_id)` 

Delete a FAQ
- You can see the faq_id with the /check_faqs command