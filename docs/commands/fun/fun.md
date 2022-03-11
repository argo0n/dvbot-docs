# Fun

## `dumbfight`

Fight a user, and you or them might get muted between 20 to 120 seconds, depending on who wins. 

[Drinking a dumbfight potion](../commands/fun/item_games.md/#use) will rig your chance to win or lose the dumbfight.

!!! tip "Usage"
    
    `dumbfight [user]`

    * `user`: The user you want to fight.

**Aliases**: `df`

## `hideping`

Secretly ping someone with this command! Using this command will delete your message, and ping your target with an anonymous webhook, plus hiding the ping (for iOS, Desktop and Web users only).

!!! tip "Usage"
    
    `hideping <channel> [member] <message>`

    * `channel`: The channel in which you would want your target to be pinged in.
    * `member`: The target who you want to hide ping.
    * `message`: An optional message to show when the user gets pinged.

**Aliases**: `hp`, `secretping`

## `chatchart`

Show the percentage of messages sent by various members in a channel.

Add the `--bots` flag to include bots in the chatchart.

!!! tip "Usage"
    
    `chatchart <channel> (--bots)`

    * `channel`: The channel to generate a chatchart for.


**Aliases**: `cc`



## `nickbet`

Challenge your friend to a nick bet! Both of you will choose a nickname for one another, and one of you will choose a side of the coin.

If the coin flips onto the side that you choose, you will win! The loser will have their nickname changed.

!!! tip "Usage"

    `nickbet [user] <duration>`

    * `user`: The user you want to challenge.
    * `duration`: The duration of the nickbet. If a duration is specified, the loser will have their nicknames frozen for that entire duration.

**Aliases**: `nb`

## `snipe`

"snipes" a deleted message, showing its content. 

!!! tip "Usage"
    
    `snipe`

**Aliases**: `s`

## `editsnipe`

"snipes" an edited message, showing its unedited content.

!!! tip "Usage"
    
    `editsnipe` 

**Aliases**: `es`

## `reactionsnipe`

"snipes" a removed reaction. 

!!! tip "Usage"
    
    `reactionsnipe`

**Aliases**: `reactionsnipe`

## `lockgen`

Locks #general-chat for 5 seconds. Simple as that.

This command has a 2 minute global cooldown to prevent abuse.

!!! tip "Usage"
    
    `lockgen`

**Aliases**: `lg`

## `scramble`

Scrambles your target's nickname for 3 minutes, effectively freezing it until the 3 minutes are up.

!!! tip "Usage"
    
    `scramble [user]`

    * `user`: The user whose nickname you would like to scramble.

**Aliases**: `shuffle`


## `firstmessage`

Shows the first message of a channel.

!!! tip "Usage"
    
    `firstmessage <channel>`

    * `channel`: The channel whose first message you would like to see.

**Aliases**: `fm`

## `covidvbot`

Fetches information about the virus game in Dank Vibes Bot.

!!! tip "Usage"
    
    `covidvbot`


**Aliases**: `covid`, `infect`


## `randomcolor`

Changes the **Random Color** role's color to a random color. It can only be used 3 times a day.

!!! tip "Usage"
    
    `randomcolor`

**Aliases**: `rc`

## `color`

Can be used to show a certain color, or get dominant and matching colors of an image.

!!! tip "Usage"
    
    `color [argument]`

    * `argument`: This argument can be:
        - a color hexcode from #000000 to #FFFFFF
        - a URL to an image
        - a user (to get the profile picture)

**Aliases**: `cc`

## `dm`

Acting like a messenger, Dank Vibes Bot will anonymously DM a user on your behalf. 

Your DM will be manually approved by a higher-up.

!!! tip "Usage"
    
    `dm [member] [message]`

    * `member`: The member who you want to send a message to.
    * `message`: The message you want to send to them.


## `guessthenumber`

Sets up an interactive guess the number game. This command can only be run in #events, by the event host or sponsor.

Running this command will start an interactive setup to be completed in your DMs.

!!! tip "Usage"
        
    `guessthenumber`


**Aliases**: `gtn`, `numberevent`