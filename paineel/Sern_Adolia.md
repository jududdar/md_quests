# Sern Adolia
## Dialog

**You say:** `hail`



>**Sern Adolia says:** I hope you have a good reason for disturbing my contemplations. Perhaps you [seek the knowledge] of those who meditate within this Temple of Fear?

**You say:** `seek.* knowledge`



>**Sern Adolia says:** It is the secrets of Fear you seek, but first you must prove your devotion to our temple. There are pack rats within the city that have a habit of getting into things. Some of these rats have ingested a concoction developed by the necromancers of this great city. The rats have since died and, due to the concoction, their undead corpses now roam the fields. Bring me four livers from these undead rats so that we may examine them.

**You say:** `duties`



if **Faction** >= Amiable then



>**Sern Adolia says:** The primary duty of this temple is to spread terror, fright, and dread as a symbol of your devotion to our lord Cazic Thule. We are currently researching a means of summoning avatars of Fright, Terror and Dread, the primary minions of the Faceless in his home plane. Will you [assist me in summoning] the avatar of Fright?


elseif **Faction** >= Indifferent then



>**Sern Adolia says:** I sense the potential to learn the ways of fear within you. Continue striving to master your fear and one day perhaps you can be of service to our Lord Cazic-Thule.




else



>**Sern Adolia says:** Begone from this place! Infidels like you have no place among the faithful of Cazic-Thule!


**You say:** `assist`



if **Faction** >= Amiable then



>**Sern Adolia says:** In order to summon the avatar of Fright. I require some special components for the ritual. Fetch me the flesh of a zombie. the dust used in the process of mummification. [charred bone chips]. and a [vial of Tunare's Breath].


elseif **Faction** >= Indifferent then



>**Sern Adolia says:** I sense the potential to learn the ways of fear within you. Continue striving to master your fear and one day perhaps you can be of service to our Lord Cazic-Thule.


else



>**Sern Adolia says:** Begone from this place! Infidels like you have no place among the faithful of Cazic-Thule!


**You say:** `chips`



>**Sern Adolia says:** Some time ago a necromancer by the name of Obretl was sent to slay Rathmana Allin and his abomination of an adopted son. Ortallius. Obretl failed in his task and now haunts a small ruin in the desert of Ro cursed by Solusek to wallow in his failure in the form of a burning skeleton. Slay Obretl to free him from his pathetic existence and gather his charred remains.

**You say:** `vial`



>**Sern Adolia says:** Tunare's Breath is a life-giving potion created by the Fier'Dal Soldiers of Tunare. Seek out the druid Kalayia who is known to wander the Faydarks in search of reagents for potions. Procure from her a vial of Tunare's Breath. Shed her blood if need be.
end

## Turn-Ins



local text = "I need no fewer than four infected rat livers!! Now, go get me what I require!!";

local text1 = "I require all four reagents, anything less is useless. Incompetence will get you nowhere amongst the faithful of Cazic-Thule!";


if( **You turn in:** [Harbingers of Fear Guild Note](/item/18019)) then 


>**Sern Adolia says:** You are welcomed into the fold. Now go out. and prove yourself. young one. You have much to learn about the Dark Truth.


* __Faction:__ [Heretics](/faction/265) (100)


* __Faction:__ [Deepwater Knights](/faction/242) (-100)


* __Faction:__ [Gate Callers](/faction/254) (-100)


* __Faction:__ [Craftkeepers](/faction/231) (-100)


* __Faction:__ [Crimson Hands](/faction/233) (-100)


 **You receive:**  [Blood Splattered Tunic](/item/13573) (+20 exp)

elseif **Faction** >= Indifferent and  **You turn in:** [Infected Rat Livers](/item/13270), [Infected Rat Livers](/item/13270), [Infected Rat Livers](/item/13270), [Infected Rat Livers](/item/13270)) then


>**Sern Adolia says:** Well done, go now and continue your contemplations of fear. Keep up with your [duties] and you will soon be reaping the rewards granted by our Lord Cazic-Thule!!


* __Faction:__ [Heretics](/faction/265) (5)


* __Faction:__ [Craftkeepers](/faction/231) (-5)


* __Faction:__ [Crimson Hands](/faction/233) (-5)


* __Faction:__ [Deepwater Knights](/faction/242) (-5)


* __Faction:__ [Gate Callers](/faction/254) (-5)


 **You receive:**  [Initiate Symbol of Cazic Thule](/item/1437) (+500 exp)

elseif **Faction** >= Amiable and  **You turn in:** [Zombie Skin](/item/13074), [Embalming Dust](/item/16990), [Charred Bone Chips](/item/14102), [Vial of Tunares Breath](/item/14103)) then


>**Sern Adolia says:** Excellent Job Soandso. These components will help with our research immeasurably. You will soon be reaping the rewards granted by our Lord Cazic-Thule!! If you want to further assist our research effots, talk to Atdehim Sqonci.


* __Faction:__ [Heretics](/faction/265) (30)


* __Faction:__ [Craftkeepers](/faction/231) (-30)


* __Faction:__ [Crimson Hands](/faction/233) (-30)


* __Faction:__ [Deepwater Knights](/faction/242) (-30)


* __Faction:__ [Gate Callers](/faction/254) (-30)


 **You receive:**  [Fright Forged Helm](/item/14100) (+1000 exp)

**This NPC *should* return incorrect items given.**






