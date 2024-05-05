# Shakrn Meadowgreen



[Shakrn Meadowgreen](/npc/14075) is a level 29 Centaur Warrior that spawns in [Southern Plains of Karana](/zone/14).







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


if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_894.png" alt="" /> <a
                                href="/item/13743" data-url="13743" class="tooltip-link link">Goblin Fire Totem</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_964.png" alt="" /> <a
                                href="/item/10035" data-url="10035" class="tooltip-link link">Ruby</a>) then


>**Shakrn Meadowgreen says:** By the gods, a fire goblin totem! Well done, warrior! Here is your crafted helm. Wear it with pride, for it is a true warrior's helmet.


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_550.png" alt="" /> <a
                                href="/item/4173" data-url="4173" class="tooltip-link link">Crafted Helm</a> (+25000 exp)

 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1056.png" alt="" /> <a
                                href="/item/13737" data-url="13737" class="tooltip-link link">Aviak Charm</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_961.png" alt="" /> <a
                                href="/item/10032" data-url="10032" class="tooltip-link link">Star Ruby</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_961.png" alt="" /> <a
                                href="/item/10032" data-url="10032" class="tooltip-link link">Star Ruby</a>) then


>**Shakrn Meadowgreen says:** Ho ho! An aviak charm. These are not easy to come by. You have proven yourself a mighty warrior, and therefore deserve to wear these crafted warrior gauntlets.


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_531.png" alt="" /> <a
                                href="/item/4178" data-url="4178" class="tooltip-link link">Crafted Gauntlets</a> (+25000 exp)

 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_895.png" alt="" /> <a
                                href="/item/13744" data-url="13744" class="tooltip-link link">Goblin Frost Totem</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_963.png" alt="" /> <a
                                href="/item/10034" data-url="10034" class="tooltip-link link">Sapphire</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_963.png" alt="" /> <a
                                href="/item/10034" data-url="10034" class="tooltip-link link">Sapphire</a>) then


>**Shakrn Meadowgreen says:** What strength you must have to return with a frost goblin totem. You have surprised me - I did not think you up to the task. Take these crafted boots - you have indeed earned them.


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_524.png" alt="" /> <a
                                href="/item/4180" data-url="4180" class="tooltip-link link">Crafted Plate Boots</a> (+25000 exp)

 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_885.png" alt="" /> <a
                                href="/item/13739" data-url="13739" class="tooltip-link link">Griffon Eye</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_962.png" alt="" /> <a
                                href="/item/10033" data-url="10033" class="tooltip-link link">Fire Emerald</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_962.png" alt="" /> <a
                                href="/item/10033" data-url="10033" class="tooltip-link link">Fire Emerald</a>) then


>**Shakrn Meadowgreen says:** A griffon eye - I shall eat well tonight, and toast you in the manner of my ancestors. Take these crafted vambraces - they will serve you well.


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_622.png" alt="" /> <a
                                href="/item/4176" data-url="4176" class="tooltip-link link">Crafted Vambraces</a> (+25000 exp)

 

**This NPC *should* return incorrect items given.**



