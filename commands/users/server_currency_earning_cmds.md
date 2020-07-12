# Server Currency Commands

#### Pick

This allows the user to pick up the currency in the channel. (Note: This command requires that the code in the image of the currency drop is placed after it, or the user will not pick up the currency)


#### Balance

This command will show the user their current balance of server currency, if any.


#### Timely

This command allows the user to earn a small amount of currency once every 24 hours.


#### Leaderboard

Shows the current top currency holders of the server.


#### Give

Gives a specified user a certain amount of currency. You can specify the reason after the mention or user ID.


## Command Structures

| Command     | Alias                 | Structure                              | Example                                                |
| ----------- | --------------------- | -------------------------------------- | ------------------------------------------------------ |
| Pick        | N/A                   | `.pick <code>`                         | `.pick a53d`                                           |
| Balance     | `.bal` `.$` or `.cur` | `.balance`                             | `.balance`                                             |
| Timely      | N/A                   | `.timely`                              | `.timely`                                              |
| Leaderboard | `.lb`                 | `.leaderboard`                         | `.leaderboard` or `.lb`                                |
| Give        | N/A                   | `.give <amount> <user_ID>\|<@mention>` | `.give 150 323541255403470858 Because I felt like it.` |