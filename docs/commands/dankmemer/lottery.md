# Lottery Management

## `lottery`

Add users to the specified lottery. If no user is provided, it will show the last entered user for the lottery instead.

Any reserved numbers from [`lottery reserve`](#lottery-reserve) will be automatically added to the lottery.

!!! tip "Usage"

    `lottery [lottery_id] [user] <user> <user>...`

    * `lottery_id`: The ID of the lottery you want to add users to.
    * `user`: The user you want to add to the lottery. You can specify as many users as you want.

## `lottery start`

Starts a lottery.

!!! tip "Usage"

    `lottery start [lottery_type] [max_tickets] [entry_fee]`

    * `lottery_type`: The type of lottery you want to start. **It must be one of `dank`, `karuta` or `owo`.**
    * `max_tickets`: The maximum number of tickets you want to allow per user.
    * `entry_fee`: The amount of money you want to charge per ticket. This doesn't really do anything except for showing the embed in the lottery channel.

## `lottery reserve` 

Reserve a lottery number for a user, or view the existing reserved numbers for a lottery.

!!! tip "Usage"

    `lottery reserve [lottery_id] [user] [lottery_number]`

    * `lottery_id`: The ID of the lottery you want to reserve a number for.
    * `user`: The user you want to reserve a number for. If a user is not specified, it will show the already reserved numbers for the lottery.
    * `lottery_number`: The number you want to reserve. If you want to remove a reserved number, specify the same user and lottery number.

## `lottery makecount`

If you messed up, use this command to change the lottery's current entry number.

This number should be the last number entered correctly.

!!! tip "Usage"

    `lottery makecount [lottery_id] [entry_number]`

    * `lottery_id`: The ID of the lottery you want to change the entry number for.
    * `entry_number`: The last correctly entered entry number.

## `lottery end`

Ends a lottery, duh.

If there are un-entered reserved lottery numbers, it will be added automatically before the lottery winner is chosen.

Dank Vibes Bot will then DM you on the template to send for #gold-pot.

!!! tip "Usage"

    `lottery end [lottery_id]`

    * `lottery_id`: The ID of the lottery you want to end.
    