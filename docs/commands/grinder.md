# Grinder Utilities

Grinder utilities are for keeping track of grinders' donated statistics automatically.
When coins are shared by a grinder with the **3M Grinder Tier**, **5M Grinder Tier** or **Trial Grinder** role, the bot will automatically add the user to their grinder data.

## `grindercheck` 

Shows you or a user's Grinder statistics.

!!! tip "Usage"

    `grindercheck <user>`
    
    * `user`: The user whose Grinder statistics you'd like to check. If no `user` is specified, your own Grinder statistics will be shown.

**Aliases**: `gcheck`, `gc`


## `gedit` 

Adds or removes a certain amount of coins from a grinder's data. To change it to a specific amount, use [`gset`](#gset) instead.

!!! tip "Usage"

    `gedit [member] [number]`
    
    * `member`: The user whose Grinder data you'd like to edit.
    * `number`: The amount of coins you'd like to add or remove.


## `gset` 

Sets the coins a grinder has donated to a specific amount. To add or remove coins, use [`gedit`](#gedit) instead.

!!! tip "Usage"

    `gset [member] [number]`
    
    * `member`: The user whose Grinder data you'd like to edit.
    * `number`: The amount of coins you'd like to set.

## `gedit` 

Adds or removes a certain amount of coins from a grinder's data. To change it to a specific amount, use [`gset`](#gset) instead.

!!! tip "Usage"

    `gedit [member] [number]`
    
    * `member`: The user whose Grinder data you'd like to edit.
    * `number`: The amount of coins you'd like to add or remove.

## `gdm`

This command will: 

* Check whether grinders have completed their requirement, and send summary to specified channels. 
* Remind grinders that their requirements have been checked.

!!! tip "Usage"

    `gdm <flags>`

    * `flags`: Optional Flags
        - `--msg [message]`: Add an optional message to be DMed to each grinder.

## `grinderleaderboard`

Shows the Grinder Leaderboard.

!!! tip "Usage"
    
    `grinderleaderboard <arg>`

    * `arg`: Duration of the leaderboard.
        - `daily` for today's Grinder leaderboard.
        - `weekly` for this week's Grinder leaderboard.
        - `last week` for last week's Grinder leaderboard.
        - `monthly` for this month's Grinder leaderboard.

## `grinderpaymentinadvance`

Sets the in advance payout balance for a user.

If a user's in advance payout balance is more than 0, whenever the grinder requirement is checked, it'll deduct from this balance as if the user completed their requirement. 

!!! tip "Usage"

    `grinderpaymentinadvance [member] [amount]`

    * `member`: The user whose in advance payout amount you'd like to edit.
    * `amount`: The amount of coins to be added (+) or removed (-) from their in advance payout balance.
