# Shakrn Meadowgreen




## Dialog

**You say:** `hail`



e.self:Say("Hail. I am Shakrn Meadowgreen, Warrior extraordinaire and Master Armorer of the Meadowgreen family. My brother and I craft [armor] for the bravest warriors in the land 

**You say:** `armor`



>**Shakrn Meadowgreen says:** I smith [Helms], [Gauntlets], [Boots] and [Vambraces]. My brother Ulan smiths Bracers, Greaves, Pauldruns and Breastplates.

**You say:** `qualify`



>**Shakrn Meadowgreen says:** So you are a warrior of renown?  [Prove] it to me and I will smith you [armor] befitting your exalted station.

**You say:** `prove`



>**Shakrn Meadowgreen says:** You will prove yourself to me the old fashioned way, by killing things and bringing me back proof of your deed.  Bah.  What other way is there?

**You say:** `helm`



>**Shakrn Meadowgreen says:** One of my brethren spoke to me of the mystic properties of the Fire Totems carried by the Goblin High Shaman in Solusek's Eye. My mighty Centaur body will not fit down those twisty goblin passages, so I have not been able to acquire one on my own. As proof of your powers, I ask you to bring me a Fire Totem and one [Ruby] stone. Do so and I will reward you with a Crafted Helmet.

**You say:** `gauntlets`



>**Shakrn Meadowgreen says:** Crafted gauntlets - the mark of a distinguished warrior. I have a personal grudge to settle with those twice-cursed aviaks. They have been raiding our merchant convoys for the last few weeks, causing mischief to no Bring me an aviak charm from an avocet. I am sure I will not need to tell you how to get it. An aviak charm and two [star rubies], and I will reward you with crafted gauntlets.

**You say:** `boots`



>**Shakrn Meadowgreen says:** One of my brethren spoke to me of the mystic properties of the Frost Totems carried by the Goblin High Shamans in Permafrost Keep. I have been unable to fetch one for myself, as my Centaur's body will not fit through the tunnels of those sniveling wretches. Prove your might by gifting me a Frost Totem and two [Sapphire] stones. Do this and I will reward you with a pair of Crafted Boots.

**You say:** `vambraces`



>**Shakrn Meadowgreen says:** Come, warrior, and speak to me of your strength. Bring me the eye of a griffon that I might eat it raw in the fashion of my ancestors. Do this for me - then gift me with two [fire emeralds], and for you I will make a crafted vambrace.

**You say:** `ruby`



>**Shakrn Meadowgreen says:** I need a ruby for a piece of jewelry my brother and I are creating.

**You say:** `star rubies`



>**Shakrn Meadowgreen says:** I need a star ruby for a piece of jewelry my brother and I are creating.

**You say:** `fire emerald`



>**Shakrn Meadowgreen says:** i need a fire emerald for a piece of jewelry my brother and I are creating.

**You say:** `sapphire`



>**Shakrn Meadowgreen says:** I need a sapphire for a piece of jewelry my brother and I are creating
end

## Turn-Ins



local text = "Wait, Soandso, are you not forgetting something?";


if( **You turn in:** [Goblin Fire Totem](/item/13743), [Ruby](/item/10035)) then


>**Shakrn Meadowgreen says:** By the gods, a fire goblin totem! Well done, warrior! Here is your crafted helm. Wear it with pride, for it is a true warrior's helmet.


 **You receive:**  [Crafted Helm](/item/4173) (+25000 exp)

elseif( **You turn in:** [Aviak Charm](/item/13737), [Star Ruby](/item/10032), [Star Ruby](/item/10032)) then


>**Shakrn Meadowgreen says:** Ho ho! An aviak charm. These are not easy to come by. You have proven yourself a mighty warrior, and therefore deserve to wear these crafted warrior gauntlets.


 **You receive:**  [Crafted Gauntlets](/item/4178) (+25000 exp)

elseif( **You turn in:** [Goblin Frost Totem](/item/13744), [Sapphire](/item/10034), [Sapphire](/item/10034)) then


>**Shakrn Meadowgreen says:** What strength you must have to return with a frost goblin totem. You have surprised me - I did not think you up to the task. Take these crafted boots - you have indeed earned them.


 **You receive:**  [Crafted Plate Boots](/item/4180) (+25000 exp)

elseif( **You turn in:** [Griffon Eye](/item/13739), [Fire Emerald](/item/10033), [Fire Emerald](/item/10033)) then


>**Shakrn Meadowgreen says:** A griffon eye - I shall eat well tonight, and toast you in the manner of my ancestors. Take these crafted vambraces - they will serve you well.


 **You receive:**  [Crafted Vambraces](/item/4176) (+25000 exp)

**This NPC *should* return incorrect items given.**



