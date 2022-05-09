# Dank Memer Utilities

Dank Vibes Bot provides [Dank Memer Reminders](#dankreminders) for you to be regularly reminded to perform tasks/run certain Dank Memer commands. This includes Drop reminders and Daily reminders.

In addition, when you run `pls stream` and choose to begin to stream, Dank Vibes Bot will inform you of the current trending game (provided it has been set by a mod).

## `dankreminders`

Shows your reminders for Dank Memer and allows you to enable/disable them through buttons.
Change your type of reminder via the select menu.

!!! tip "Usage"

    `dankreminders`

**Aliases**: `drm`, `dankrm`

## `setmarriagepartner`

Sets (or changes) your current Dank Memer marriage partner (for marriage reminders).
To reset your marriage partner to None, do not specify a user.

!!! tip "Usage"
    
    `setmarriagepartner <user>`

    * `user`: The user to be set as your marriage partner. If no `user` is specified, your marriage partner will be reset.

**Aliases**: `smp`, `mp`, `marriagepartner`

## `trendinggame`
Sets the current trending game.

!!! tip "Usage"
    
    `trendinggame <game_name>`

    * `<game_name>`: The game that is trending. To see if an existing trending game is set, do not specify a game.

## `dankcooldowns`
Shows your reminder durations in Discord timestamp format.

!!! tip "Usage"
    
    `dankcooldowns`

**Aliases**: `dankcd`, `dcd`

## `dankitems`

This command shows the latest donation values of an item. These values are derived from Dank Memer's trade value, unless it has been manually overwritten by an admin.

!!! tip "Usage"

    `dankitems <item>`

    * `<item>`: The item to show its trade value.

    If you don't specify an item, it will show the trade values for all items.

**Aliases**: `items`

## `dankitems set`

Set the value of a Dank Memer item, overwriting it and preventing it from being updated automatically.

!!! tip "Usage"

    `dankitems set [item] [value]`

    * `item`: The item to set its trade value.
    * `value`: The value to set it to. If you want to reset the value and make it update with Dank Memer's trade values, set the `value` to `none`.

**Aliases**: `setvalue`

## `itemcalc`

Calculates the total donation value of a bunch of items. 

!!! tip "Usage"

    `itemcalc <number of items> [item] <number of items> [item]`

    * `number of items`: The number of items to calculate the value of. This can be left out, and Dank Vibes Bot will interpret it as **one** item.
    * `item`: The item to calculate the value of. This is compulsory.

**Aliases**: `ic`