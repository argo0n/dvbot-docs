# Giveaway Utilities

The giveaway features for Dank Vibes Bot are in beta development.

## `trophy` 

Starts a trophy giveaway. 

!!! tip "Usage"
    
    `trophy <flags>`

    * `flags`:
        - `--prize [prize]`: The prize for the giveaway. if no prize is specified, it will default to "<a:dv_iconOwO:837943874973466664> **1 Pepe Trophy**".
        - `--time [time]`: The time in seconds for the giveaway to last. if no time is specified, it will default to 24 hours.
        - `--winner [number]`: the number of winners for the giveaway. if no number is specified, it will default to 1.
        - `--msg [message]`: an additional message to accompany the giveaway ping. if no message is specified, it will default to "Enter the trophy giveaway above!".

## `giveaway` 

This command does nothing.

**Aliases**: `g`

## `giveaway start`

[![also available as a slash](../../assets/slash_command.gif)](../../slash_commands/#giveaway-start)

!!! warning
    This command is non-functional, please check the [slash command version](../../slash_commands/#giveaway-start) of it.

**Aliases**: `giveaway s`

## `giveaway cancel`

Cancels a giveaway before it's supposed to be over. No winners will be picked.

!!! tip "Usage"

    `giveaway cancel [message]`

    * `message`: A message link to the giveaway, or a message ID.

**Aliases**: `giveaway c`

## `giveaway end`

Ends a giveaway before it's supposed to be over. Winners will be picked.

!!! tip "Usage"

    `giveaway end [message]`

    * `message`: A message link to the giveaway, or a message ID.

**Aliases**: `giveaway e`

## `giveaway reroll`

Rerolls the winner for a giveaway.

!!! tip "Usage"
    `giveaway reroll [message_id] <winners>`

    * `message_id`: The message ID or link to the giveaway.
    * `winners`: The number of winners to reroll for the giveaway.

**Aliases**: `giveaway r`

## `giveaway active`

List active giveaways.

!!! tip "Usage"
    `giveaway active`

**Aliases**: `giveaway a`, `giveaway list`, `giveaway l`

## `giveaway gw`

A command for giveaway staffs. 

## `giveaway elite`

A command for giveaway staffs. 

## `giveaway booster`

A command for giveaway staffs. 

## `giveaway nitro`

A command for giveaway staffs. 

## `giveawayconfig`

Giveaway configurations (or profiles) can be set for specific channels. They are like a template, where in each channel, you can choose roles that can bypass the giveaway requirement, roles that are blacklisted from joining or roles that can gain extra entries from the giveaway. When you start a giveaway, these configurations will be applied to the giveaway automatically.

This command will show you all existing giveaway profiles for various channels in the server.

!!! tip "Usage"

    `giveawayconfig`

**Aliases**: `gwconfig`

## `giveawayconfig add`

Creates a fresh new giveaway profile for a channel.

!!! tip "Usage"

    `giveawayconfig add [channel]`

    * `channel`: The channel to create the profile for.

**Aliases**: `giveawayconfig create`, `giveaway new`

## `giveawayconfig edit`

Edits the giveaway profile for a channel.

Unlike many other bots, there is only one command for editing bypass, blacklist and multi roles all in one go. 

You can choose what you want to edit by selecting the buttons, and following the instructions for adding or removing roles.

![type:video](../../assets/GiveawayConfig.mp4)

!!! tip "Usage"

    `giveawayconfig edit [channel]`

    * `channel`: The channel to edit the profile for.