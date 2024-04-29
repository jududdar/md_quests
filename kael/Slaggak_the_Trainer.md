# Slaggak the Trainer
## Dialog

if **Faction** >= Apprehensive then


**You say:** `hail`




>**Slaggak the Trainer says:** Hello there, " .. e.other:Race() .. ". I am Slaggak, the trainer. The Kromrif here will soon be ready to serve the great and honorable King Tormax.


**You say:** `serve`




>**Slaggak the Trainer says:** So you say, little one. Why are you here, then? You should be out slaying those pestering little Coldain or maybe those damnable shard wurms and wyverns.


**You say:** `coldain`




>**Slaggak the Trainer says:** The Coldain are the ice dwarves. They have defiled our lands for long enough. Thinking of them makes my blood run hot. With my new position as trainer, I am not allowed to roam the lands and slaughter their kind as I once did.' Slaggak sighs. 'I long for the days when I could fashion necklaces from their skulls.


**You say:** `shard wurm`




>**Slaggak the Trainer says:** You must have seen the shard wurms by now! The lizards that roam the lands eating whatever they can find? They can grow to be quite ferocious! Not nearly as ferocious as their ancient cousins, the dragons, but a nuisance nonetheless. We have a bounty on those beasts here in Kael Drakkel.


**You say:** `skull`




>**Slaggak the Trainer says:** Go from here and seek out the Coldain, slay them, and return to me with their heads. I wish to fashion four skull talismans as I once did. If you can do this for me, I will surely let King Tormax know of your deeds and reward you with a piece of armor from the Militia armory.


**You say:** `bounty`




>**Slaggak the Trainer says:** If you think you have what it takes to slay the shard wurms or their relatives, the wyverns, bring back proof of your exploits. For every four shard wurm fang you bring me, I am authorized to reward you with a pair of cerulean greaves. Every fourth ice wyvern stinger will grant you a pair of vambraces.


else


**Slaggak the Trainer says one of the following:**

>I didn't know Slime could speak common.  Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here?  Now go away!

>I wonder how much I could get for the tongue of a blithering fool?  Leave before I decide to find out for myself.
end

## Turn-Ins





if( **Faction is** > Dubious) then


if( **You turn in:** [Coldain Head](/item/30081), [Coldain Head](/item/30081), [Coldain Head](/item/30081), [Coldain Head](/item/30081)) then



>*Slaggak the Trainer looks down at you as you hold up the skulls of the wretched little dwarves.  'Excellent work, Soandso.  Here is your reward as promised.  A piece of prize armor crafted for war.*



* __Faction:__ [Kromrif](/faction/419) (40)



* __Faction:__ [Kromzek](/faction/448) (10)



* __Faction:__ [Coldain](/faction/406) (-20)



* __Faction:__ [Claws of Veeshan](/faction/430) (-4)



 **You receive:** eq.ChooseRandom( [Giant Scalemail Belt](/item/25011), 25016, 25013, 25010, 25017, 25014, 25007, 25005, 25015, 25009, 25006, 25012, 25018) (+50000 exp)


elseif( **You turn in:** [Shard Wurm Fang](/item/25100), [Shard Wurm Fang](/item/25100), [Shard Wurm Fang](/item/25100), [Shard Wurm Fang](/item/25100)) then



>**Slaggak the Trainer says:** Excellent work, Soandso.  Here is your reward as promised. A piece of prize armor crafted for war.



* __Faction:__ [Kromrif](/faction/419) (40)



* __Faction:__ [Kromzek](/faction/448) (10)



* __Faction:__ [Coldain](/faction/406) (-20)



* __Faction:__ [Claws of Veeshan](/faction/430) (-4)



 **You receive:**  [Cerulean Greaves](/item/25071) (+50000 exp)


elseif( **You turn in:** [Ice Wyvern Stinger](/item/25101), [Ice Wyvern Stinger](/item/25101), [Ice Wyvern Stinger](/item/25101), [Ice Wyvern Stinger](/item/25101)) then



>**Slaggak the Trainer says:** Excellent work, Soandso.  Here is your reward as promised. A piece of prize armor crafted for war.



* __Faction:__ [Kromrif](/faction/419) (40)



* __Faction:__ [Kromzek](/faction/448) (10)



* __Faction:__ [Coldain](/faction/406) (-20)



* __Faction:__ [Claws of Veeshan](/faction/430) (-4)



 **You receive:**  [Cerulean Vambraces](/item/25070) (+50000 exp)


**This NPC *should* return incorrect items given.**
