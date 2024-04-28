# Brutol Rhaksen
## Dialog

if(eq.get_current_expansion() >= 4.0) then


**You say:** `hail`




>**Brutol Rhaksen says:** Oh, hello down there, puny one. I'm Brutol Rhaksen. Commmander of warriors who [serve] the Dismal Rage, and that's really all you need to know..for now.


**You say:** `serve`




>**Brutol Rhaksen says:** You must become strong to survive amongst the ranks of the Dismal Rage. Take this note to Rolfic Gohar and he will help you get a suit of armor to protect your scrawny hide from the weapons of our enemies. Once you have been properly outfitted return to me and will give you your [next orders].



**You receive:**  [Note to Rolfic Gohar](/item/19843)


**You say:** `next orders`




>**Brutol Rhaksen says:** Ready to make yourself useful Soandso ? Beneath West Freeport are sewer tunnels leading to North Freeport being used by the Knights of Truth and the Sentries and Passion that have gained too much notoriety with the Freeport Militia and the Dismal Rage to pass safely through the eastern and western quarters of Freeport. We believe a sympathizer of the Sentries of Passion, Tarsa Yovar, is hiding somewhere in the western tunnel system. The sympathizer is a Steel Warrior faithful to Erollisi and although she is only a minor nuisance must be dealt with. Find her and bring me her head.

end


## Turn-Ins



local expansion_flag = eq.get_current_expansion();



if **You turn in:** [A tattered note](/item/18857)


>**Brutol Rhaksen says:** Hahaha.. I sure hope you prove more valuable than you look, little one.


* __Faction:__ [Dismal Rage](/faction/271) (100)


* __Faction:__ [Knights of Truth](/faction/281) (-15)


* __Faction:__ [Opal Darkbriar](/faction/296) (20)


 **You receive:**  [Faded Crimson Tunic*](/item/13561) (+20 exp)

elseif(expansion_flag >= 4.0 and  **You turn in:** [Tarsa Yovar's Head](/item/19932)


>**Brutol Rhaksen says:** Take this and get it sharpened. Bring it back to me with a Giant Rattlesnake Skin and you will have proven yourself able to wield a Dismal Rage Battle Axe, to help teach the way of Innoruuk!


 **You receive:**  [Dull Dismal Battleaxe](/item/19921) (+100 exp)

elseif(expansion_flag >= 4.0 and  **You turn in:** [Sharpened Dismal Battleaxe](/item/19926), [Giant Rattlesnake Skin](/item/19852)


>**Brutol Rhaksen says:** You have proven your faith Soandso. Take this to vanquish any and all whom question the absolute power of Innoruuk!


 **You receive:**  [Dismal Rage Battle Axe](/item/19938) (+100 exp)

**This NPC *should* return incorrect items given.**
;

