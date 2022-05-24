# Moderation

For moderation tools, click [here](../mod/tools)

## `cleanup`

Cleans up Dank Vibes Bot's messages and messages that contain Dank Vibes Bot's commands.

!!! tip "Usage"

    `cleanup <number_of_messages>`

    * `number_of_messages`: Number of messages to be cleaned up. If no number is specified, it will delete 100 instead.

**Aliases**: `cu`

## `freezenick`

Freezes a member's nickname to the specified nicknanme. 

!!! tip "Usage"

    `freezenick [member] [nickname]`

    * `member`: Member to freeze the nickname of.
    * `nickname`: Nickname to freeze the member's nickname to.

**Aliases** `fn`

## `unfreezenick`

Unfreezes a member's nickname.

!!! tip "Usage"

    `unfreezenick [member]`

    * `member`: Member to unfreeze the nickname of.

**Aliases**: `ufn`

## `ban`

Bans a member from the server.

!!! tip "Usage"

    `ban [member] <reason>`

    * `member`: Member to ban.
    * `reason`: Reason for the ban.

## `timeout`

Timeouts a member for a specified amount of time. (native Discord timeout)

!!! tip "Usage"

    `timeout [member] [time]`

    * `member`: Member to timeout.
    * `time`: Duration of timeout. It cannot be longer than 4 weeks, this is a Discord API limitation.

**Aliases**: `to`

## `untimeout`

Removes a member's timeout.

!!! tip "Usage"

    `untimeout [member]`

    * `member`: Member to untimeout.

**Aliases**: `uto`, `ut`

## `modlog`

Shows a user's mod log.

!!! tip "Usage"

    `modlog [member]`

    * `member`: Member to show the mod log of.

## `slowmode`

Sets a channel's slowmode.

!!! tip "Usage"

    `slowmode <channel> [duration]`

    * `channel`: Channel to set the slowmode of. If no channel is specified, the channel you used the command in will have its slowmode changed.
    * `duration`: Duration of slowmode, cannot be longer than 6 hours.
    
## `roleinfo`

Provides information about a role, including its position, number of members, color, and its role icon.

!!! tip "Usage"

    `roleinfo [role]`

    * `role`: Role to show information about.

## `names`

Shows a user's past usernames.

!!! warning

Past usernames are logged from 9 January 2022 onwards.

!!! tip "Usage"

    `names [member]`

    * `member`: The member whom you'd like to see their past usernames.

## `nicknames`

Shows a user's past nicknames.

!!! warning

Past nicknames are logged from 9 January onwards.

!!! tip "Usage"

    `nicknames [member]`

    * `member`: The member whom you'd like to see their past nicknames.