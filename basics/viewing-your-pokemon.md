---
description: >-
  On this page you will learn about your pokémon inventory and everything you
  need to know to view, edit and interact with the pokémon you acquire via
  catching, market, auction or other methods.
---

# Your Pokémon

{% hint style="warning" %}
This site is an early **work in progress**. Many pages may be missing or incomplete. Please let us know at [discord.gg/poketwo](https://discord.gg/poketwo) if you would like to help write or improve a page.
{% endhint %}

### Contents

1. [#list-of-related-commands](viewing-your-pokemon.md#list-of-related-commands "mention")
2. [#introduction](viewing-your-pokemon.md#introduction "mention")
3. [#viewing-your-inventory](viewing-your-pokemon.md#viewing-your-inventory "mention")
   1. [#navigating](viewing-your-pokemon.md#navigating "mention")
   2. [#filtering](viewing-your-pokemon.md#filtering "mention")
   3. [#ordering](viewing-your-pokemon.md#ordering "mention")
   4. [#reindexing](viewing-your-pokemon.md#reindexing "mention")
4. [#selecting-pokemon](viewing-your-pokemon.md#selecting-pokemon "mention")
   1. [#preventing-xp-gain](viewing-your-pokemon.md#preventing-xp-gain "mention")
   2. [#preventing-evolution](viewing-your-pokemon.md#preventing-evolution "mention")
5. [#infoing-pokemon](viewing-your-pokemon.md#infoing-pokemon "mention")
6. [#favoriting-and-unfavoriting](viewing-your-pokemon.md#favoriting-and-unfavoriting "mention")
   1. [#favoriting-in-bulk](viewing-your-pokemon.md#favoriting-in-bulk "mention")
   2. [#unfavoriting-in-bulk](viewing-your-pokemon.md#unfavoriting-in-bulk "mention")
7. [#nicknaming](viewing-your-pokemon.md#nicknaming "mention")
   1. [#nicknaming-in-bulk](viewing-your-pokemon.md#nicknaming-in-bulk "mention")
8. [#releasing](viewing-your-pokemon.md#releasing "mention")
   1. [#releasing-in-bulk](viewing-your-pokemon.md#releasing-in-bulk "mention")

### List of related commands

1. `@​Pokétwo#8236 [pokemon|p] [filters]` - To view your pokémon inventory
2. `@​Pokétwo#8236 [info|i] [pokémon-id]` - To view the info of a pokemon. Shows currently selected pokémon if no ID is provided
3. `@​Pokétwo#8236 [order|or] [sorting-method]` - To sort your pokémon inventory
4. `@​Pokétwo#8236 reindex` - To reindex your pokémons' IDs to fix missing IDs or other such problems
5. `@​Pokétwo#8236 [select|s] <pokémon-id>` - To select a pokémon
6. `@​Pokétwo#8236 [favorite|fav]/[unfavorite|unfav] <pokémon-ids>` - To favorite/unfavorite one or more pokémon by ID
7. `@​Pokétwo#8236 [favoriteall|favall]/[unfavoriteall|unfavall] [filters]` - To favorite/unfavorite pokémon in bulk

### Introduction

You will, over the course of playing Pokétwo, acquire many different pokémon from many different sources such as catching, market, auction, trading, etc. On this page, you will learn the different ways to view and interact with those pokémon.

### Viewing Your Inventory

The command `@​Pokétwo#8236 [pokemon|p]` is used to view all the pokémon which you own.

This will show you a list of your collected pokémon in the order that is set (default is by ID).

![](<../.gitbook/assets/Screenshot 2023-02-26 154143.png>)

#### Navigating

To navigate through the pages of your inventory, you can use the ◀ and ▶️ buttons or use the following commands:

* `@​Pokétwo#8236 [first|f]` - To go to the first page of your inventory
* `@​Pokétwo#8236 [next|n|forward]` - To go to the next page
* `@​Pokétwo#8236 [previous|prev|back|b]` - To go to the previous page
* `@​Pokétwo#8236 [last|l]` - To go to the last page of your inventory
* `@​Pokétwo#8236 [go|g|page] <page-number>` - To jump to a specific page of your inventory

#### Filtering

As you acquire more and more pokémon, it will get harder and harder to find specific pokémon in your inventory. That's where filters come in.

You can use various filters with the `@​Pokétwo#8236 pokemon [filters]` command to filter the pokémon that are shown. The filters that are supported with this command are:

<details>

<summary><code>pokemon</code> supported filters</summary>

* [--alolan](../intermediate-topics/search-filters.md#alolan)
* [--atkiv](../intermediate-topics/search-filters.md#atkiv-less-than-integer-greater-than)
* [--defiv](../intermediate-topics/search-filters.md#defiv-less-than-integer-greater-than)
* [--embedcolor](../intermediate-topics/search-filters.md#embedcolor)
* [--event](../intermediate-topics/search-filters.md#event)
* [--favorite](../intermediate-topics/search-filters.md#favorite)
* [--galarian](../intermediate-topics/search-filters.md#galarian)
* [--hextuple](../intermediate-topics/search-filters.md#hextuple-less-than-integer-greater-than)
* [--hpiv](../intermediate-topics/search-filters.md#hpiv-less-than-integer-greater-than)
* [--iv](../intermediate-topics/search-filters.md#iv-less-than-integer-decimal-greater-than)
* [--legendary](../intermediate-topics/search-filters.md#legendary)
* [--level](../intermediate-topics/search-filters.md#level-less-than-integer-greater-than)
* [--limit](../intermediate-topics/search-filters.md#limit-less-than-integer-greater-than)
* [--mega](../intermediate-topics/search-filters.md#mega)
* [--mythical](../intermediate-topics/search-filters.md#mythical)
* [--name](../intermediate-topics/search-filters.md#name-less-than-name-greater-than)
* [--nickname](../intermediate-topics/search-filters.md#nickname-less-than-nickname-greater-than)
* [--pentuple](../intermediate-topics/search-filters.md#pentuple-less-than-integer-greater-than)
* [--quadruple](../intermediate-topics/search-filters.md#quadruple-less-than-integer-greater-than)
* [--region](../intermediate-topics/search-filters.md#region-less-than-region-greater-than)
* [--shiny](../intermediate-topics/search-filters.md#shiny)
* [--skip](../intermediate-topics/search-filters.md#skip-less-than-integer-greater-than)
* [--spatkiv](../intermediate-topics/search-filters.md#spatkiv-less-than-integer-greater-than)
* [--spdefiv](../intermediate-topics/search-filters.md#spdefiv-less-than-integer-greater-than)
* [--spdiv](../intermediate-topics/search-filters.md#spdiv-less-than-integer-greater-than)
* [--triple](../intermediate-topics/search-filters.md#triple-less-than-integer-greater-than)
* [--type](../intermediate-topics/search-filters.md#type-less-than-type-greater-than)
* [--ub](../intermediate-topics/search-filters.md#ub)

</details>

For more info on a specific filter, click its name in the above list. To know more about filters in general, please visit [search-filters.md](../intermediate-topics/search-filters.md "mention")

<details>

<summary>Examples</summary>

Pokémon with level higher than 50

```
@​Pokétwo#8236 pokemon --level > 50
```

All Ralts

```
@​Pokétwo#8236 pokemon --name Ralts
```

Pokémon with IV less than 10

```
@​Pokétwo#8236 pokemon --iv < 10
```

</details>

#### Ordering

By default, your inventory is going to be sorted by the order each pokémon was acquired; **They will be sorted by their ID**. But this can be changed to either of the following order methods using the `@​Pokétwo#8236 [order|or] <order-method>`:

* `number` - Sort by pokémon ID (default is **ascending**)
* `iv` - Sort by pokémon ID (default is **descending**)&#x20;
* `level` - Sort by pokémon level (default is **descending**)
* `pokedex` - Sort by pokémons' pokedex ID (default is **ascending**)

Add a `+` or `-` to the end of either of these to sort by `ascending` or `descending` respectively. Otherwise, it will use their respective defaults.

<figure><img src="../.gitbook/assets/Screenshot 2023-02-26 171938.png" alt=""><figcaption><p>Example of ordering by ID, descending (-)</p></figcaption></figure>

#### Reindexing

Sometimes when releasing, trading, selling, or other ways in which you can remove/acquire pokémon from your inventory, there may be problems with the IDs of your pokémon such as skipping an ID, 2 pokémon having the same ID, some IDs missing, etc.&#x20;

Such problems with pokémons' IDs can be fixed using the command `@​Pokétwo#8236 reindex`. After you send the command, you will be asked to wait until it is complete. The time it takes to reindex depends on how many pokémon you have.

Example:

As you can see in this image, after releasing a pokémon there is a gap in my inventory where the ID 4 is missing

<figure><img src="../.gitbook/assets/Screenshot 2023-02-26 174011.png" alt=""><figcaption></figcaption></figure>

Now, we can fix this using the `reindex` command, shown as follows:

<figure><img src="../.gitbook/assets/Screenshot 2023-02-26 174311.png" alt=""><figcaption><p>And they have been reindexing, moving all the pokemon after 4 to fix the gap</p></figcaption></figure>

### Selecting Pokémon

You can select a pokémon using the command `@​Pokétwo#8236 [select|s] <pokémon-id>`. Your selected pokémon levels up from your chat activity. Your selected pokémon will be the default for commands that need pokémon ID but one isn't passed. Your selected pokémon will also be safe from being released, sold, or traded.

Whenever you send messages (with an interval of **1.5 seconds**), the pokémon will gain a random amount of XP between **10** and **40**. Commands do not count.

When your selected pokémon reaches the XP requirement, it will level up to the next level, resetting the XP and increasing the XP requirement by **25**. The XP requirement starts from **275** (at level 1) and ends at **2750** (at level 100).

#### Preventing XP gain

Some pokémon like mint shinies may lose value if there is XP on them. You can prevent your selected pokémon from gaining XP by buying and equipping an XP blocker for **150 pokécoins** using `@​Pokétwo#8236 buy xp blocker`.

A safe way to equip an XP blocker on a pokèmon is to buy the XP blocker on a different pokémon and then move it, because otherwise, you may accidentally gain XP:

* Select a different pokémon using `@​Pokétwo#8236 select <pokémon-id>`
* Buy an XP blocker using `@​Pokétwo#8236 buy xp blocker`
* Move the item using `@​Pokétwo#8236 [moveitem|mvi] <ID of pokémon that you want to protect>`

#### Preventing evolution

You can prevent your selected pokémon from evolving by buying an **Everstone** for **150 pokécoins** using `@​Pokétwo#8236 buy everstone`. The pokémon will still gain XP and level up however, just will not evolve under any circumstances.&#x20;

### Infoing pokémon

You can see the info of your pokémon such as IVs, level, nature, etc using the command `@​Pokétwo#8236 [info|i] <pokémon-id>`. if no ID is passed, it will show the info of the selected pokémon.

<figure><img src="../.gitbook/assets/e Screenshot 2023-02-26 182644.png" alt=""><figcaption></figcaption></figure>

In the following sections, the commands support the input of multiple IDs. You can use this tool that I have made, to copy IDs from embeds sent by Pokétwo. Just copy and paste the embed into this tool and it will automatically extract the IDs and let you copy them all or individually.

{% embed url="https://witherredaway.github.io/tools/ids/" %}

### Favoriting and Unfavoriting

You may have noticed some pokémon having a :hearts: emoji next to their name. This means that pokémon is favorited and protected from removal in any way such as releasing, selling, trading, etc.

To favorite one or more pokémon by ID, use the command `@​Pokétwo#8236 [favorite|fav] <pokémon-ids>`. E.g. `@​Pokétwo#8236 favorite 123 4567 89`.&#x20;

Similarly, you can unfavorite one or more pokémon by ID using `@​Pokétwo#8236 [unfavorite|unfav] <pokémon-ids>`. E.g. `@​Pokétwo#8236 unfavorite 123 4567 89`.

#### Favoriting in bulk

You can also favorite pokémon in bulk using the command `@​Pokétwo#8236 [favoriteall|favall|fa] [filters]` where you can use many filters to favorite groups of pokémon.

<details>

<summary><code>favoriteall</code> Supported filters</summary>

1. [--alolan](../intermediate-topics/search-filters.md#alolan)
2. [--atkiv](../intermediate-topics/search-filters.md#atkiv-less-than-integer-greater-than)
3. [--defiv](../intermediate-topics/search-filters.md#defiv-less-than-integer-greater-than)
4. [--embedcolor](../intermediate-topics/search-filters.md#embedcolor)
5. [--event](../intermediate-topics/search-filters.md#event)
6. [--favorite](../intermediate-topics/search-filters.md#favorite)
7. [--galarian](../intermediate-topics/search-filters.md#galarian)
8. [--hextuple](../intermediate-topics/search-filters.md#hextuple-less-than-integer-greater-than)
9. [--hpiv](../intermediate-topics/search-filters.md#hpiv-less-than-integer-greater-than)
10. [--iv](../intermediate-topics/search-filters.md#iv-less-than-integer-decimal-greater-than)
11. [--legendary](../intermediate-topics/search-filters.md#legendary)
12. [--level](../intermediate-topics/search-filters.md#level-less-than-integer-greater-than)
13. [--limit](../intermediate-topics/search-filters.md#limit-less-than-integer-greater-than)
14. [--mega](../intermediate-topics/search-filters.md#mega)
15. [--mythical](../intermediate-topics/search-filters.md#mythical)
16. [--name](../intermediate-topics/search-filters.md#name-less-than-name-greater-than)
17. [--nickname](../intermediate-topics/search-filters.md#nickname-less-than-nickname-greater-than)
18. [--pentuple](../intermediate-topics/search-filters.md#pentuple-less-than-integer-greater-than)
19. [--quadruple](../intermediate-topics/search-filters.md#quadruple-less-than-integer-greater-than)
20. [--region](../intermediate-topics/search-filters.md#region-less-than-region-greater-than)
21. [--shiny](../intermediate-topics/search-filters.md#shiny)
22. [--skip](../intermediate-topics/search-filters.md#skip-less-than-integer-greater-than)
23. [--spatkiv](../intermediate-topics/search-filters.md#spatkiv-less-than-integer-greater-than)
24. [--spdefiv](../intermediate-topics/search-filters.md#spdefiv-less-than-integer-greater-than)
25. [--spdiv](../intermediate-topics/search-filters.md#spdiv-less-than-integer-greater-than)
26. [--triple](../intermediate-topics/search-filters.md#triple-less-than-integer-greater-than)
27. [--type](../intermediate-topics/search-filters.md#type-less-than-type-greater-than)
28. [--ub](../intermediate-topics/search-filters.md#ub)

</details>

#### Unfavoriting in bulk

Similarly, you can unfavorite pokémon in bulk using the command `@​Pokétwo#8236 [unfavoriteall|unfavall|ufa] [filters]` where you can use many filters to unfavorite groups of pokémon.

<details>

<summary><code>unfavoriteall</code> Supported filters</summary>

1. [--alolan](../intermediate-topics/search-filters.md#alolan)
2. [--atkiv](../intermediate-topics/search-filters.md#atkiv-less-than-integer-greater-than)
3. [--defiv](../intermediate-topics/search-filters.md#defiv-less-than-integer-greater-than)
4. [--embedcolor](../intermediate-topics/search-filters.md#embedcolor)
5. [--event](../intermediate-topics/search-filters.md#event)
6. [--favorite](../intermediate-topics/search-filters.md#favorite)
7. [--galarian](../intermediate-topics/search-filters.md#galarian)
8. [--hextuple](../intermediate-topics/search-filters.md#hextuple-less-than-integer-greater-than)
9. [--hpiv](../intermediate-topics/search-filters.md#hpiv-less-than-integer-greater-than)
10. [--iv](../intermediate-topics/search-filters.md#iv-less-than-integer-decimal-greater-than)
11. [--legendary](../intermediate-topics/search-filters.md#legendary)
12. [--level](../intermediate-topics/search-filters.md#level-less-than-integer-greater-than)
13. [--limit](../intermediate-topics/search-filters.md#limit-less-than-integer-greater-than)
14. [--mega](../intermediate-topics/search-filters.md#mega)
15. [--mythical](../intermediate-topics/search-filters.md#mythical)
16. [--name](../intermediate-topics/search-filters.md#name-less-than-name-greater-than)
17. [--nickname](../intermediate-topics/search-filters.md#nickname-less-than-nickname-greater-than)
18. [--pentuple](../intermediate-topics/search-filters.md#pentuple-less-than-integer-greater-than)
19. [--quadruple](../intermediate-topics/search-filters.md#quadruple-less-than-integer-greater-than)
20. [--region](../intermediate-topics/search-filters.md#region-less-than-region-greater-than)
21. [--shiny](../intermediate-topics/search-filters.md#shiny)
22. [--skip](../intermediate-topics/search-filters.md#skip-less-than-integer-greater-than)
23. [--spatkiv](../intermediate-topics/search-filters.md#spatkiv-less-than-integer-greater-than)
24. [--spdefiv](../intermediate-topics/search-filters.md#spdefiv-less-than-integer-greater-than)
25. [--spdiv](../intermediate-topics/search-filters.md#spdiv-less-than-integer-greater-than)
26. [--triple](../intermediate-topics/search-filters.md#triple-less-than-integer-greater-than)
27. [--type](../intermediate-topics/search-filters.md#type-less-than-type-greater-than)
28. [--ub](../intermediate-topics/search-filters.md#ub)

</details>

### Nicknaming

You may have noticed some pokémon having extra text next to their name within quotes. That is a nickname. These are quite useful for organizing your pokémon, but can also act as a way to remember different pokémon and distinguish them.

To nickname pokémon, use the command `@​Pokétwo#8236 [nickname|nick] <pokémon-id> <nickname>`

To reset the nickname of a pokémon, do the same thing but `reset` as the nickname: `@​Pokétwo#8236 nickname <pokémon-id> reset`.

You can find these nicknamed pokémon in the `pokemon` command using the [`--nickname`](../intermediate-topics/search-filters.md#nickname-less-than-nickname-greater-than) filter.

#### Nicknaming in bulk

You can also nickname pokémon in bulk by using the command `@​Pokétwo#8236 [nicknameall|nickall|na] <nickname> [filters]` and use filters to nickname groups of pokémon.

<details>

<summary><code>nicknameall</code> supported filters</summary>

1. [--alolan](viewing-your-pokemon.md#alolan)
2. [--atkiv](viewing-your-pokemon.md#atkiv-less-than-integer-greater-than)
3. [--defiv](viewing-your-pokemon.md#defiv-less-than-integer-greater-than)
4. [--embedcolor](viewing-your-pokemon.md#embedcolor)
5. [--event](viewing-your-pokemon.md#event)
6. [--favorite](viewing-your-pokemon.md#favorite)
7. [--galarian](viewing-your-pokemon.md#galarian)
8. [--hextuple](viewing-your-pokemon.md#hextuple-less-than-integer-greater-than)
9. [--hpiv](viewing-your-pokemon.md#hpiv-less-than-integer-greater-than)
10. [--iv](viewing-your-pokemon.md#iv-less-than-integer-decimal-greater-than)
11. [--legendary](viewing-your-pokemon.md#legendary)
12. [--level](viewing-your-pokemon.md#level-less-than-integer-greater-than)
13. [--limit](viewing-your-pokemon.md#limit-less-than-integer-greater-than)
14. [--mega](viewing-your-pokemon.md#mega)
15. [--mythical](viewing-your-pokemon.md#mythical)
16. [--name](viewing-your-pokemon.md#name-less-than-name-greater-than)
17. [--nickname](viewing-your-pokemon.md#nickname-less-than-nickname-greater-than)
18. [--pentuple](viewing-your-pokemon.md#pentuple-less-than-integer-greater-than)
19. [--quadruple](viewing-your-pokemon.md#quadruple-less-than-integer-greater-than)
20. [--region](viewing-your-pokemon.md#region-less-than-region-greater-than)
21. [--shiny](viewing-your-pokemon.md#shiny)
22. [--skip](viewing-your-pokemon.md#skip-less-than-integer-greater-than)
23. [--spatkiv](viewing-your-pokemon.md#spatkiv-less-than-integer-greater-than)
24. [--spdefiv](viewing-your-pokemon.md#spdefiv-less-than-integer-greater-than)
25. [--spdiv](viewing-your-pokemon.md#spdiv-less-than-integer-greater-than)
26. [--triple](viewing-your-pokemon.md#triple-less-than-integer-greater-than)
27. [--type](viewing-your-pokemon.md#type-less-than-type-greater-than)
28. [--ub](viewing-your-pokemon.md#ub)

</details>

Similarly, you can un-nickname pokémon in bulk by nicknaming them `reset` using the command `@​Pokétwo#8236 [nicknameall|nickall|na] reset [filters]` and using filters to un-nickname groups of pokémon.

### Releasing

At one point when you have been acquiring pokémon a lot, you will find pokémon that are simply useless to you that you want to get rid of to debloat your inventory.&#x20;

Such can be done using the `@​Pokétwo#8236 release <pokémon-ids>` where you can provide multiple IDs to release for **2 pokécoins** each. **Releasing a pokémon will permanently remove it from the bot, so please use it with caution.**

#### Releasing in bulk

You can also release pokémon in bulk by using the command `@​Pokétwo#8236 [releaseall|ra] [filters]` and use filters to release groups of pokémon.

<details>

<summary><code>releaseall</code> supported filters</summary>

1. [--alolan](viewing-your-pokemon.md#alolan)
2. [--atkiv](viewing-your-pokemon.md#atkiv-less-than-integer-greater-than)
3. [--defiv](viewing-your-pokemon.md#defiv-less-than-integer-greater-than)
4. [--embedcolor](viewing-your-pokemon.md#embedcolor)
5. [--event](viewing-your-pokemon.md#event)
6. [--galarian](viewing-your-pokemon.md#galarian)
7. [--hextuple](viewing-your-pokemon.md#hextuple-less-than-integer-greater-than)
8. [--hpiv](viewing-your-pokemon.md#hpiv-less-than-integer-greater-than)
9. [--iv](viewing-your-pokemon.md#iv-less-than-integer-decimal-greater-than)
10. [--legendary](viewing-your-pokemon.md#legendary)
11. [--level](viewing-your-pokemon.md#level-less-than-integer-greater-than)
12. [--limit](viewing-your-pokemon.md#limit-less-than-integer-greater-than)
13. [--mega](viewing-your-pokemon.md#mega)
14. [--mythical](viewing-your-pokemon.md#mythical)
15. [--name](viewing-your-pokemon.md#name-less-than-name-greater-than)
16. [--nickname](viewing-your-pokemon.md#nickname-less-than-nickname-greater-than)
17. [--pentuple](viewing-your-pokemon.md#pentuple-less-than-integer-greater-than)
18. [--quadruple](viewing-your-pokemon.md#quadruple-less-than-integer-greater-than)
19. [--region](viewing-your-pokemon.md#region-less-than-region-greater-than)
20. [--shiny](viewing-your-pokemon.md#shiny)
21. [--skip](viewing-your-pokemon.md#skip-less-than-integer-greater-than)
22. [--spatkiv](viewing-your-pokemon.md#spatkiv-less-than-integer-greater-than)
23. [--spdefiv](viewing-your-pokemon.md#spdefiv-less-than-integer-greater-than)
24. [--spdiv](viewing-your-pokemon.md#spdiv-less-than-integer-greater-than)
25. [--triple](viewing-your-pokemon.md#triple-less-than-integer-greater-than)
26. [--type](viewing-your-pokemon.md#type-less-than-type-greater-than)
27. [--ub](viewing-your-pokemon.md#ub)

</details>
