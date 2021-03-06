---
description: >-
  Filters usable in various commands such as pokemon, market search, auction
  search, etc to narrow down your search to find the exact pokémon you're
  looking for.
---

# Search Filters

{% hint style="warning" %}
This site is an early **work in progress**. Many pages may be missing or incomplete. Please let us know at [discord.gg/poketwo](https://discord.gg/poketwo) if you would like to help write or improve a page.
{% endhint %}

### Contents

1. [Contents](search-filters.md#contents)
2. [Introduction](search-filters.md#introduction)
3. [Supported commands](search-filters.md#supported-commands)
4. [Naming system of filters](search-filters.md#naming-system-of-filters)
5. [Usage of filters](search-filters.md#usage-of-filters)

<details>

<summary>6. <a href="search-filters.md#list-of-filters">List of filters</a></summary>

1. [--alolan](search-filters.md#alolan)
2. [--atkiv](search-filters.md#atkiv-less-than-integer-greater-than)
3. [--bids](search-filters.md#bids)
4. [--caught](search-filters.md#caught)
5. [--defiv](search-filters.md#defiv-less-than-integer-greater-than)
6. [--embedcolor](search-filters.md#embedcolor)
7. [--ends](search-filters.md#ends-less-than-duration-greater-than)
8. [--event](search-filters.md#event)
9. [--favorite](search-filters.md#favorite)
10. [--galarian](search-filters.md#galarian)
11. [--hextuple](search-filters.md#hextuple-less-than-integer-greater-than)
12. [--hpiv](search-filters.md#hpiv-less-than-integer-greater-than)
13. [--iv](search-filters.md#iv-less-than-integer-decimal-greater-than)
14. [--legendary](search-filters.md#legendary)
15. [--level](search-filters.md#level-less-than-integer-greater-than)
16. [--limit](search-filters.md#limit-less-than-integer-greater-than)
17. [--mega](search-filters.md#mega)
18. [--mine](search-filters.md#mine)
19. [--mythical](search-filters.md#mythical)
20. [--name](search-filters.md#name-less-than-name-greater-than)
21. [--nickname](search-filters.md#nickname-less-than-nickname-greater-than)
22. [--order](search-filters.md#order-less-than-order-greater-than)
23. [--ordera](search-filters.md#ordera)
24. [--orderd](search-filters.md#orderd)
25. [--pentuple](search-filters.md#pentuple-less-than-integer-greater-than)
26. [--quadruple](search-filters.md#quadruple-less-than-integer-greater-than)
27. [--region](search-filters.md#region-less-than-region-greater-than)
28. [--shiny](search-filters.md#shiny)
29. [--skip](search-filters.md#skip-less-than-integer-greater-than)
30. [--spatkiv](search-filters.md#spatkiv-less-than-integer-greater-than)
31. [--spdefiv](search-filters.md#spdefiv-less-than-integer-greater-than)
32. [--spdiv](search-filters.md#spdiv-less-than-integer-greater-than)
33. [--triple](search-filters.md#triple-less-than-integer-greater-than)
34. [--type](search-filters.md#type-less-than-type-greater-than)
35. [--ub](search-filters.md#ub)
36. [--uncaught](search-filters.md#uncaught)

</details>

{% tabs %}
{% tab title="Stat Filters" %}
**Level:** [--level](search-filters.md#level-less-than-integer-greater-than)

**Name:** [--name](search-filters.md#name-less-than-name-greater-than)

**Nickname:** [--nickname](search-filters.md#nickname-less-than-nickname-greater-than)

**Favorite:** [--favorite](search-filters.md#favorite)

**Rarity:**

* **Mythical:** [--mythical](search-filters.md#mythical)
* **Legendary:** [--legendary](search-filters.md#legendary)
* **Ultra Beast:** [--ub](search-filters.md#ub)

**Type:** [--type](search-filters.md#type-less-than-type-greater-than)

**Region:** [--region](search-filters.md#region-less-than-region-greater-than)

**Embed Color:** [--embedcolor](search-filters.md#embedcolor)
{% endtab %}

{% tab title="IV Filters" %}
**HP:** [--hpiv](search-filters.md#hpiv-less-than-integer-greater-than)

**Attack:** [--atkiv](search-filters.md#atkiv-less-than-integer-greater-than)

**Defense:** [--defiv](search-filters.md#defiv-less-than-integer-greater-than)

**Sp. Atk:** [--spatkiv](search-filters.md#spatkiv)

**Sp. Def:** [--spdefiv](search-filters.md#spdefiv-less-than-integer-greater-than)

**Speed:** [--spdiv](search-filters.md#spdiv-less-than-integer-greater-than)

**Total IV:** [--iv](search-filters.md#iv-less-than-integer-decimal-greater-than)

**Triple:** [--triple](search-filters.md#triple-less-than-integer-greater-than)

**Quadruple:** [--quadruple](search-filters.md#quadruple-less-than-integer-greater-than)

**Pentuple:** [--pentuple](search-filters.md#pentuple-less-than-integer-greater-than)

**Hextuple:** [--hextuple](search-filters.md#hextuple-less-than-integer-greater-than)
{% endtab %}

{% tab title="Forms" %}
**Shiny:** [--shiny](search-filters.md#shiny)

**Event:** [--event](search-filters.md#event)

**Mega:** [--mega](search-filters.md#mega)

**Alolan:** [--alolan](search-filters.md#alolan)

**Galarian:** [--galarian](search-filters.md#galarian)
{% endtab %}

{% tab title="Miscellaneous" %}
**Limit:** [--limit](search-filters.md#limit-less-than-integer-greater-than)

**Skip:** [--skip](search-filters.md#skip-less-than-integer-greater-than)



\[**auction search** only]

**Bids:** [--bids](search-filters.md#bids)

**Ends:** [--ends](search-filters.md#ends-less-than-duration-greater-than)



\[**auction search** and **market search** only]

**Order:** [--order](search-filters.md#order-less-than-order-greater-than)

**Mine:** [--mine](search-filters.md#mine)

&#x20;

\[**pokedex** only]

**Caught:** [--caught](search-filters.md#caught)

**Uncaught:** [--uncaught](search-filters.md#uncaught)

**Ascending Order by Caught:** [--ordera](search-filters.md#ordera)

**Descending Order by Caught:** [--orderd](search-filters.md#orderd)
{% endtab %}
{% endtabs %}

### Introduction

Filters are special keywords that begin with `--` which can be used in [certain commands](search-filters.md#supported-commands) to filter the Pokémon returned (whether it is a search command or otherwise).

For example, if the user wishes to add all owned Ralts to a trade, this can be achieved by using the [`--name`](search-filters.md#name-less-than-name-greater-than) filter in the `trade addall` command. This article documents all available filters, their functionality, examples, and more.&#x20;

### Supported commands

Commands that support filters and the filters they support. Check out the full list of filters [**here**](search-filters.md#contents).

<details>

<summary>1. <a href="../economy/auctions.md">auction search</a> (p!a s)</summary>

1. [--alolan](search-filters.md#alolan)
2. [--atkiv](search-filters.md#atkiv-less-than-integer-greater-than)
3. [--bids](search-filters.md#bids)
4. [--defiv](search-filters.md#defiv-less-than-integer-greater-than)
5. [--embedcolor](search-filters.md#embedcolor)
6. [--ends](search-filters.md#ends-less-than-duration-greater-than)
7. [--event](search-filters.md#event)
8. [--galarian](search-filters.md#galarian)
9. [--hextuple](search-filters.md#hextuple-less-than-integer-greater-than)
10. [--hpiv](search-filters.md#hpiv-less-than-integer-greater-than)
11. [--iv](search-filters.md#iv-less-than-integer-decimal-greater-than)
12. [--legendary](search-filters.md#legendary)
13. [--level](search-filters.md#level-less-than-integer-greater-than)
14. [--limit](search-filters.md#limit-less-than-integer-greater-than)
15. [--mega](search-filters.md#mega)
16. [--mine](search-filters.md#mine)
17. [--mythical](search-filters.md#mythical)
18. [--name](search-filters.md#name-less-than-name-greater-than)
19. [--order](search-filters.md#order-less-than-order-greater-than)
20. [--pentuple](search-filters.md#pentuple-less-than-integer-greater-than)
21. [--quadruple](search-filters.md#quadruple-less-than-integer-greater-than)
22. [--region](search-filters.md#region-less-than-region-greater-than)
23. [--shiny](search-filters.md#shiny)
24. [--skip](search-filters.md#skip-less-than-integer-greater-than)
25. [--spatkiv](search-filters.md#spatkiv-less-than-integer-greater-than)
26. [--spdefiv](search-filters.md#spdefiv-less-than-integer-greater-than)
27. [--spdiv](search-filters.md#spdiv-less-than-integer-greater-than)
28. [--triple](search-filters.md#triple-less-than-integer-greater-than)
29. [--type](search-filters.md#type-less-than-type-greater-than)
30. [--ub](search-filters.md#ub)

</details>

<details>

<summary>2. favoriteall (p!fa)</summary>

1. [--alolan](search-filters.md#alolan)
2. [--atkiv](search-filters.md#atkiv-less-than-integer-greater-than)
3. [--defiv](search-filters.md#defiv-less-than-integer-greater-than)
4. [--embedcolor](search-filters.md#embedcolor)
5. [--event](search-filters.md#event)
6. [--galarian](search-filters.md#galarian)
7. [--hextuple](search-filters.md#hextuple-less-than-integer-greater-than)
8. [--hpiv](search-filters.md#hpiv-less-than-integer-greater-than)
9. [--iv](search-filters.md#iv-less-than-integer-decimal-greater-than)
10. [--legendary](search-filters.md#legendary)
11. [--level](search-filters.md#level-less-than-integer-greater-than)
12. [--limit](search-filters.md#limit-less-than-integer-greater-than)
13. [--mega](search-filters.md#mega)
14. [--mythical](search-filters.md#mythical)
15. [--name](search-filters.md#name-less-than-name-greater-than)
16. [--nickname](search-filters.md#nickname-less-than-nickname-greater-than)
17. [--pentuple](search-filters.md#pentuple-less-than-integer-greater-than)
18. [--quadruple](search-filters.md#quadruple-less-than-integer-greater-than)
19. [--region](search-filters.md#region-less-than-region-greater-than)
20. [--shiny](search-filters.md#shiny)
21. [--skip](search-filters.md#skip-less-than-integer-greater-than)
22. [--spatkiv](search-filters.md#spatkiv-less-than-integer-greater-than)
23. [--spdefiv](search-filters.md#spdefiv-less-than-integer-greater-than)
24. [--spdiv](search-filters.md#spdiv-less-than-integer-greater-than)
25. [--triple](search-filters.md#triple-less-than-integer-greater-than)
26. [--type](search-filters.md#type-less-than-type-greater-than)
27. [--ub](search-filters.md#ub)

</details>

<details>

<summary>3. <a href="../economy/the-market.md">market search</a> (p!m s)</summary>

1. [--alolan](search-filters.md#alolan)
2. [--atkiv](search-filters.md#atkiv-less-than-integer-greater-than)
3. [--defiv](search-filters.md#defiv-less-than-integer-greater-than)
4. [--embedcolor](search-filters.md#embedcolor)
5. [--event](search-filters.md#event)
6. [--galarian](search-filters.md#galarian)
7. [--hextuple](search-filters.md#hextuple-less-than-integer-greater-than)
8. [--hpiv](search-filters.md#hpiv-less-than-integer-greater-than)
9. [--iv](search-filters.md#iv-less-than-integer-decimal-greater-than)
10. [--legendary](search-filters.md#legendary)
11. [--level](search-filters.md#level-less-than-integer-greater-than)
12. [--limit](search-filters.md#limit-less-than-integer-greater-than)
13. [--mega](search-filters.md#mega)
14. [--mine](search-filters.md#mine)
15. [--mythical](search-filters.md#mythical)
16. [--name](search-filters.md#name-less-than-name-greater-than)
17. [--order](search-filters.md#order-less-than-order-greater-than)
18. [--pentuple](search-filters.md#pentuple-less-than-integer-greater-than)
19. [--quadruple](search-filters.md#quadruple-less-than-integer-greater-than)
20. [--region](search-filters.md#region-less-than-region-greater-than)
21. [--shiny](search-filters.md#shiny)
22. [--skip](search-filters.md#skip-less-than-integer-greater-than)
23. [--spatkiv](search-filters.md#spatkiv-less-than-integer-greater-than)
24. [--spdefiv](search-filters.md#spdefiv-less-than-integer-greater-than)
25. [--spdiv](search-filters.md#spdiv-less-than-integer-greater-than)
26. [--triple](search-filters.md#triple-less-than-integer-greater-than)
27. [--type](search-filters.md#type-less-than-type-greater-than)
28. [--ub](search-filters.md#ub)

</details>

<details>

<summary>4. nickall (p!na)</summary>

1. [--alolan](search-filters.md#alolan)
2. [--atkiv](search-filters.md#atkiv-less-than-integer-greater-than)
3. [--defiv](search-filters.md#defiv-less-than-integer-greater-than)
4. [--embedcolor](search-filters.md#embedcolor)
5. [--event](search-filters.md#event)
6. [--favorite](search-filters.md#favorite)
7. [--galarian](search-filters.md#galarian)
8. [--hextuple](search-filters.md#hextuple-less-than-integer-greater-than)
9. [--hpiv](search-filters.md#hpiv-less-than-integer-greater-than)
10. [--iv](search-filters.md#iv-less-than-integer-decimal-greater-than)
11. [--legendary](search-filters.md#legendary)
12. [--level](search-filters.md#level-less-than-integer-greater-than)
13. [--limit](search-filters.md#limit-less-than-integer-greater-than)
14. [--mega](search-filters.md#mega)
15. [--mythical](search-filters.md#mythical)
16. [--name](search-filters.md#name-less-than-name-greater-than)
17. [--nickname](search-filters.md#nickname-less-than-nickname-greater-than)
18. [--pentuple](search-filters.md#pentuple-less-than-integer-greater-than)
19. [--quadruple](search-filters.md#quadruple-less-than-integer-greater-than)
20. [--region](search-filters.md#region-less-than-region-greater-than)
21. [--shiny](search-filters.md#shiny)
22. [--skip](search-filters.md#skip-less-than-integer-greater-than)
23. [--spatkiv](search-filters.md#spatkiv-less-than-integer-greater-than)
24. [--spdefiv](search-filters.md#spdefiv-less-than-integer-greater-than)
25. [--spdiv](search-filters.md#spdiv-less-than-integer-greater-than)
26. [--triple](search-filters.md#triple-less-than-integer-greater-than)
27. [--type](search-filters.md#type-less-than-type-greater-than)
28. [--ub](search-filters.md#ub)

</details>

<details>

<summary>5. pokedex (p!d)</summary>

1. [--caught](search-filters.md#caught)
2. [--legendary](search-filters.md#legendary)
3. [--mythical](search-filters.md#mythical)
4. [--ordera](search-filters.md#ordera)
5. [--orderd](search-filters.md#orderd)
6. [--region](search-filters.md#region-less-than-region-greater-than)
7. [--type](search-filters.md#type-less-than-type-greater-than)
8. [--ub](https://app.gitbook.com/o/v6Hu8g8ZTlGEzK8GZO2X/s/V8TpJwvEXrp8bgi2enWi/\~/changes/Jsti1rFh7TzR0xPjJrG8/intermediate-topics/search-filters#ub)
9. [--uncaught](search-filters.md#uncaught)

</details>

<details>

<summary>6. pokemon (p!p)</summary>

1. [--alolan](search-filters.md#alolan)
2. [--atkiv](search-filters.md#atkiv-less-than-integer-greater-than)
3. [--defiv](search-filters.md#defiv-less-than-integer-greater-than)
4. [--embedcolor](search-filters.md#embedcolor)
5. [--event](search-filters.md#event)
6. [--favorite](search-filters.md#favorite)
7. [--galarian](search-filters.md#galarian)
8. [--hextuple](search-filters.md#hextuple-less-than-integer-greater-than)
9. [--hpiv](search-filters.md#hpiv-less-than-integer-greater-than)
10. [--iv](search-filters.md#iv-less-than-integer-decimal-greater-than)
11. [--legendary](search-filters.md#legendary)
12. [--level](search-filters.md#level-less-than-integer-greater-than)
13. [--limit](search-filters.md#limit-less-than-integer-greater-than)
14. [--mega](search-filters.md#mega)
15. [--mythical](search-filters.md#mythical)
16. [--name](search-filters.md#name-less-than-name-greater-than)
17. [--nickname](search-filters.md#nickname-less-than-nickname-greater-than)
18. [--pentuple](search-filters.md#pentuple-less-than-integer-greater-than)
19. [--quadruple](search-filters.md#quadruple-less-than-integer-greater-than)
20. [--region](search-filters.md#region-less-than-region-greater-than)
21. [--shiny](search-filters.md#shiny)
22. [--skip](search-filters.md#skip-less-than-integer-greater-than)
23. [--spatkiv](search-filters.md#spatkiv-less-than-integer-greater-than)
24. [--spdefiv](search-filters.md#spdefiv-less-than-integer-greater-than)
25. [--spdiv](search-filters.md#spdiv-less-than-integer-greater-than)
26. [--triple](search-filters.md#triple-less-than-integer-greater-than)
27. [--type](search-filters.md#type-less-than-type-greater-than)
28. [--ub](search-filters.md#ub)

</details>

<details>

<summary>7. releaseall (p!ra)</summary>

1. [--alolan](search-filters.md#alolan)
2. [--atkiv](search-filters.md#atkiv-less-than-integer-greater-than)
3. [--defiv](search-filters.md#defiv-less-than-integer-greater-than)
4. [--embedcolor](search-filters.md#embedcolor)
5. [--event](search-filters.md#event)
6. [--galarian](search-filters.md#galarian)
7. [--hextuple](search-filters.md#hextuple-less-than-integer-greater-than)
8. [--hpiv](search-filters.md#hpiv-less-than-integer-greater-than)
9. [--iv](search-filters.md#iv-less-than-integer-decimal-greater-than)
10. [--legendary](search-filters.md#legendary)
11. [--level](search-filters.md#level-less-than-integer-greater-than)
12. [--limit](search-filters.md#limit-less-than-integer-greater-than)
13. [--mega](search-filters.md#mega)
14. [--mythical](search-filters.md#mythical)
15. [--name](search-filters.md#name-less-than-name-greater-than)
16. [--nickname](search-filters.md#nickname-less-than-nickname-greater-than)
17. [--pentuple](search-filters.md#pentuple-less-than-integer-greater-than)
18. [--quadruple](search-filters.md#quadruple-less-than-integer-greater-than)
19. [--region](search-filters.md#region-less-than-region-greater-than)
20. [--shiny](search-filters.md#shiny)
21. [--skip](search-filters.md#skip-less-than-integer-greater-than)
22. [--spatkiv](search-filters.md#spatkiv-less-than-integer-greater-than)
23. [--spdefiv](search-filters.md#spdefiv-less-than-integer-greater-than)
24. [--spdiv](search-filters.md#spdiv-less-than-integer-greater-than)
25. [--triple](search-filters.md#triple-less-than-integer-greater-than)
26. [--type](search-filters.md#type-less-than-type-greater-than)
27. [--ub](search-filters.md#ub)

</details>

<details>

<summary>8. <a href="../economy/trading.md">trade addall</a> (p!t aa)</summary>

1. [--alolan](search-filters.md#alolan)
2. [--atkiv](search-filters.md#atkiv-less-than-integer-greater-than)
3. [--defiv](search-filters.md#defiv-less-than-integer-greater-than)
4. [--embedcolor](search-filters.md#embedcolor)
5. [--event](search-filters.md#event)
6. [--galarian](search-filters.md#galarian)
7. [--hextuple](search-filters.md#hextuple-less-than-integer-greater-than)
8. [--hpiv](search-filters.md#hpiv-less-than-integer-greater-than)
9. [--iv](search-filters.md#iv-less-than-integer-decimal-greater-than)
10. [--legendary](search-filters.md#legendary)
11. [--level](search-filters.md#level-less-than-integer-greater-than)
12. [--limit](search-filters.md#limit-less-than-integer-greater-than)
13. [--mega](search-filters.md#mega)
14. [--mythical](search-filters.md#mythical)
15. [--name](search-filters.md#name-less-than-name-greater-than)
16. [--nickname](search-filters.md#nickname-less-than-nickname-greater-than)
17. [--pentuple](search-filters.md#pentuple-less-than-integer-greater-than)
18. [--quadruple](search-filters.md#quadruple-less-than-integer-greater-than)
19. [--region](search-filters.md#region-less-than-region-greater-than)
20. [--shiny](search-filters.md#shiny)
21. [--skip](search-filters.md#skip-less-than-integer-greater-than)
22. [--spatkiv](search-filters.md#spatkiv-less-than-integer-greater-than)
23. [--spdefiv](search-filters.md#spdefiv-less-than-integer-greater-than)
24. [--spdiv](search-filters.md#spdiv-less-than-integer-greater-than)
25. [--triple](search-filters.md#triple-less-than-integer-greater-than)
26. [--type](search-filters.md#type-less-than-type-greater-than)
27. [--ub](search-filters.md#ub)

</details>

### Naming system of filters

Filters are named according to their general purpose. E.g. the `--name` filter searches by the **name** of pokémon. _They are **case-sensitive**, meaning that, e.g. `--Name` will not work; It must be all lowercase._

{% hint style="info" %}
Any abbreviation of a filter can also be used to access that filter. E.g. the `--name` filter can be accessed using either of:

* `--n`
* `--na`
* `--nam`
* `--name`

<mark style="color:yellow;">Note:</mark> The bot will raise an <mark style="color:red;">**ambiguous option**</mark> error if two or more filters coincide with the same abbreviation. E.g. `--m` can refer to both `--mega` and `--mythical`, thus requiring for more specificity. However, there are some exceptions:&#x20;

1. `--n` is hardcoded to refer to `--name`
2. `--t` to `--type`
3. `--r` to `--region`
{% endhint %}

### Usage of filters

Filters can be used alongside each other and for further filtration, unless they serve the same general purpose. E.g.

![Here, the filters --name and --nickname are used to show pokémon with the name Ralts and nickname Example](../.gitbook/assets/IMG\_20220124\_150155.jpg)

Some filters can also be used more than once in a command to filter with a wider range of criteria of the same kind. E.g.

![Here, the --type filter is used twice, once with Psychic and once with Grass to search for pokémon that are of the type Psychic or Grass or both. ](../.gitbook/assets/IMG\_20220130\_183721.jpg)

### List of filters

All the filters in alphabetical order.

[Index](search-filters.md#contents)

> #### --alolan

> Filter for regional variant of pokémon that come from the Alola region and identify as alolan forms.

<details>

<summary>Commonly used aliases</summary>

\--alolan

\--alo

\--al

</details>

<details>

<summary>Commands</summary>

<mark style="color:green;">auction search</mark>

<mark style="color:green;">favoriteall</mark>

<mark style="color:green;">market search</mark>

<mark style="color:green;">nickall</mark>

<mark style="color:red;">pokedex</mark>

<mark style="color:green;">pokemon</mark>

<mark style="color:green;">releaseall</mark>

<mark style="color:green;">trade addall</mark>&#x20;

<mark style="color:green;">unfavoriteall</mark>

</details>

<details>

<summary>Pokémon</summary>

* [Alolan Diglett](https://pokemondb.net/pokedex/diglett)
* [Alolan Dugtrio](https://pokemondb.net/pokedex/dugtrio)
* [Alolan Exeggutor](https://pokemondb.net/pokedex/exeggutor)
* [Alolan Geodude](https://pokemondb.net/pokedex/geodude)
* [Alolan Graveler](https://pokemondb.net/pokedex/graveler)
* [Alolan Golem](https://pokemondb.net/pokedex/golem)
* [Alolan Grimer](https://pokemondb.net/pokedex/grimer)
* [Alolan Muk ](https://pokemondb.net/pokedex/muk)
* [Alolan Marowak](https://pokemondb.net/pokedex/marowak)
* [Alolan Meowth](https://pokemondb.net/pokedex/meowth)
* [Alolan Persian](https://pokemondb.net/pokedex/persian)
* [Alolan Raichu](https://pokemondb.net/pokedex/raichu)
* [Alolan Rattata](https://pokemondb.net/pokedex/rattata)
* [Alolan Raticate](https://pokemondb.net/pokedex/raticate)
* [Alolan Sandshrew](https://pokemondb.net/pokedex/sandshrew)
* [Alolan Sandslash](https://pokemondb.net/pokedex/sandslash)
* [Alolan Vulpix](https://pokemondb.net/pokedex/vulpix)
* [Alolan Ninetales](https://pokemondb.net/pokedex/ninetales)

</details>

#### --atkiv `<integer>`

> Filter for pokémon with the specified Attack/ATK IV. You can use `>`, `<` or `=` to show greater than, less than or equal to the specified integer.

<details>

<summary>Commonly used aliases</summary>

\--atkiv

\--atk

\--at

</details>

<details>

<summary>Commands</summary>

<mark style="color:green;">auction search</mark>

<mark style="color:green;">favoriteall</mark>

<mark style="color:green;">market search</mark>

<mark style="color:green;">nickall</mark>

<mark style="color:red;">pokedex</mark>

<mark style="color:green;">pokemon</mark>

<mark style="color:green;">releaseall</mark>

<mark style="color:green;">trade addall</mark>&#x20;

<mark style="color:green;">unfavoriteall</mark>

</details>

<details>

<summary>Examples</summary>

Pokémon with ATK IV greater than 20

```
p!pokemon --atkiv > 20
```

Pokémon with ATK IV less than 30

```
p!pokemon --atkiv < 30
```

Pokémon with ATK IV greater than 20 but less than 30

```
p!pokemon --atkiv > 20 --atkiv < 30
```

Pokémon with ATK IV equal to 25

```
p!pokemon --atkiv 25
p!pokemon --atkiv = 25
```

</details>

#### --bids

> Filter for auctions that you hold the current bid on.&#x20;

<details>

<summary>Commonly used aliases</summary>

\--bids

\--bid

\--b

</details>

<details>

<summary>Commands</summary>

<mark style="color:green;">auction search</mark>

<mark style="color:red;">favoriteall</mark>

<mark style="color:red;">market search</mark>

<mark style="color:red;">nickall</mark>

<mark style="color:red;">pokedex</mark>

<mark style="color:red;">pokemon</mark>

<mark style="color:red;">releaseall</mark>

<mark style="color:red;">trade addall</mark> <mark style="color:red;"></mark><mark style="color:red;"><mark style="color:green;"><mark style="color:green;"></mark>&#x20;

<mark style="color:red;">unfavoriteall</mark>

</details>

#### --caught

> Filter for showing pokémon that you have caught atleast once in the **pokedex** command.

<details>

<summary>Commonly used aliases</summary>

\--caught

\--cau

</details>

<details>

<summary>Commands</summary>

<mark style="color:red;">auction search</mark>

<mark style="color:red;">favoriteall</mark>

<mark style="color:red;">market search</mark>

<mark style="color:red;">nickall</mark>

<mark style="color:green;">pokedex</mark>

<mark style="color:red;">pokemon</mark>

<mark style="color:red;">releaseall</mark>

<mark style="color:red;">trade addall</mark> <mark style="color:red;"></mark><mark style="color:red;"><mark style="color:green;"><mark style="color:green;"></mark>&#x20;

<mark style="color:red;">unfavoriteall</mark>

</details>

#### --defiv `<integer>`

> Filter for pokémon with specified Defence/DEF IV. You can use `>`, `<` or `=` to show greater than, less than or equal to the specified integer.

<details>

<summary>Commonly used aliases</summary>

\--defiv

\--def

</details>

<details>

<summary>Commands</summary>

<mark style="color:green;">auction search</mark>

<mark style="color:green;">favoriteall</mark>

<mark style="color:green;">market search</mark>

<mark style="color:green;">nickall</mark>

<mark style="color:red;">pokedex</mark>

<mark style="color:green;">pokemon</mark>

<mark style="color:green;">releaseall</mark>

<mark style="color:green;">trade addall</mark>&#x20;

<mark style="color:green;">unfavoriteall</mark>

</details>

<details>

<summary>Examples</summary>



Pokémon with DEF IV greater than 20

```
p!pokemon --defiv > 20
```

Pokémon with DEF IV less than 30

```
p!pokemon --defiv < 30
```

Pokémon with DEF IV greater than 20 but less than 30

```
p!pokemon --defiv > 20 --defiv < 30
```

Pokémon with DEF IV equal to 25

```
p!pokemon --defiv 25
p!pokemon --defiv = 25
```

</details>

#### --embedcolor

> Filter for pokémon that have an [embedcolor](https://cdn.discordapp.com/attachments/850044183188078633/935513947702960138/IMG\_20220125\_180818.jpg) equipped.

<details>

<summary>Commonly used aliases</summary>

\--embed

\--ec

</details>

<details>

<summary>Commands</summary>

<mark style="color:green;">auction search</mark>

<mark style="color:green;">favoriteall</mark>

<mark style="color:green;">market search</mark>

<mark style="color:green;">nickall</mark>

<mark style="color:red;">pokedex</mark>

<mark style="color:green;">pokemon</mark>

<mark style="color:green;">releaseall</mark>

<mark style="color:green;">trade addall</mark>&#x20;

<mark style="color:green;">unfavoriteall</mark>

</details>

#### --ends `<duration>`

> Filter for auctions ending within `<duration>`. `<duraton>` requires a number (integer or decimal) and a time unit.&#x20;
>
> * `ms` for milliseconds
> * `s` for seconds
> * `m` for minutes
> * `h` for hours
> * `d` for days
> * `w` for weeks
>
> E.g. `1h`, `1hour`, `2d`

![Here, p!auction search --name Ralts --ends 1hour is searching for all current auctions that are of the pokémon Ralts and ends before 1 hour. ](../.gitbook/assets/Picsart\_22-01-30\_19-56-55-408.jpg)

![Here, p!auction search --name Ralts --ends 30m is searching for all current auctions that are of the pokémon Ralts and ends before 30 minutes. ](../.gitbook/assets/Picsart\_22-01-30\_19-58-18-800.jpg)

<details>

<summary>Commands</summary>

<mark style="color:green;">auction search</mark>

<mark style="color:red;">favoriteall</mark>

<mark style="color:red;">market search</mark>

<mark style="color:red;">nickall</mark>

<mark style="color:red;">pokedex</mark>

<mark style="color:red;">pokemon</mark>

<mark style="color:red;">releaseall</mark>

<mark style="color:red;">trade addall</mark> <mark style="color:red;"></mark><mark style="color:red;"><mark style="color:green;"><mark style="color:green;"></mark>&#x20;

<mark style="color:red;">unfavoriteall</mark>

</details>

#### --event

> Filter for pokémon that were obtainable through certain pokétwo events; that have the rarity **Event** shown in the **pokedex** command.

<details>

<summary>Commonly used aliases</summary>

\--event

\--ev

</details>

<details>

<summary>Commands</summary>

<mark style="color:green;">auction search</mark>

<mark style="color:green;">favoriteall</mark>

<mark style="color:green;">market search</mark>

<mark style="color:green;">nickall</mark>

<mark style="color:red;">pokedex</mark>

<mark style="color:green;">pokemon</mark>

<mark style="color:green;">releaseall</mark>

<mark style="color:green;">trade addall</mark>&#x20;

<mark style="color:green;">unfavoriteall</mark>

</details>

{% content-ref url="events.md" %}
[events.md](events.md)
{% endcontent-ref %}

#### --favorite

> Filter for viewing all of your favorited pokémon. Favorited pokémon have a "♥️" next to their name.
>
> {% hint style="info" %}
> You can favorite/unfavorite pokémon using the `favorite`/`unfavorite` or `favoriteall`/`unfavoriteall` commands.
> {% endhint %}

<details>

<summary>Commonly used aliases</summary>

\--fav

</details>

<details>

<summary>Commands</summary>

<mark style="color:red;">auction search</mark>

<mark style="color:red;">favoriteall</mark>

<mark style="color:red;">market search</mark>

<mark style="color:green;">nickall</mark>

<mark style="color:red;">pokedex</mark>

<mark style="color:green;">pokemon</mark>

<mark style="color:red;">releaseall</mark>

<mark style="color:red;">trade addall</mark> <mark style="color:green;"></mark>&#x20;

<mark style="color:green;">unfavoriteall</mark>

</details>

#### --galarian

> Filter for regional variant of pokémon that come from the Galar region and identify as galarian forms.

<details>

<summary>Commonly used aliases</summary>

\--galar

\--gal

</details>

<details>

<summary>Comnands</summary>

<mark style="color:green;">auction search</mark>

<mark style="color:green;">favoriteall</mark>

<mark style="color:green;">market search</mark>

<mark style="color:green;">nickall</mark>

<mark style="color:red;">pokedex</mark>

<mark style="color:green;">pokemon</mark>

<mark style="color:green;">releaseall</mark>

<mark style="color:green;">trade addall</mark>&#x20;

<mark style="color:green;">unfavoriteall</mark>

</details>

<details>

<summary>Pokémon</summary>

* [Galarian Articuno](https://pokemondb.net/pokedex/articuno)
* [Galarian Corsola](https://pokemondb.net/pokedex/corsola)
* [Galarian Darumaka](https://pokemondb.net/pokedex/darumaka)
* [Galarian Farfetch'd](https://pokemondb.net/pokedex/farfetchd)
* [Galarian Linoone](https://pokemondb.net/pokedex/linoone)
* [Galarian Meowth](https://pokemondb.net/pokedex/meowth)
* [Galarian Moltres](https://pokemondb.net/pokedex/moltres)
* [Galarian Mr. Mime](https://pokemondb.net/pokedex/mr-mime)
* [Galarian Ponyta](https://pokemondb.net/pokedex/ponyta)
* [Galarian Rapidash](https://pokemondb.net/pokedex/rapidash)
* [Galarian Slowbro](https://pokemondb.net/pokedex/slowbro)
* [Galarian Slowking](https://pokemondb.net/pokedex/slowking)
* [Galarian Slowpoke](https://pokemondb.net/pokedex/slowpoke)
* [Galarian Standard Darmanitan](https://pokemondb.net/pokedex/darmanitan)
* [Galarian Stunfisk](https://pokemondb.net/pokedex/stunfisk)
* [Galarian Weezing](https://pokemondb.net/pokedex/weezing)
* [Galarian Yamask](https://pokemondb.net/pokedex/yamask)
* [Galarian Zapdos](https://pokemondb.net/pokedex/zapdos)
* [Galarian Zigzagoon](https://pokemondb.net/pokedex/zigzagoon)

</details>

#### --hextuple  `<integer>`

> Filter for pokémon that have 6 stat IVs that are equal to `<integer>`.  To elaborate, for a pokémon to match the criteria for this filter, its stat IVs, namely `HP`, `ATK`, `DEF`, `SPATK`, `SPDEF` and `SPD` IVs all need to be the same, equal to `<integer>`.

![E.g. this pokémon would match the criteria for p!pokemon --hextuple 31 because it has 6 equal stat IVs that are 31.](../.gitbook/assets/IMG\_20220125\_220828.jpg)

<details>

<summary>Commonly used aliases</summary>

\--six

\--hex

\--hexa

\--sextuple

</details>

<details>

<summary>Commands</summary>

<mark style="color:green;">auction search</mark>

<mark style="color:green;">favoriteall</mark>

<mark style="color:green;">market search</mark>

<mark style="color:green;">nickall</mark>

<mark style="color:red;">pokedex</mark>

<mark style="color:green;">pokemon</mark>

<mark style="color:green;">releaseall</mark>

<mark style="color:green;">trade addall</mark>&#x20;

<mark style="color:green;">unfavoriteall</mark>

</details>

#### --hpiv `<integer>`

> Filter for pokémon with the specified HP IV. You can use `>`, `<` or `=` to show greater than, less than or equal to the specified integer.

<details>

<summary>Commonly used aliases</summary>

\--hp

</details>

<details>

<summary>Commands</summary>

<mark style="color:green;">auction search</mark>

<mark style="color:green;">favoriteall</mark>

<mark style="color:green;">market search</mark>

<mark style="color:green;">nickall</mark>

<mark style="color:red;">pokedex</mark>

<mark style="color:green;">pokemon</mark>

<mark style="color:green;">releaseall</mark>

<mark style="color:green;">trade addall</mark>&#x20;

<mark style="color:green;">unfavoriteall</mark>

</details>

<details>

<summary>Examples</summary>

Pokémon with HP IV greater than 20

```
p!pokemon --hpiv > 20
```

Pokémon with HP IV less than 30

```
p!pokemon --hpiv < 30
```

Pokémon with HP IV greater than 20 but less than 30

```
p!pokemon --hpiv > 20 --hpiv < 30
```

Pokémon with HP IV equal to 25

```
p!pokemon --hpiv 25
p!pokemon --hpiv = 25
```

</details>

#### --iv `<integer/decimal>`

> Filter for pokémon with the specified Total IV. You can use `>`, `<` or `=` to show greater than, less than or equal to the specified integer or decimal. Typing an integer will show all of its decimal variants. E.g. `--iv 67` will show IVs `67.20%` and `67.74%` (all possible 67<68 IVs).

<details>

<summary>Commands</summary>

<mark style="color:green;">auction search</mark>

<mark style="color:green;">favoriteall</mark>

<mark style="color:green;">market search</mark>

<mark style="color:green;">nickall</mark>

<mark style="color:red;">pokedex</mark>

<mark style="color:green;">pokemon</mark>

<mark style="color:green;">releaseall</mark>

<mark style="color:green;">trade addall</mark>&#x20;

<mark style="color:green;">unfavoriteall</mark>

</details>

<details>

<summary>Examples</summary>

Pokémon with Total IV greater than 20

```
p!pokemon --iv > 20
```

Pokémon with Total IV less than 30

```
p!pokemon --iv < 30
```

Pokémon with Total IV greater than 20 but less than 30

```
p!pokemon --iv > 20 --iv < 30
```

Pokémon with Total IV equal to 25

```
p!pokemon --iv 25
p!pokemon --iv = 25
```

</details>

#### --legendary

> Filter for [Legendary pokémon](https://nintendo.fandom.com/wiki/Legendary\_Pok%C3%A9mon) (pokémon with the **legendary** rarity, this can be seen in the **pokedex** command for a pokémon.) E.g. Raikou.

<details>

<summary>Commonly used aliases</summary>

\--leg

\--legend

</details>

<details>

<summary>Commands</summary>

<mark style="color:green;">auction search</mark>

<mark style="color:green;">favoriteall</mark>

<mark style="color:green;">market search</mark>

<mark style="color:green;">nickall</mark>

<mark style="color:green;">pokedex</mark> (cannot be used alongside other rarity filters)

<mark style="color:green;">pokemon</mark>

<mark style="color:green;">releaseall</mark>

<mark style="color:green;">trade addall</mark>&#x20;

<mark style="color:green;">unfavoriteall</mark>

</details>

#### --level `<integer>`

> Filter for pokémon with the specified level. You can use `>`, `<` or `=` to show greater than, less than or equal to the specified integer or decimal.

<details>

<summary>Commonly used aliases</summary>

\--lev

</details>

<details>

<summary>Commands</summary>

<mark style="color:green;">auction search</mark>

<mark style="color:green;">favoriteall</mark>

<mark style="color:green;">market search</mark>

<mark style="color:green;">nickall</mark>

<mark style="color:red;">pokedex</mark>

<mark style="color:green;">pokemon</mark>

<mark style="color:green;">releaseall</mark>

<mark style="color:green;">trade addall</mark>&#x20;

<mark style="color:green;">unfavoriteall</mark>

</details>

<details>

<summary>Examples</summary>

Pokémon with level greater than 20

```
p!pokemon --level > 20
```

Pokémon with level less than 30

```
p!pokemon --level < 30
```

Pokémon with level greater than 20 but less than 30

```
p!pokemon --level > 20 --level < 30
```

Pokémon with level equal to 25

```
p!pokemon --level 25
p!pokemon --level = 25
```

</details>

#### --limit `<integer>`

> Filter to limit the amount of pokémon shown. Regardless of how many pokémon the search returns, it'll always show `<integer>` amount of pokémon as long as there is enough.

![E.g. in this image, it is showing 3 pokémon even though there may be more in my inventory.](../.gitbook/assets/IMG\_20220126\_140500.jpg)

<details>

<summary>Commonly used aliases</summary>

\--lim

</details>

<details>

<summary>Commands</summary>

<mark style="color:green;">auction search</mark>

<mark style="color:green;">favoriteall</mark>

<mark style="color:green;">market search</mark>

<mark style="color:green;">nickall</mark>

<mark style="color:red;">pokedex</mark>

<mark style="color:green;">pokemon</mark>

<mark style="color:green;">releaseall</mark>

<mark style="color:green;">trade addall</mark>

<mark style="color:green;">unfavoriteall</mark>

</details>

#### --mega

> Filter for pokémon that are in their mega form. (Transformed by purchasing a Mega evolution for your pokémon from **p!shop 6**)

<details>

<summary>Commands</summary>

<mark style="color:green;">auction search</mark>

<mark style="color:green;">favoriteall</mark>

<mark style="color:green;">market search</mark>

<mark style="color:green;">nickall</mark>

<mark style="color:red;">pokedex</mark>

<mark style="color:green;">pokemon</mark>

<mark style="color:green;">releaseall</mark>

<mark style="color:green;">trade addall</mark>

<mark style="color:green;">unfavoriteall</mark>

</details>

<details>

<summary>Pokémon</summary>

* [Mega Venusaur](https://pokemondb.net/pokedex/venusaur)
* [X Mega Charizard](https://pokemondb.net/pokedex/charizard)
* [Y Mega Charizard](https://pokemondb.net/pokedex/charizard)
* [Mega Blastoise](https://pokemondb.net/pokedex/blastoise)
* [Mega Beedrill](https://pokemondb.net/pokedex/beedrill)
* [Mega Pidgeot](https://pokemondb.net/pokedex/pidgeot)
* [Mega Alakazam](https://pokemondb.net/pokedex/alakazam)
* [Mega Slowbro](https://pokemondb.net/pokedex/slowbro)
* [Mega Gengar](https://pokemondb.net/pokedex/gengar)
* [Mega Kangaskhan](https://pokemondb.net/pokedex/kangaskhan)
* [Mega Pinsir](https://pokemondb.net/pokedex/pinsir)
* [Mega Gyarados](https://pokemondb.net/pokedex/gyarados)
* [Mega Aerodactyl](https://pokemondb.net/pokedex/aerodactyl)
* [X Mega Mewtwo](https://pokemondb.net/pokedex/mewtwo)
* [Y Mega Mewtwo](https://pokemondb.net/pokedex/mewtwo)
* [Mega Ampharos](https://pokemondb.net/pokedex/ampharos)
* [Mega Steelix](https://pokemondb.net/pokedex/steelix)
* [Mega Scizor](https://pokemondb.net/pokedex/scizor)
* [Mega Heracross](https://pokemondb.net/pokedex/heracross)
* [Mega Houndoom](https://pokemondb.net/pokedex/houndoom)
* [Mega Tyranitar](https://pokemondb.net/pokedex/tyranitar)
* [Mega Sceptile](https://pokemondb.net/pokedex/sceptile)
* [Mega Blaziken](https://pokemondb.net/pokedex/blaziken)
* [Mega Swampert](https://pokemondb.net/pokedex/swampert)
* [Mega Gardevoir](https://pokemondb.net/pokedex/gardevoir)
* [Mega Sableye](https://pokemondb.net/pokedex/sableye)
* [Mega Mawile](https://pokemondb.net/pokedex/mawile)
* [Mega Aggron](https://pokemondb.net/pokedex/aggron)
* [Mega Medicham](https://pokemondb.net/pokedex/medicham)
* [Mega Manectric](https://pokemondb.net/pokedex/manectric)
* [Mega Sharpedo](https://pokemondb.net/pokedex/sharpedo)
* [Mega Camerupt](https://pokemondb.net/pokedex/camerupt)
* [Mega Altaria](https://pokemondb.net/pokedex/altaria)
* [Mega Banette](https://pokemondb.net/pokedex/banette)
* [Mega Absol](https://pokemondb.net/pokedex/absol)
* [Mega Glalie](https://pokemondb.net/pokedex/glalie)
* [Mega Salamence](https://pokemondb.net/pokedex/salamence)
* [Mega Metagross](https://pokemondb.net/pokedex/metagross)
* [Mega Latias](https://pokemondb.net/pokedex/latias)
* [Mega Latios](https://pokemondb.net/pokedex/latios)
* [Mega Kyogre](https://pokemondb.net/pokedex/kyogre)
* [Mega Groudon](https://pokemondb.net/pokedex/groudon)
* [Mega Rayquaza](https://pokemondb.net/pokedex/rayquaza)
* [Mega Lopunny](https://pokemondb.net/pokedex/lopunny)
* [Mega Garchomp](https://pokemondb.net/pokedex/garchomp)
* [Mega Lucario](https://pokemondb.net/pokedex/lucario)
* [Mega Abomasnow](https://pokemondb.net/pokedex/abomasnow)
* [Mega Gallade](https://pokemondb.net/pokedex/gallade)
* [Mega Audino](https://pokemondb.net/pokedex/audino)
* [Mega Diancie](https://pokemondb.net/pokedex/diancie)

</details>

#### --mine

> Filter for viewing pokémon on **market search** and **auction search** that belong to you; listings or auctions that you have added or started and haven't been removed/bought yet.&#x20;

<details>

<summary>Commonly used aliases</summary>

\--mi

\--listings

\--list

</details>

<details>

<summary>Commands</summary>

<mark style="color:green;">auction search</mark>

<mark style="color:red;">favoriteall</mark>

<mark style="color:green;">market search</mark>

<mark style="color:red;">nickall</mark>

<mark style="color:red;">pokedex</mark>

<mark style="color:red;">pokemon</mark>

<mark style="color:red;">releaseall</mark>

<mark style="color:red;">trade addall</mark>

<mark style="color:red;">unfavoriteall</mark>

</details>

#### --mythical

> Filter for [Mythical pokémon](https://nintendo.fandom.com/wiki/Mythical\_Pok%C3%A9mon) (pokémon with the **Mythical** rarity, this can be seen in the **pokedex** command for a pokémon.) E.g. Darkrai.

<details>

<summary>Commonly used aliases</summary>

\--mythic

\--myth

\--my

</details>

<details>

<summary>Commands</summary>

<mark style="color:green;">auction search</mark>

<mark style="color:green;">favoriteall</mark>

<mark style="color:green;">market search</mark>

<mark style="color:green;">nickall</mark>

<mark style="color:green;">pokedex</mark> (cannot be used alongside other rarity filters)

<mark style="color:green;">pokemon</mark>

<mark style="color:green;">releaseall</mark>

<mark style="color:green;">trade addall</mark>&#x20;

<mark style="color:green;">unfavoriteall</mark>

</details>

#### --name `<name>`

> Filter for the name(s) of a pokémon. This filter can be used to look for any pokémon by the displayed or pokédex names (not [nickname](search-filters.md#nickname-less-than-nickname-greater-than)).

![Tip: You can use any of these names shown in the pokedex of a pokémon (viewed using the pokedex command).](../.gitbook/assets/IMG\_20220125\_195037.jpg)

<details>

<summary>Commonly used aliases</summary>

\--n

\--name

</details>

<details>

<summary>Commands</summary>

<mark style="color:green;">auction search</mark>

<mark style="color:green;">favoriteall</mark>

<mark style="color:green;">market search</mark>

<mark style="color:green;">nickall</mark>

<mark style="color:red;">pokedex</mark>

<mark style="color:green;">pokemon</mark>

<mark style="color:green;">releaseall</mark>

<mark style="color:green;">trade addall</mark>&#x20;

<mark style="color:green;">unfavoriteall</mark>

</details>

#### --nickname `<nickname>`

> Filter for finding pokémon with `<nickname>` as their nickname, set by the user using the `nick` or `nickall` commands. You can use this filter multiple times in commands to search for pokémon with the matching nickname for each.&#x20;
>
> {% hint style="info" %}
> **You can use this filter with the `nickall` command to nickname pokémon with an existing nickname. E.g. `p!nickall new_nick --nickname old_nick`**
> {% endhint %}

<details>

<summary>Commonly used aliases</summary>

\--ni

\--nick

</details>

<details>

<summary>Commands</summary>

<mark style="color:green;">auction search</mark>

<mark style="color:green;">favoriteall</mark>

<mark style="color:green;">market search</mark>

<mark style="color:green;">nickall</mark>

<mark style="color:red;">pokedex</mark>

<mark style="color:green;">pokemon</mark>

<mark style="color:green;">releaseall</mark>

<mark style="color:green;">trade addall</mark>&#x20;

<mark style="color:green;">unfavoriteall</mark>

</details>

#### --order `<order>`

> Filter for sorting the pokémon shown in **market search** and **auction search** in a specific order. This filter can only be used _once_ per command.
>
> Options for `<order>`:
>
> {% hint style="info" %}
> **Optionally add a `-` or `+` at the end of an option for descending(`-`) or ascending(`+`) order of that option, otherwise it uses the default (descending for `iv` and `level` and ascending for the rest).**
> {% endhint %}
>
> * `iv` - Sort by the total IV of pokémon.
> * `level` - Sort by the level of pokémon.
> * \[**auction search** only]:
>   * `bid` - Sort by the **Current Bid** of auctions.
>   * `ends` - Sort by the remaining duration of auctions
> * \[**market search** only]:
>   * `price` - Sort by the **Price** of market listings.
>   * `id` - Sort by the [ID](https://cdn.discordapp.com/attachments/768175554402058313/936668421217734656/IMG\_20220128\_223543.jpg)s of market listings.

<details>

<summary>Commonly used aliases</summary>

\--o

\--or

</details>

<details>

<summary>Commands</summary>

<mark style="color:green;">auction search</mark>

<mark style="color:red;">favoriteall</mark>

<mark style="color:green;">market search</mark>

<mark style="color:red;">nickall</mark>

<mark style="color:red;">pokedex</mark>

<mark style="color:red;">pokemon</mark>

<mark style="color:red;">releaseall</mark>

<mark style="color:red;">trade addall</mark>

<mark style="color:red;">unfavoriteall</mark>

</details>

<details>

<summary>Examples</summary>

Order **market search** by `price` ascending (low to high)

```
p!market search --order price
p!market search --order price+
```

Order **auction search** by `iv` descending

```
p!auction search --order iv
p!auction search --order iv-
```

</details>

#### --ordera

> Filter for sorting pokémon in the **pokedex** command in ascending order of the caught amount of each pokémon.&#x20;

<details>

<summary>Commands</summary>

<mark style="color:red;">auction search</mark>

<mark style="color:red;">favoriteall</mark>

<mark style="color:red;">market search</mark>

<mark style="color:red;">nickall</mark>

<mark style="color:green;">pokedex</mark>

<mark style="color:red;">pokemon</mark>

<mark style="color:red;">releaseall</mark>

<mark style="color:red;">trade addall</mark>

<mark style="color:red;">unfavoriteall</mark>

</details>

#### --orderd

> Filter for sorting pokémon in the **pokedex** command in descending order of the caught amount of each pokémon.

<details>

<summary>Commands</summary>

<mark style="color:red;">auction search</mark>

<mark style="color:red;">favoriteall</mark>

<mark style="color:red;">market search</mark>

<mark style="color:red;">nickall</mark>

<mark style="color:green;">pokedex</mark>

<mark style="color:red;">pokemon</mark>

<mark style="color:red;">releaseall</mark>

<mark style="color:red;">trade addall</mark>

<mark style="color:red;">unfavoriteall</mark>

</details>

#### --pentuple `<integer>`

> Filter for pokémon that have atleast 5 stat IVs that are equal to `<integer>`.  To elaborate, for a pokémon to match the criteria for this filter, 5 of its stat IVs, namely `HP`, `ATK`, `DEF`, `SPATK`, `SPDEF` and `SPD` IVs, need to be the same, equal to `<integer>`. This filter will also match combinations that are higher than 5.

![E.g. this pokémon would match the criteria for p!pokemon --pentuple 31 because it has 5 equal stat IVs that are 31.](../.gitbook/assets/IMG\_20220128\_235049.jpg)

<details>

<summary>Commonly used aliases</summary>

\--five

\--pent

\--penta

\--quintuple

</details>

<details>

<summary>Commands</summary>

<mark style="color:green;">auction search</mark>

<mark style="color:green;">favoriteall</mark>

<mark style="color:green;">market search</mark>

<mark style="color:green;">nickall</mark>

<mark style="color:red;">pokedex</mark>

<mark style="color:green;">pokemon</mark>

<mark style="color:green;">releaseall</mark>

<mark style="color:green;">trade addall</mark>&#x20;

<mark style="color:green;">unfavoriteall</mark>

</details>

#### --quadruple `<integer>`

> Filter for pokémon that have atleast 4 stat IVs that are equal to `<integer>`.  To elaborate, for a pokémon to match the criteria for this filter, 4 of its stat IVs, namely `HP`, `ATK`, `DEF`, `SPATK`, `SPDEF` and `SPD` IVs, need to be the same, equal to `<integer>`. This filter will also match combinations that are higher than 4.

![E.g. this pokémon would match the criteria for p!pokemon --quadruple 31 because it has 4 equal stat IVs that are 31.](../.gitbook/assets/IMG\_20220128\_235159.jpg)

<details>

<summary>Commonly used aliases</summary>

\--four

\--quad

\--quadra

\--tetra

</details>

<details>

<summary>Commands</summary>

<mark style="color:green;">auction search</mark>

<mark style="color:green;">favoriteall</mark>

<mark style="color:green;">market search</mark>

<mark style="color:green;">nickall</mark>

<mark style="color:red;">pokedex</mark>

<mark style="color:green;">pokemon</mark>

<mark style="color:green;">releaseall</mark>

<mark style="color:green;">trade addall</mark>&#x20;

<mark style="color:green;">unfavoriteall</mark>

</details>

#### --region `<region>`

> Filter for pokémon that are from the region `<region>`.&#x20;

<details>

<summary>Commonly used aliases</summary>

\--r

\--reg

</details>

<details>

<summary>Commands</summary>

<mark style="color:green;">auction search</mark>

<mark style="color:green;">favoriteall</mark>

<mark style="color:green;">market search</mark>

<mark style="color:green;">nickall</mark>

<mark style="color:green;">pokedex</mark>

<mark style="color:green;">pokemon</mark>

<mark style="color:green;">releaseall</mark>

<mark style="color:green;">trade addall</mark>

<mark style="color:green;">unfavoriteall</mark>

</details>

<details>

<summary>Regions</summary>

1. [Kanto](https://pokemondb.net/pokedex/national#gen-1)
2. [Johto](https://pokemondb.net/pokedex/national#gen-2)
3. [Hoenn](https://pokemondb.net/pokedex/national#gen-3)
4. [Sinnoh](https://pokemondb.net/pokedex/national#gen-4)
5. [Unova](https://pokemondb.net/pokedex/national#gen-5)
6. [Kalos](https://pokemondb.net/pokedex/national#gen-6)
7. [Alola](https://pokemondb.net/pokedex/national#gen-7)
8. [Galar](https://pokemondb.net/pokedex/national#gen-8)

</details>

#### --shiny

> Filter for viewing shiny pokémon. Shiny pokémon have a ✨ next to their name.

{% hint style="danger" %}
**Beware of fake shinies! Some dishonest users may attempt to decieve others by nicknaming their pokémon** `✨` **and selling it as a legitimate shiny. Fake shinies have quotes around the emoji: "**✨**". Always double check, and with this filter where possible.**
{% endhint %}

<details>

<summary>Commonly used aliases</summary>

\--sh

\--shi

</details>

<details>

<summary>Commands</summary>

<mark style="color:green;">auction search</mark>

<mark style="color:green;">favoriteall</mark>

<mark style="color:green;">market search</mark>

<mark style="color:green;">nickall</mark>

<mark style="color:red;">pokedex</mark>

<mark style="color:green;">pokemon</mark>

<mark style="color:green;">releaseall</mark>

<mark style="color:green;">trade addall</mark>

<mark style="color:green;">unfavoriteall</mark>

</details>

#### --skip `<integer>`

> Filter to exclude a certain number of pokémon from the beginning when using a command. For example, you may use this filter to favorite all Ralts except the first 5 using `p!favoriteall --n Ralts --skip 5`. &#x20;

<details>

<summary>Commonly used aliases</summary>

\--sk

</details>

<details>

<summary>Commands</summary>

<mark style="color:green;">auction search</mark>

<mark style="color:green;">favoriteall</mark>

<mark style="color:green;">market search</mark>

<mark style="color:green;">nickall</mark>

<mark style="color:red;">pokedex</mark>

<mark style="color:green;">pokemon</mark>

<mark style="color:green;">releaseall</mark>

<mark style="color:green;">trade addall</mark>

<mark style="color:green;">unfavoriteall</mark>

</details>

<details>

<summary>Examples</summary>

Show all Ralts on auction except the first 3

```
p!auction search --name Ralts --skip 3
```

Nickname all Ralts except the first 3

```
p!nickall NICK --name Ralts --skip 3
```

Add all Ralts to a trade except the first 3

```
p!trade addall --name Ralts --skip 3
```

</details>

#### --spatkiv `<integer>`

> Filter for pokémon with the specified Special Attack/SPATK IV. You can use `>`, `<` or `=` to show greater than, less than or equal to the specified integer.

<details>

<summary>Commonly used aliases</summary>

\--spatk

</details>

<details>

<summary>Commands</summary>

<mark style="color:green;">auction search</mark>

<mark style="color:green;">favoriteall</mark>

<mark style="color:green;">market search</mark>

<mark style="color:green;">nickall</mark>

<mark style="color:red;">pokedex</mark>

<mark style="color:green;">pokemon</mark>

<mark style="color:green;">releaseall</mark>

<mark style="color:green;">trade addall</mark>

<mark style="color:green;">unfavoriteall</mark>

</details>

<details>

<summary>Examples</summary>



Pokémon with SPATK IV greater than 20

```
p!pokemon --spatkiv > 20
```

Pokémon with SPATK IV less than 30

```
p!pokemon --spatkiv < 30
```

Pokémon with SPATK IV greater than 20 but less than 30

```
p!pokemon --spatkiv > 20 --spatkiv < 30
```

Pokémon with SPATK IV equal to 25

```
p!pokemon --spatkiv 25
p!pokemon --spatkiv = 25
```

</details>

#### --spdefiv `<integer>`

> Filter for pokémon with the specified Special Defense/SPDEF IV. You can use `>`, `<` or `=` to show greater than, less than or equal to the specified integer.

<details>

<summary>Commonly used aliases</summary>

\--spdef

</details>

<details>

<summary>Commands</summary>

<mark style="color:green;">auction search</mark>

<mark style="color:green;">favoriteall</mark>

<mark style="color:green;">market search</mark>

<mark style="color:green;">nickall</mark>

<mark style="color:red;">pokedex</mark>

<mark style="color:green;">pokemon</mark>

<mark style="color:green;">releaseall</mark>

<mark style="color:green;">trade addall</mark>

<mark style="color:green;">unfavoriteall</mark>

</details>

<details>

<summary>Examples</summary>

Pokémon with SPDEF IV greater than 20

```
p!pokemon --spdefiv > 20
```

Pokémon with SPDEF IV less than 30

```
p!pokemon --spdefiv < 30
```

Pokémon with SPDEF IV greater than 20 but less than 30

```
p!pokemon --spdefiv > 20 --spdefiv < 30
```

Pokémon with SPDEF IV equal to 25

```
p!pokemon --spdefiv 25
p!pokemon --spdefiv = 25
```

</details>

#### --spdiv `<integer>`

> Filter for pokémon with the specified Speed/SPD IV. You can use `>`, `<` or `=` to show greater than, less than or equal to the specified integer.

<details>

<summary>Commands</summary>

<mark style="color:green;">auction search</mark>

<mark style="color:green;">favoriteall</mark>

<mark style="color:green;">market search</mark>

<mark style="color:green;">nickall</mark>

<mark style="color:red;">pokedex</mark>

<mark style="color:green;">pokemon</mark>

<mark style="color:green;">releaseall</mark>

<mark style="color:green;">trade addall</mark>

<mark style="color:green;">unfavoriteall</mark>

</details>

<details>

<summary>Examples</summary>

Pokémon with SPD IV greater than 20

```
p!pokemon --spdiv > 20
```

Pokémon with SPD IV less than 30

```
p!pokemon --spdiv < 30
```

Pokémon with SPD IV greater than 20 but less than 30

```
p!pokemon --spdiv > 20 --spdiv < 30
```

Pokémon with SPD IV equal to 25

```
p!pokemon --spdiv 25
p!pokemon --spdiv = 25
```

</details>

#### --triple `<integer>`

> Filter for pokémon that have atleast 3 stat IVs that are equal to `<integer>`. To elaborate, for a pokémon to match the criteria for this filter, 3 of its stat IVs, namely `HP`, `ATK`, `DEF`, `SPATK`, `SPDEF` and `SPD` IVs, need to be the same, equal to `<integer>`. This filter will also match combinations that are higher than 3.

![E.g. this pokémon would match the criteria for p!pokemon --triple 31 because it has 3 equal stat IVs that are 31.](../.gitbook/assets/IMG\_20220130\_172840.jpg)

<details>

<summary>Commonly used aliases</summary>

\--three

\--trip

\--tri

</details>

<details>

<summary>Commands</summary>

<mark style="color:green;">auction search</mark>

<mark style="color:green;">favoriteall</mark>

<mark style="color:green;">market search</mark>

<mark style="color:green;">nickall</mark>

<mark style="color:red;">pokedex</mark>

<mark style="color:green;">pokemon</mark>

<mark style="color:green;">releaseall</mark>

<mark style="color:green;">trade addall</mark>&#x20;

<mark style="color:green;">unfavoriteall</mark>

</details>

#### --type `<type>`

> Filter for pokémon that are of the type `<type>`. The type of a pokémon can be viewed by using the **pokedex** command.

<details>

<summary>Commonly used aliases</summary>

\--t

\--ty

</details>

<details>

<summary>Commands</summary>

<mark style="color:green;">auction search</mark>

<mark style="color:green;">favoriteall</mark>

<mark style="color:green;">market search</mark>

<mark style="color:green;">nickall</mark>

<mark style="color:green;">pokedex</mark>

<mark style="color:green;">pokemon</mark>

<mark style="color:green;">releaseall</mark>

<mark style="color:green;">trade addall</mark>&#x20;

<mark style="color:green;">unfavoriteall</mark>

</details>

<details>

<summary>Types</summary>

* [Normal](https://pokemondb.net/type/normal)
* [Fire](https://pokemondb.net/type/fire)
* [Water](https://pokemondb.net/type/water)
* [Grass](https://pokemondb.net/type/grass)
* [Electric](https://pokemondb.net/type/electric)
* [Ice](https://pokemondb.net/type/ice)
* [Fighting](https://pokemondb.net/type/fighting)
* [Poison](https://pokemondb.net/type/poison)
* [Ground](https://pokemondb.net/type/ground)
* [Flying](https://pokemondb.net/type/flying)
* [Psychic](https://pokemondb.net/type/psychic)
* [Bug](https://pokemondb.net/type/bug)
* [Rock](https://pokemondb.net/type/rock)
* [Ghost](https://pokemondb.net/type/ghost)
* [Dark](https://pokemondb.net/type/dark)
* [Dragon](https://pokemondb.net/type/dragon)
* [Steel](https://pokemondb.net/type/steel)
* [Fairy](https://pokemondb.net/type/fairy)

</details>

#### --ub

> Filter for [Ultra Beast pokémon](https://pokemon.fandom.com/wiki/Ultra\_Beasts) (pokémon with the **Ultra Beast** rarity, this can be seen in the **pokedex** command for a pokémon.) E.g. Pheromosa.

<details>

<summary>Commonly used aliases</summary>

\--u

</details>

<details>

<summary>Commands</summary>

<mark style="color:green;">auction search</mark>

<mark style="color:green;">favoriteall</mark>

<mark style="color:green;">market search</mark>

<mark style="color:green;">nickall</mark>

<mark style="color:green;">pokedex</mark> (cannot be used alongside other rarity filters)

<mark style="color:green;">pokemon</mark>

<mark style="color:green;">releaseall</mark>

<mark style="color:green;">trade addall</mark>

<mark style="color:green;">unfavoriteall</mark>

</details>

#### --uncaught

> Filter for all the uncaught pokémon in the **pokedex** command.&#x20;

<details>

<summary>Commonly used aliases</summary>

\--unc

\--un

</details>

<details>

<summary>Commands</summary>

<mark style="color:red;">auction search</mark>

<mark style="color:red;">favoriteall</mark>

<mark style="color:red;">market search</mark>

<mark style="color:red;">nickall</mark>

<mark style="color:green;">pokedex</mark>

<mark style="color:red;">pokemon</mark>

<mark style="color:red;">releaseall</mark>

<mark style="color:red;">trade addall</mark>

<mark style="color:red;">unfavoriteall</mark>

</details>
