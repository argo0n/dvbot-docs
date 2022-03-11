# Tools

Dank Vibes Bot provides a range of tools meant to make moderation easier, such as having a censor function, bulk lockdown and others.

When a support ticket is created, Dank Vibes Bot will inform the user to say their issue if they have not said anything in the ticket. 

Separately, to ensure efficiency, if the ticket creator only says "hi", Dank Vibes Bot will inform them that they need to specify their reason for opening the ticket.

!!! warning

    Censor functions in Dank Vibes Bot are only for moderating output such as [`hideping`](../../fun/fun/#hideping), [`nick`](../../fun/fun/#nickbet) and [`dm`](../../fun/fun/#dm). 

## `getraw`

Gets the raw content of a message.

!!! tip "Usage"

    `getraw [message_id] <channel>`

    * `message_id`: The ID of the message which you want to get the raw content of.
    * `channel`: The channel of the message, if it was sent in another channel (not the one you're in).

## `censor`

Censor a word or phrase.

To view the list of censored words, use [`censor list`](#censor-list).

To remove a censored word, use [`censor remove`](#censor-remove).

!!! tip "Usage"

    `censor [phrase]`

    * `phrase`: Phrase to be censored.

**Aliases**: `censor add`

## `censor list`

List all censored/blacklisted words.

!!! danger

    Do not run this in a public channel.

!!! tip "Usage"
    
    `censor list`

## `censor remove`

Remove a word or phrase from the censor list.

!!! tip "Usage"

    `censor remove [phrase]`

    * `phrase`: Phrase to be removed from the censor list.

## `lockdown start`

Lock all the channels in a lockdown profile.

!!! tip "Usage"

    `lockdown start [name]`

    * `name`: Name of the lockdown profile.

## `lockdown end`

Unlock all the channels in a lockdown profile.

!!! tip "Usage"

    `lockdown end [name]`

    * `name`: Name of the lockdown profile.

## `lockdown view`

View the channels in a lockdown profile (and whether they're locked), or see all the lockdown profiles available.

!!! tip "Usage"

    `lockdown view <name>`

    * `name`: Name of the lockdown profile. If you don't specify a lockdown profile, it will show all the lockdown profiles instead. 

## `lockdown create` 

Creates a lockdown profile, allowing channels in that profile to be locked all at once. \

!!! tip "Usage"

    `lockdown create [name] [channel]`

    * `name`: Name of the lockdown profile.
    * `channel`: The first channel in the lockdown profile.

## `lockdown delete`

This **deletes** a lockdown profile!

!!! danger

    This will **delete** the lockdown profile, and it cannot be recovered.

!!! tip "Usage"

    `lockdown delete [name]`

    * `name`: Name of the lockdown profile.

**Aliases**: `clear`

## `lockdown add`

Adds a channel to a lockdown profile.

!!! tip "Usage"

    `lockdown add [name] [channel]`

    * `name`: Name of the lockdown profile.
    * `channel`: The channel you'd like to add to the lockdown profile. **You can specify more than one lockdown channel at once in the command (`lockdown add alpha #channel-1 #channel-2 #channel-3`).**

## `lockdown remove`

Removes a channel from a lockdown profile.

!!! warning

    If you remove all channels from a lockdown profile, that effectively deletes it.

!!! tip "Usage"
    
    `lockdown remove [name] [channel]`

    * `name`: Name of the lockdown profile.
    * `channel`: The channel you'd like to remove from the lockdown profile. **You can specify more than one lockdown channel at once in the command (`lockdown remove alpha #channel-1 #channel-2 #channel-3`).**

## `lockdown message`

Changes the lockdown message (that is sent when a lockdown starts or ends) for a lockdown profile. You can add a embed as the lockdown message by getting the JSON code of an embed via [Carlbot's dashboard](https://carl.gg/dashboard/595457764935991326/embeds). Otherwise, a normal message will be shown in a generic embed's description.

You can choose whether to send the message when a lockdown starts or ends.

To view the message for a lockdown profile, just use the command without a message.

!!! tip "Usage"

    `lockdown message [name] <message>`

    * `name`: Name of the lockdown profile.
    * `message`: The message to be sent when a lockdown starts or ends. To see the current message set, do not specify a message.


## `list`

List roles, users or channels by providing their IDs using this command! This command won't ping any users or roles.

!!! tip "Usage"

    `list [list_type] [things_to_list]`

    * `list_type`: The type of list you'd like to see. It can be `member/user`, `role`, or `channel`.

    * `things_to_list`: The IDs you'd like to list. It should be user, role or channel IDs separated by spaces, or newlines.

## `screenshot`

Gets the screenshot of a website. Any website can be specified.

You are not allowed to use this command to get private information about the bot, such as IP addresses, locations, and the bot's server's specifications. Doing so will result in a command blacklist.

!!! tip "Usage"

    `screenshot [website]`

    * `website`: The website link you'd like to get the screenshot of.

**Aliases**: `ss`

## `self`

Sends a message showing 6 self roles which can be obtained via buttons.

To highlight a role in green, use `--roles the **full names** of the roles` separated in commas. They are not case sensitive.

!!! tip "Usage"

    `self <channel> <roles>`

    * `channel`: Channel to send the message to. 
    * `roles`: Roles to highlight in green. Example: `--roles partnered heist ping,events ping`

**Aliases**: `selfroles`

## `memberpvc`

Checks and shows the private chanenls that a member has access to. 

!!! warning

    This is only for higher-ups. To see the members in your own private channel, use [`pvc`](../../utility/#pvc)

!!! tip "Usage"

    `memberpvc <member>`

    * `member`: Member to check. If no member is specified it will show the channels you have access to.

## `dhvt`

No description provided.

!!! tip "Usage"

    `dhvt`

## `role`

Use this command to add or remove a role to or from a user.

!!! tip "Usage"

    `role [user] [role]`

    * `user`: The user to add or remove the role from.
    * `role`: The role to add or remove.

## `role icon`

Change a role's icon.

!!! tip "Usage"

    `role icon [role] [argument]`

    * `role`: The role to change the icon of.
    * `argument`: The argument to change the icon to. It can be a Unicode Emoji, Custom Emoji, Attachment or URL to an image. 

## `role removeall`

Remove a specific role from everyone who has it.

!!! tip "Usage"

    `role removeall [role]`

    * `role`: The role to remove from everyone.

**Aliases**: `rall`

## `sticky resetlist`

Resets the queue that contains channels for sticky messages. This fixes a bug caused by improper API handling by Discord.

!!! tip "Usage"

    `sticky resetlist`

## `sticky create`

Creates a sticky message for the specified channel. Only one sticky message can be created for one channel.

To add an embed as a message, add it in the form of a JSON code which you can get from [Carl-bot's dashboard](https://carl.gg/dashboard/595457764935991326/embeds).

!!! tip "Usage"

    `sticky create [channel] [message]`

    * `channel`: The channel to create the sticky message in.
    * `message`: The message to be sent as a sticky message.

**Aliases**: `add`

## `sticky remove`

Removes a sticky message from the specified channel.

!!! tip "Usage"

    `sticky remove [channel]`

    * `channel`: The channel to remove the sticky message from.

## `sticky view`

Shows all active sticky messages in the server.

!!! tip "Usage"

    `sticky view`

