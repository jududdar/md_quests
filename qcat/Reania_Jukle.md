# Reania Jukle
## Dialog

**You say:** `hail`



>**Reania Jukle says:** Greetings, Soandso. What can I help you with?

**You say:** `what is the ink of the dark`



>**Reania Jukle says:** Ink of the Dark, you say? That isn't an everyday item, you know. In fact, I can't remember the last time someone requested it. I have given up keeping any here with me. You are going to need to find your own supply now. Sorry.

**You say:** `find the ink of the dark`



>**Reania Jukle says:** The ink is the blood of a dark scribe. Tempt him and give him this vial. He should cooperate.


**You receive:**  [Empty Ink Vial](/item/10626)


local enchant_bars_lib = require("self_found_enchant_bars");

enchant_bars_lib.check_bars_quest_dialogue(e.self, e.other, e.message);
## Turn-Ins





if( **You turn in:** [Blood Stained Note](/item/18851)) then 


* __Faction:__ [Bloodsabers](/faction/221) (100)


* __Faction:__ [Guards of Qeynos](/faction/262) (-15)


* __Faction:__ [Opal Darkbriar](/faction/296) (10)


* __Faction:__ [Priests of Life](/faction/341) (-25)


* __Faction:__ [Corrupt Qeynos Guards](/faction/230) (5)


 **You receive:**  [Dirty Purple Robe*](/item/13596) (+20 exp)


local enchant_bars_lib = require("self_found_enchant_bars");

enchant_bars_lib.check_for_bars_to_enchant(item_lib, e.self, e.other, e.trade);


**This NPC *should* return incorrect items given.**
;





