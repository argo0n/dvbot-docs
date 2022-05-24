# Slash Commands

As there are very little slash commands at the moment, they have all been condensed into one single page. 

## `/hideping`

Secretly ping someone with this command! 

!!! tip "Usage"

    `/hideping [target] <channel? <message>`

    * `target`: The user you want to ping.
    * `channel`: The channel in which you would want your target to be pinged in.
    * `message`: An optional message to show when the user gets pinged.

## `/dm`

Acting like a messenger, Dank Vibes Bot anonymously will DM the user on your behalf.

!!! tip "Usage"

    `/dm [member] [message]`

    * `member`: The member who you want to send a message to.
    * `message`: What to DM to the user

## `/goeatpoop`

Image generation | Get someone to eat poop

!!! tip "Usage"

    `/goeatpoop [member]`

    * `member`: The member who you want to eat poop

## `/stank`

Image generation | Someone's too stanky in here.

!!! tip "Usage"

    `/stank [member]`

    * `member`: The member who is stinky

## `/audacity`

Image generation | The Lion, The Witch, and the Audacity of-

!!! tip "Usage"

    `/audacity [member]` 

    * `member`: The member who is being a b-

## `/annoy`

Generate an image of someone being annoying in your DMs.

!!! tip "Usage"
    
    `/annoy [member]` 

    * `member`: The member who is annoying you

## `/captcha`

Generate a reCAPTCHA button with the specified text.

!!! tip "Usage"
    
    `/captcha [text]` 

    * `text`: The text to show beside the recaptcha button.

## `/didyoumean`

Google's Did You Mean can be really fuzzy sometimes.

!!! tip "Usage"
    
    `/didyoumean [search_bar_text] [did_you_mean_text]` 

    * `search_bar_text`: The phrase that you were searching on Google
    * `did_you_mean_text`: What Google thought you meant


## `/drake`

I don't really know how to explain this meme... It's just the drake hotline bling meme thing

!!! tip "Usage"
    
    `/drake [top_text] [bottom_text]` 

    * `top_text`: The top text that Drake doesn't like.
    * `bottom_text`: The bottom text that Drake likes

## `/fact`

IT IS A FACT!!!

!!! tip "Usage"
    
    `/fact [text]` 

    * `text`: The text that is a fact.

## `/bad`

you bad bad (but it's a man)

!!! tip "Usage"
    
    `/bad [member]` 

    * `member`: the member who is misbehaving

## `/what`

*sancturary guardian music plays*

!!! tip "Usage"

    `/what [member]`

    * `member`: WHAT

## `/spam`

Shows you images of spam (the food)

!!! tip "Usage"

    `/spam`

## `/spoiler`

Adds a fake spoiler tag to a photo that you sent, including blurring it.

!!! tip "Usage"

    `/spoiler <member> <link> <attachment>`

    * `member`: The member whom you want to add the spoiler tag to their profile picture.
    * `link`: The link to the image you want to add the spoiler tag to.
    * `attachment`: The attachment that you want to add the spoiler tag to.

    **Only send one of these arguments!!** For example: If you add a `member`, do not add a `link` or `attachment`.

## `/find`

Find a entity in the server, be it a member, role or channel.

This makes use of Discord's ability to autocomplete when finding such objects.

When entering a object, its name, ID (and mention, if applicable) will be sent.

!!! tip "Usage"

    `/find <user> <role> <text_chanel> <voice_channel> <category_channel> <stage_channel>`

    * `user`: The user you want to find.
    * `role`: The role you want to find.
    * `text_chanel`: The text channel you want to find.
    * `voice_channel`: The voice channel you want to find.
    * `category_channel`: The category channel you want to find.
    * `stage_channel`: The stage channel you want to find.

    At least one of these arguments must be provided.

## `/giveaway start`

Start a giveaway in the server!

This command is only available as a slash command as it is complicated to parse for different items in a prefixed (text) command.

This command will:

- Fetch any existing configs for giveaways.
- Check if you have a booster role as a requirement, and if so remove any bypass roles.
- Asks for your confirmation before starting the giveaway.

!!! tip "Usage"

    `/giveaway start [duration] [prize] <number_of_winners> <donor> <message> <required_role> <required_role2> <required_role3> <amari_level> <amari_weekly_xp> <channel>`

    * `duration`: The duration of the giveaway.
    * `prize`: The prize of the giveaway.
    * `number_of_winners`: The number of winners who can win in the giveaway.
    * `donor`: The donor of the giveaway.
    * `message`: A message that will be displayed as if the donor (or giveaway host) had sent it.
    * `required_role`: The required role to participate in the giveaway.
    * `required_role2`: The required role to participate in the giveaway.
    * `required_role3`: The required role to participate in the giveaway.
    * `amari_level`: The Amari level required to participate in the giveaway.
    * `amari_weekly_xp`: The Amari Weekly XP required to participate in the giveaway.
    * `channel`: The channel in which the giveaway will be held.