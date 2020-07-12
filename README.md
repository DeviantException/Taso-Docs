# Taso-Docs
Documentation for Taso bot

Table of Contents:

    * [Commands](/commands/cmds.md)
        * [Administrative Commands](/commands/administrative_cmds.md)
        * [User Commands](/commands/user_cmds.md)
                * [Server Currency Commands](/commands/user/server_currency_earning_cmds.md)
                * [Server Shop Commands](/commands/user/server_shop_cmds.md)
                * [Currency Gaming Commands](/commands/user/currency_gaming_cmds.md)
                * [Leveling Commands](/commands/user/leveling_cmds.md)
        * [Bot Maintainer Commands](/commands/bot_maintainer_cmds.md)

### How to Read This Documentation
All commands referenced in this documentation will use the default prefix of `-`.

All required arguments in a command will be enclosed in `<angle brackets like this>`.

Any optional arguments for a command will be enclosed in `[square brackets like this]`.

When you see a vertical pipe like this `|` means you can use anything on either side of it as an argument in the command.

**Example:**

The command to clean messages will be documented like this: `-clean <number>|<user> <number>`. The vertical pipe means you can run the command in any of the following ways:
  * `-clean 20` (cleans 20 messages from the channel)
  * `-clean @user1234 15` (cleans 15 messages from the designated user in the channel)
  * `-clean 000000000000000000 15` (cleans 15 messages from the designated user in the channel)

When you see `<user>` in a command structure you can use either the user ID or mention. If you see `<user>...` in a command structure you can pass multiple users into that command.

**Example:**

The command to warn a user will be documented like this: `-warn <user>... [reason]`. This means you can run the command in any of the following ways:
  * `-warn @user#1234`
  * `-warn 000000000000000000`
  * `-warn @user#1234 sent bot commands in wrong channel`
  * `-warn 000000000000000000 sent bot commands in wrong channel`
  * `-warn @user#1234 @user#5678 sent bot commands in wrong channel`
  * `-warn 000000000000000000 000000000000000000 sent bot commands in wrong channel`
