---
description: Basic auction information and commands.
---

# Auctions

Pokétwo auctions are essentially public sales of a pokémon, where the pokémon is sold to the highest bidder. After an auction is started, people can bid on the auction. The first person who bid on an auction can bid anywhere higher or the same as the starting bid (SB). The next person who bid would need to bid \<current bid (CB)+ bid increment (BI)> and so on.\
\
At the moment, auctions are only available on the Official Poketwo Community server.  \
\
The following are the basic auction commands :\
\
**Starting an auction**\
****P!a start (Pokemon ID) (Duration) (Starting bid) (Bid increment) Ex. P!a start 297 12h 1000 100

* Auctioning pokemon 297
* The auction will last for 12 hours
* 1000pc starting bid
* 100pc bid increment\
  ![](<../.gitbook/assets/image (22).png>)\
  \


For the duration, you can use w (ex. 1w) for week, d (ex. 3d) for days, h (ex. 3h) for hours, and m (ex. 30m) for minutes.\
The maximum duration for an auction is 1 week.\
Note that bid increment cant be higher than starting bid.\
After starting an auction, you cant cancel them.\
\
P!a lowerstart (auction id) (new start)\
You can use this command to change the starting bid of your own auction if no one bid on it yet.\
\
**Searching**

* P!a s --(You can add different filters here. For more information you can check the filter page) ex. P!a s --leg \
  &#x20;     P!a s --n xerneas \
  &#x20;     P!a s --n popplio --sh --iv >60
* P!a s --mi \
  Searching your own auctions
* P!a i (auction id) \
  To check more spesific detail about an auction. Including the highest bidder, the iv of the pokemon, etc. \
  ![](<../.gitbook/assets/image (25).png>)
* P!a s --bids\
  Using this command, you can see the auctions where you're the highest bidder.
* P!a s --o bid+/-\
  \--o bids+ to search for auctions with the lowest bid\
  \--o bids- to search for auctions with the highest bid
* P!a s --o ends+/-\
  \--o ends+ to search for auction that would end the fastest\
  \--o ends- to search for auction that would end the slowest

**Bidding**

P!a bid (auction id) (bid)\
Ex. P!a bid 103483 12000

* Bidding on auction 103483
* Bid amount is 12000pc

Do note that **you cant cancel your bid**, so always double-check!

Auction ID are the numbers on the left side when you're searching for auctions\
![](<../.gitbook/assets/image (15).png>)

\
\
\
\
****
