---
description: >-
  Pokémon are here! In this section you will learn everything about wild spawns,
  how to catch Pokémon, how to guess them, spawn rates and chances, tips and
  tricks, etc.
---

# Spawning & Catching

{% hint style="warning" %}
This site is an early **work in progress**. Many pages may be missing or incomplete. Please let us know at [discord.gg/poketwo](https://discord.gg/poketwo) if you would like to help write or improve a page.
{% endhint %}

### List of related commands

1. `@​Pokétwo#8236 [catch|c] <pokémon-name>` - To catch a pokémon that has [spawned](spawning-and-catching.md#spawning-pokemon).
2. `@​Pokétwo#8236 [hint|h]` - To get a [hint ](spawning-and-catching.md#pokemon-hints)for the name of the pokémon currently present in the channel
3. `@​Pokétwo#8236 togglemention` - To stop the bot from mentioning you whenever you catch pokémon
4. `@​Pokétwo#8236 profile` - To view your pokétwo profile
5. `@​Pokétwo#8236 shop [page_number]` - To view shop and its items at specific pages
6. `@​Pokétwo#8236 buy <item>` - To buy an item from the shop
7. `@​Pokétwo#8236 [shinyhunt|sh] <pokémon-name>` - To start [shinyhunting](spawning-and-catching.md#shiny-hunting) a pokémon. WIll discard current streak after confirmation.
8. `@​Pokétwo#8236 [pokedex|d] [pokémon-name]` - To view the pokédex of a pokémon
9. `@​Pokétwo#8236 buy incense` - To buy an [incense](spawning-and-catching.md#incenses) **in the current channel**
10. `@​Pokétwo#8236 stopincense` - To <mark style="color:red;">**PERMANENTLY**</mark>** ** stop an incense active in the current channel
11. `@​Pokétwo#8236 redirect <channel-names|reset>` - To [redirect ](spawning-and-catching.md#setting-spawn-channels)natural spawns to specific channels, or to reset the set spawn channels

### Spawning Pokémon

Pokémon spawning is based on the activity of a server. Messages sent by **non-bot** users count towards a spawn criterion and spawns a pokémon when met.&#x20;

Messages sent by 2 or more users count towards that criterion faster, so inviting Pokétwo to a server with friends who converse naturally is a great place to start. Otherwise, it becomes cumbersome to manually send messages in order for spawns to occur.

{% hint style="danger" %}
Auto-spammers that spam to trigger spawns, Auto-catchers that automatically catch spawned pokémon and other automated activities via selfbotting, made in order to gain an unfair advantage, are strictly prohibited by both Discord and Pokétwo and are suspendable offences. Read [Pokétwo's Terms of Service](https://poketwo.net/terms) along with [Discord's Terms of Service](https://discord.com/terms) in order to learn more about what we allow and what we don't.
{% endhint %}

#### Spawn rates

The conditions for optimal spawn rate of pokémon is as follows, under which there will be a spawn **every 24 messages**:

* **When 1 user sends messages**
  * Optimal rate of messages: Send a message every **1.5 seconds**
  * Time to spawn (at optimal message rate): **36 seconds**
* **When 2 or more users send messages**&#x20;
  * Optimal Rate of messages: Send a message, alternating between 2+ users, every **1 second**
  * Time to spawn (at optimal message rate): **24 seconds**

### **Spawn chances**

Different pokémon have different chances to spawn. There are pokémon that spawn very often and there are pokémon that spawn very rarely. The spawn chance of pokémon play an important role in determining its market value.

Here is a list of links you can visit in order to find up-to-date spawn chances of various pokémon and categories (and their catchable forms). They are all **ordered by chance (ascending)**:

{% tabs %}
{% tab title="Base pokémon" %}
* [**Searchable list of All Pokémon**](https://gist.github.com/WitherredAway/1bc525b05f4cd52555a2a18c331e0cf9)****
* ****[**Starter Pokémon**](https://gist.github.com/WitherredAway/1bdee3b3fb2a29ae8f83ebdd70013456)****



1. ****[**Mythical Pokémon**](https://gist.github.com/ba3f32d61cfdaf857c8541d168c21698)****
2. ****[**Legendary Pokémon**](https://gist.github.com/af25f3f398fbc0441fd0248a5ca3faad)****
3. ****[**Ultra Beast Pokémon**](https://gist.github.com/ba3f1b7063e939d8119286bbeb8e8080)
{% endtab %}

{% tab title="Forms" %}
1. ****[**Alolan Pokémon**](https://gist.github.com/7c3cdaaa36c38d2fb2bd716652b09d00)****
2. ****[**Galarian Pokémon**](https://gist.github.com/4fb6735b2241506105af52626953618b)****
3. ****[**Hisuian Pokémon**](https://gist.github.com/4bcf5ef86577b14aa464a3376adb430e)****

****

* ****[**Latest event pokémon**](https://gist.github.com/caf8fc84a8072cfcd1d07b2d18730d5e)****
{% endtab %}

{% tab title="Regional Pokémon" %}
1. ****[**Kanto**](https://gist.github.com/2c48fc73eb1a9e94737634092e1c62e3) **** \[`168`]
2. ****[**Johto** ](https://gist.github.com/4456e7da504e9ff5ddc653cd3bc4e76c)\[`105`]
3. ****[**Hoenn**](https://gist.github.com/ce4facd1f383676bb745cece67fbac50) \[`143`]
4. ****[**Sinnoh** ](https://gist.github.com/e9a435742bea160eb588c8812e0730c4)\[`109`]
   * ****[**Hisui** ](https://gist.github.com/46bbc638f81687aa42709a83078aa1f8)\[`7`]
5. ****[**Unova** ](https://gist.github.com/6af2072d0229c3f5582b32f20b65f2f5)\[`166`]
6. ****[**Kalos** ](https://gist.github.com/849a6b64a35a505c7afb2eb276eda18d)\[`77`]
7. ****[**Alola** ](https://gist.github.com/a55287b7bff61b90b3182bca602b062a)\[`108`]
8. ****[**Galar** ](https://gist.github.com/f4d75c84e7ed4ce57273b6ef860a5a54)\[`90`]
{% endtab %}
{% endtabs %}

### Catching Pokémon

To catch a pokémon, when one spawns, you must guess which pokémon it is. This can seem difficult at the beginning but if you catch enough, it will gradually get easier.&#x20;

After guessing the pokémon, run the command `@​Pokétwo#8236 [catch|c] <guess>` to attempt to catch it.

Failed attempts do no make the pokémon despawn, you can try as many times as you want as long as nobody else catches it.

![Catching a Marill](<../.gitbook/assets/Screenshot 2023-02-23 191240 (1).png>)

{% hint style="info" %}
You can make it so that the bot does not ping you when catching pokémon via the `@​Pokétwo#8236 togglemention` command. Use the same to turn it back on.

<img src="../.gitbook/assets/Screenshot 2023-02-23 221838.png" alt="" data-size="original">
{% endhint %}

### Catching rewards

Various **badges** for your profile (`@​Pokétwo#8236 profile`) and **pokécoin** rewards can be earned by catching different number of pokémon.

#### Quests

Different quests can be completed to earn **badges** and **pokécoins**. Please refer to the following table for the pokécoin rewards.

From each region, there is a quest to catch different set number of pokémon for respective amount of pokécoins. For detailed info, please visit our [quests.md](../intermediate-topics/quests.md "mention") page.

| Milestone (per region) | Reward (pokécoins)                   |
| ---------------------- | ------------------------------------ |
| 20 Pokémon             | 2,000                                |
| 50 Pokémon             | 5,000                                |
| 100 Pokémon            | 10,000                               |
| 200 Pokémon            | 20,000                               |
| 500 Pokémon            | 50,000 (& respective regional badge) |

A total of **696,000 pokécoins** and **8 badges** can be earned after completion of all `5 x 8 = 40` quests

#### Catch milestones

If you catch multiple of the same pokémon, you can earn pokécoins at certain milestones.

| Total number caught | Rewards (pokécoins) |
| ------------------- | ------------------- |
| 1                   | 35                  |
| 10                  | 350                 |
| 100                 | 3,500               |
| 1,000               | 35,000              |
| 10,000              | 350,000             |
| 100,000             | 3,500,000           |

### Pokémon hints

If you don't know a Pokémon's name, or you just don't remember what it was called, you can receive hints to guess it.

To receive hints for a Pokémon's name, the command is `@​Pokétwo#8236 [hint|h]`. This will show a few letters of the Pokémon's name, which can help you to guess the name.

For example:

![The Pokémon in this picture is Dragonair.](<../.gitbook/assets/Screenshot 2023-02-23 192052.png>)

Furthermore, you can join [our community server](https://discord.gg/poketwo) and ask for help with pokémon names in the <mark style="background-color:blue;">#whos-that-pokemon</mark> channel!

### Shiny Pokémon

Whenever you catch a pokémon, there is a `1/4096` or `~0.0244%` chance of it being shiny. It is important to understand that shinies don't _spawn;_ it is determined after the catch, whether or not it will be shiny.

There are only two ways to increase this chance:

1. Buying a **Shiny Charm** from the shop (page 7). This will increase the shiny chance of _all pokémon_ by **20%** for **1 week**. **Shiny Charms can not be stacked**.
   * Increased chance: `1/3413.3` or `~0.029%`
   * Command: `@​Pokétwo#8236 buy shiny charm`
   * Price: **150 shards** (30,000 pokécoins)
2. By **Shiny Hunting** a specific pokémon. This will increase the shiny chance of the _one particular pokémon_ that you shiny hunt.
   * Increased chance: `7 + √(shiny_streak) / 28672` (Without Shiny Charm)
   * Command: `@​Pokétwo#8236 shinyhunt <pokémon-name>`
   * More info at [#shiny-hunting](spawning-and-catching.md#shiny-hunting "mention")

When you catch a shiny, this is the message you will see

![Here's an example of someone catching a shiny Espurr.
](../.gitbook/assets/Shiny.PNG)

### Shiny Hunting

Shiny hunting will increase the shiny chance, for only the Pokémon that you are shiny hunting, by \~**`x1.05`** at the beginning, and this value decreases and approaches **`x1`** as the shiny streak increases (e.g. it becomes \~**`x1.003`** at 100 shiny streak. and so on). **You can shiny hunt only one pokémon at a time.**

#### How to shiny hunt

The command to start shiny hunting a Pokémon is `@​Pokétwo#8236 [shinyhunt|sh] <pokémon-name>`.

#### Calculating chance

**The formula** for calculating the shiny chance % at a certain streak is:

$$(1+\frac{\sqrt{streak}}{7})\times\frac{1}{4096}\times100$$

$$=\frac{7 + \sqrt{streak}}{28672}\times100$$

**With Shiny Charm:**

$$\frac{7 + \sqrt{streak}}{23893.1}\times100$$

#### Here is a simple program to calculate the chances at a specific shiny hunt streak

{% embed url="https://trinket.io/embed/python/072b38317a?outputOnly=true&runOption=run&start=result" %}
Simple program to calculate shiny chance at a specific shiny streak
{% endembed %}

**For example, at streak 100:**

$$(1+\frac{\sqrt{100}}{7})\times\frac{1}{4096}\times100$$

$$=(1 + \frac{10}{7})\times\frac{1}{4096}\times100$$

$$=\frac{17}{7}\times\frac{1}{4096}\times100$$

$$\approx0.059$$ %

$$\approx0.06$$ %

{% hint style="warning" %}
Deriving from this formula, there is a 100% chance of shiny at around 823,543,225 streak (570,545,773 with Shiny Charm). This big number may look scary, but keep in mind that this number is purely mathematical and in a realistic situation you will have caught the shiny well before ever getting even remotely close to this number.
{% endhint %}

{% hint style="info" %}
It is not possible to shiny hunt specifically an event Pokémon or a Pokémon's form (For example, Alolan or Galarian).&#x20;

If you attempt to do so, it will instead make you shiny hunt its base form.

![](<../.gitbook/assets/Screenshot 2023-02-23 193959 (1).png>)

However, catching that form _will_ count towards this streak and the chance will increase for any form of this pokémon.

As an example, let's say you want to shiny hunt **Alolan Vulpix**. After starting hunting **Vulpix**, only catch the **Alolan** form. You must be careful not to catch the base form or any other forms, as their shiny chances will increase as well and hence break the shiny hunt streak if you get lucky, or rather, unlucky.
{% endhint %}

#### **"Can I catch a shiny that is not my hunt even if I'm hunting a Pokémon?"**

Yes you can! You can always catch a shiny, the chance of which is `1/4096` or `~0.0244%` and `1/3413.3` or `~0.029%` with Shiny Charm.

### Alternate Pokémon names

Pokémon have alternate names in different languages that you can use to catch them. To see the alternate names of a pokémon, check its pokédex using the command `@​Pokétwo#8236 [pokedex|d] <pokémon-name>`.

![Here is an example of the alt names of Charmander](<../.gitbook/assets/Alt names.jpg>)

So you can type `@​Pokétwo#8236 catch ヒトカゲ | Hitokage | Charmander | Glumanda | Salamèche` to catch a Charmander.&#x20;

### Incenses

If you wish to get spawns in a server that is not so active, you can purchase an **Incense** from the shop (page 7) which will spawn pokémon constantly at regular intervals without any prerequisites.

#### Details

An incense spawns pokémon every **20 seconds** for **1 hour**. In total, there will be **180 pokémon** that will spawn per incense.

#### Steps for purchasing an incense

* You must either have a role named **Incense** (not case-sensitive) or have **Administration**/**Owner** permissions in the server in order to purchase an incense.
* Incenses cost **50 shards** (10,000 pokécoins). You must have atleast 50 shards in order to purchase an incense, having 10,000 pokécoins will not count. \
  To buy shards, do `@​Pokétwo#8236 buy shard 50`.
* Go to the channel in which you want to buy the incense.
* Use the command `@​Pokétwo#8236 buy incense` .
* Press the <mark style="background-color:green;">**Confirm**</mark> button. If you wish to cancel, press the <mark style="background-color:red;">**Cancel**</mark> button.
* The incense will now begin to spawn. At any point in the incense, if you wish to <mark style="color:red;">**PERMANENTLY**</mark>** ** stop the incense, you can do so by using the `@​Pokétwo#8236 stopincense` command and pressing <mark style="background-color:green;">**Confirm**</mark>.
* You can do more than one incense at once, but in different channels. **You can not stack incenses.**

### Setting spawn channels

To redirect **natural (not incense)** spawns to specific channels, you can use the command `​Pokétwo#8236 redirect #channel1 #channel2 #channel3` with as many channels as you want.

To view the current set spawn channels, use the command `@​Pokétwo#8236 config` which will list them all.&#x20;

To **reset** the set spawn channels, use `@​Pokétwo#8236 redirect reset`, which will remove all set spawn channels and make it so that pokémon spawn in the same channels that are active.

{% hint style="info" %}
This page is an improved version of the original that was made by Sept#8911 (Discord ID: 891522852182982656) ❤️
{% endhint %}
