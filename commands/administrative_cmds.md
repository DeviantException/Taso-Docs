# Administrative Commands

#### Take

Removes the specified amount of currency from a specified user.


#### Award

Can be used to award a specified user or set of users the specified amount of server currency. You can also specify the reason for awarding the server currency after the user. If a role is specified, the bot will award the specified amount of server currency to all users within that role.


#### Shop Add

Adds an item to the shop by specifying the type, price, and name. Currently, the only available type is a role.


#### Shop Remove

Removes an item from the shop by its ID. If the `.shop` command is run it should display the list of things in that shop with a number next to it. That number is the ID.


## Command Structures

| Command     | Alias     | Structure                                    | Example                                                                              |
| ----------- | --------- | -------------------------------------------- | ------------------------------------------------------------------------------------ |
| Take        | N/A       | `.take <amount> <user_ID\|@mention>`         | `.take 50 323541255403470858` or `.take 50 @Cerberus#0005`                           |
| Award       | N/A       | `.award <amount> <user_ID\|@mention>`        | `.award 50 323541255403470858` or `.award 50 @Cerberus#0005`                         |
| Shop Add    | N/A       | `.shopadd <type> <cost> <role tag\|role_ID>` | `.shopadd role 500 731094524473901136` or `.shopadd role 500 <@&731094524473901136>` |
| Shop Remove | `.shoprm` | `.shoprem <ID>` or `.shoprm <ID>`            | `.shopremove 1` or `.shoprm 3`                                                       |