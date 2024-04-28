# Glyssa Sonshaw

## Dialog

local enchant_bars_lib = require("self_found_enchant_bars");

enchant_bars_lib.check_bars_quest_dialogue(e.self, e.other, e.message);
## Turn-Ins



local text = "I require the parchment from Leraena as well as the Odd Cold Iron Necklace.";


if **You turn in:** [Sealed Parchment](/item/1772), [Odd Cold Iron Necklace](/item/14585)


>**Glyssa Sonshaw says:** Ah..yes, I have seen this symbol before. There is a kobold that lives among the gnomes of Ak'anon. He may be reluctant to speak with you but you have no need to fear him. He is a follower of Brell Serilis and a valuable source of information on kobold society and culture. I will construct a message for him. Deliver the message and necklace and perhaps he can enlighten you to its meaning.


* __Faction:__ [Arcane Scientists](/faction/220) (10)


* __Faction:__ [Knights of Truth](/faction/281) (2)


* __Faction:__ [Opal Darkbriar](/faction/296) (-1)


* __Faction:__ [The Freeport Militia](/faction/330) (-1)


 **You receive:**  [Odd Cold Iron Necklace](/item/14585) (+1000 exp)


 **You receive:**  [Sealed Parchment](/item/1779) 


local enchant_bars_lib = require("self_found_enchant_bars");


enchant_bars_lib.check_for_bars_to_enchant(item_lib, e.self, e.other, e.trade);


**This NPC *should* return incorrect items given.**


