# Thomas



[Thomas](/npc/50236) is a level 61 Human GM Paladin that spawns in [Rathe Mountains](/zone/50).



## Dialog

**You say:** `hail`



>**Thomas says:** Welcome to our camp.  We are paladins gathered from many lands. We have been called to this land by our deities.  Ours is a crusade of righteousness.  Have you happened upon us by chance or do you [seek the sacred molds]?

**You say:** `helm of ro`



if **Faction** >= Indifferent +50 then



>**Thomas says:** To receive the mold of the Helm of Ro you must first demonstrate your strength.  Go to the plains of thunder.  There you shall hunt down the most vile creatures I have ever encountered.  Seek the undead cyclopes.  I have spied them in the most dangerous portions of my realm. Fetch me two of their skulls.


elseif **Faction** >= Indifferent then



>**Thomas says:** I cannot fully trust you.  You must venture to the city of Qeynos.  There you shall find the Temple of Thunder.  It is there that you shall find ways to prove your nobility.




else



>**Thomas says:** You have proven yourself not only an enemy of the Knights of Thunder, but an enemy of Karana himself. Now leave, sewer rat!



**You say:** `seek the sacred molds`



>**Thomas says:** Many of us carry the sacred molds of the holy paladin armor.  We will release it only to those who have proven themselves to each of our deities.  If you seek it, speak up!! Tell us which part you seek.  I carry the secret of the [Helm of Ro].  The others carry those of vambraces, breastplates, bracers, gauntlets, greaves and boots of Ro.

**You say:** `Lord Searfire`



>**Thomas says:** Lord Searfire is a great forge master.  He was called forth to the land of fire lakes.  It is said that he now toils in the name of Solusek Ro within a hidden temple of that land.  He and he alone knows how to obtain [ronium], a needed component for forging the sacred Armor of Ro.

**You say:** `ronium`



>**Thomas says:** It is an alloy created from two rare metals.  Only [Lord Searfire] knows the formula.
end



## Turn-Ins



local text = "I called for two cyclops skulls.";


if **Faction** >= Indifferent +50 and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1070.png" alt="" /> <a
                                href="/item/12308" data-url="12308" class="tooltip-link link">Cyclops skull</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1070.png" alt="" /> <a
                                href="/item/12308" data-url="12308" class="tooltip-link link">Cyclops skull</a>) then


>**Thomas says:** You have proven yourself to Karana.  I grant you the mold of the Ro Helm.  May the winds of Karana blow in your favor.  Now you must seek out [Lord Searfire] and  ask him for [ronium] to complete the second and only other component needed to be fashioned by a master blacksmith.


Your faction standing with [Knights of Thunder](/faction/280) got better (<span class='text-success'>+20</span>)


Your faction standing with [Bloodsabers](/faction/221) got worse (<span class='text-danger'>-20</span>)


Your faction standing with [Priests of Life](/faction/341) got better (<span class='text-success'>+15</span>)


Your faction standing with [Guards of Qeynos](/faction/262) got better (<span class='text-success'>+15</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1151.png" alt="" /> <a
                                href="/item/12298" data-url="12298" class="tooltip-link link">Mold of Ro Helm</a> 

 

**This NPC *should* return incorrect items given.**







