# Shop
This represents the store being managed

#### User Managed Properties
|Name|Description|
|-|-|
|Name|The the player chooses for the shop|
|Showroom|Information about the area customers use|
|Storage|Information about the shop inventory|

#### Dynamic Properties
|Name|Description|
|-|-|
|Rating|This is basically the players current score|
|MaxCapacity|Calculated from showroom size and available floor space|
|CustomerList|The customers currently shopping|
|SoundLevel|Calculated from how many customers are trying items and their skill|

## Behavior
At the start of the game, the player gives their shop a name.

The showroom is the primary thing being rendered. It's where the customers shop for items and checkout. The showrooms current and max capacity will affect customer generation. The showrooms SoundLevel will affect the customer experience. Nobody wants to be in a cacophany of bad players, but an empty/silent music store isn't a good thing either.

The showroom will contain the entrance/exit used by customers. The showroom size should be upgradable so more items can be on display. The player should be able to have display racks that inventory is placed on so customers can try out items and/or add them to their shopping carts. Shopping carts are just data, not rendered objects. Checkout counters will also be placed in the showroom.

The Storage should also be rendered, but customers cannot enter it. It will have a max capacity that can be upgraded. Storage racks can be purchased and placed, utilizing vertical space to increase storage capacity. Items on display do not take up storage space. 
