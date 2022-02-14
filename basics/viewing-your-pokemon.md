# Viewing Your Pokémon

{% hint style="warning" %}
This site is an early **work in progress**. Many pages may be missing or incomplete. Please let us know at [discord.gg/poketwo](https://discord.gg/poketwo) if you would like to help write or improve a page.
{% endhint %}

Now that you have started catching Pokémon, you may want to view the Pokémon you've caught so far.&#x20;

This can be done in two main ways. First, a full view which includes everything about one of your Pokémon, and second, a list view of all the Pokémon you own, with 20 showing on one page at a time.&#x20;

**p!info** (p!i): \
This command shows your current selected Pokémon in an embed message. It shows all the info you can get including a picture, level, name, nickname, current XP, nature, stats and IVs, as well as your profile picture and Pokémon number/ID. There will also be two arrow buttons at the bottom, this allows you to scroll through all your Pokémon and view their stats. The command p!next and p!back (p!n and p!b respectively) also work in place of the arrow buttons.

Now if you want to easily view the information of Pokémon other than your current selected one, there are other options. One useful command is **p!info latest** (p!i l), this shows your most recent or last caught Pokémon. Another variation of this command is **p!info ID** (p!i ID). An example of this command is p!info 4. This command shows the info of that particular Pokémon ID you selected. Pokémon ID is the number which is assigned to your Pokémon when it enters your account, to find the Pokémon ID, we must do a different command.

**p!pokemon** (p!p): \
This is a very common command and is used to show all of your Pokémon in list form. It shows information from left to right including ID (mentioned above), a small image, name, nickname, whether or not its favorited, level, and total IV. Like p!info, there will also be arrow buttons and the option to use the p!next and p!back commands, this scrolls through your Pokémon and navigates to the different pages, going back on the first page will get you to the last. **p!go page** (p!g page) can also be used, this jumps to the specified page number, for example p!go 4 will get you to the forth page of your Pokémon.&#x20;

**p!order** (p!or):\
Running this command by itself will give you some options including number (this is the ID and default option, it sorts your pokemon according to ID, from lowest to highest), IV (this sorts your pokemon from highest to lowest total IV), level (this sorts your pokemon from highest to lowest level), and Pokédex (this sorts your pokemon according to the order of the Pokédex, from lowest to highest starting from Bulbasaur). To choose your option, simply run p!order option, an example being p!order iv. This command allows you to show off your highest IV or level pokemon with just p!pokemon. Note that --order filters do not work in p!pokemon.&#x20;

Another way to change the p!pokemon command is through filters. You can refer to the [Search Filters](../intermediate-topics/search-filters.md) page to see a list of possible filters. Filters can be added next to each other to create a narrow search. For example, to find a shiny dark type, you can run a command which includes a type filter and a shiny filter, it would look something like p!pokemon --shiny --type dark (p!p --sh --t dark).&#x20;

One useful tool to view a specific group of Pokémon you like is the **p!favorite** (p!fav) command. Just running p!favorite will add a heart next to wherever you see its name or nickname, this adds this to your group of favorite Pokémon. There are also variations to this command including p!favorite ID (p!fav ID) and p!favoriteall filters (p!favall filters). Now to view all your favorited Pokémon, run p!pokemon --favorite (p!p --fav).&#x20;

**p!nickname name** (p!nick name).\
_p!nickname ID name_ and _p!nicknameall name filters_ also work. This will add a nickname to the Pokémon that is specified. Having nicknames on your pokemon can be used to later search for them or add some customization. To find specifc nicknames run p!pokemon --nickname name (p!p --ni name), this will show all Pokémon with a nickname that includes your search criteria. For example p!p --ni a will show all Pokémon with an a in their nickname.&#x20;
