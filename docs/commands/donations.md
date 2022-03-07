# Donation Utilities

Dank Vibes Bot track donations for users across different categories. 
A category can be created with [`add-category`](#add-category), and deleted with [`remove-category`](#remove-category).

Using [`mydonations`](#mydonations) or [`donations`](#donations) will show a user's donations for all categories.

## `mydonations`

Shows your own donations.

!!! tip "Usage"
    
    `mydonations`

**Aliases**: `myd`

## `donations`

Shows a user's donations. 
!!! warning
    This is mainly for staff to use, to view your own donations use [`mydonations`](#mydonations) instead.

!!! tip "Usage"
    
    `donations [member]`

    * `member`: The user whose donations you'd want to check.

**Aliases**: `d`

## `donationslb`

Shows the donation leaderboard of a category.

!!! tip "Usage"
    
    `donationslb [category-name] <number_of_users>`

    * `category-name`: The name of the donation category.
    * `number_of_users`: The number of users to show on the donation category.

**Aliases**: `dlb`


## `weeklydankleaderboard`

Shows the donation leaderboard for the Dank Memer category. 

!!! warning 
    To see the leaderboard for another category, use [`donationslb`](#donationslb).

!!! tip "Usage"
    
    `weeklydankleaderboard`

**Aliases**: `wdlb`, `weeklylb`, `wlb`



## `add-category`

Creates a donation category.

!!! tip "Usage"
    
    `add-category [category-name]`

    * `category-name`: The name for the new donation category

## `remove-category`

Removes an existing donation category.

!!! tip "Usage"
    
    `remove-category [category-name]`

    * `category-name`: The name of the category to be deleted.

## `resetdonations`

Reset the donations of a category. This action cannot be undone!!

!!! tip "Usage"
    
    `resetdonations [category-name]`

    * `category-name`: The name of the donation category to reset donations for.

## `adddonations`

Add donations to a user.

!!! tip "Usage"
    
    `adddonations [member] [amount] [category_name]`

    * `member`: Member to add donations to.
    * `amount`: Amount to add to their existing donations.
    * `category_name`: The name of the donation category to be added.

**Aliases**: `ad`

## `removedonations`

Remove donations from a user.

!!! tip "Usage"
    
    `removedonations [member] [amount] [category_name]`

    * `member`: Member to remove donations from.
    * `amount`: Amount to remove from their existing donations.
    * `category_name`: The name of the donation category to be removed.

**Aliases**: `rd`

## `set-donations`

Set donations for a user to a certain amount; this is different from adding (`adddonations`) and removing (`removedonations`) donations.

!!! tip "Usage"
    
    `set-donations [member] [amount] [category_name]`

    * `member`: Member to set donations for.
    * `amount`: Amount to set their donations to.
    * `category_name`: The name of the donation category to be set.

**Aliases**: `sd`


