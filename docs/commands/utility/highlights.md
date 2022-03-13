# Highlights

Highlights are a feature in Dank Vibes Bot, that allows you to be notified when a user mentions a phrase highlighted by you.

## `highlight`

Adds a text or phrase to your highlight list.
        
When you don't talk after a minute, you will be DMed if someone highlights you with said phrase.

!!! tip "Usage"

    `highlight [phrase]`

    * `phrase`: The phrase to highlight.

## `highlight remove`

Removes a phrase or text from your highlight list.

!!! tip "Usage"

    `highlight remove [phrase]`

    * `phrase`: The phrase to remove from your highlight list.

**Aliases**: `-`

## `highlight show`

Shows all the phrases or text that you're tracking, along with any ignored members or channels.

!!! tip "Usage"

    `highlight show`

**Aliases**: `display`, `list`

## `highlight block`

Adds a member or channel to the highlight block list.

If a user in this list highlights you, or you were highlighted in a ignored channel, you will not be notified of it.

!!! tip "Usage"

    `highlight block [argument]`

    * `argument`: The member or channel to block.

**Aliases**: `ignore`

## `highlight unblock`

Removes a channel or member from your highlight ignore list.

!!! tip "Usage"

    `highlight unblock [argument]`

    * `argument`: The channel or member to unblock and remove from your highlight ignore list.

**Aliases**: `unignore`

## `highlight clear`

Resets your highlight list. This action cannot be reversed.

!!! tip "Usage"

    `highlight clear`

**Aliases**: `reset`

## `highlight import`

Imports your highlight settings from Carl-bot.

!!! tip "Usage"

    `highlight import`

    Dank Vibes Bot will then bring you through an interactive and easy setup to move your highlight settings from Carl-bot to Dank Vibes Bot.