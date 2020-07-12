# Bot Maintainer Commands

#### Add Role Perm

Adds a permission setting for `allow` or `deny` on the specified role. If the command is run with an `allow` then to remove it you should run the Remove Role Perm command with `allow` as well.


#### Remove Role Perm

Removes the previously set permission for an `allow` or `deny` on the specified role.


#### Add User Perm

Allows for finer granulation on commands. If the user has a role that allows them to use a command via "add role perm" you can specifically deny that user by adding a `deny` with this command.


#### Remove User Perm

Removes the `allow` or `deny` permission setting for a specified user.


#### List Perms

Shows a list of the currently set permissions within the server.


#### Add Drop Image

Adds the attached image to the collection of images to show with currency drops.


## Command Structure

| Command          | Alias  | Structure                                                     | Example                                                               |
| ---------------- | ------ | ------------------------------------------------------------- | --------------------------------------------------------------------- |
| Add Role Perm    | N/A    | `.addroleperm <role_ID\|@mention> <command> <allow\|deny>`    | `.addroleperm 339829428034994179 take allow`                          |
| Remove Role Perm | N/A    | `.removeroleperm <role_ID\|@mention> <command> <allow\|deny>` | `.removeroleperm 339829428034994179 take allow`                       |
| Add User Perm    | N/A    | `.adduserperm <user_ID\|@mention> <command> <allow\|deny>`    | `.adduserperm 323541255403470858 take deny`                           |
| Remove User Perm | N/A    | `.removeuserperm <user_ID\|@mention> <command> <allow\|deny>` | `.removeuserperm 323541255403470858 take deny`                        |
| List Perms       | N/A    | `.listperms`                                                  | `.listperms`                                                          |
| Add Drop Image   | `.adi` | `.adddropimage <image>`                                       | `.adddropimage` + image file uploaded OR `.adi` + image file uploaded |