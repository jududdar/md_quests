# Ulraz S\`Lon



[Ulraz S\`Lon](/npc/42064) is a level 61 Dark Elf GM Shadow Knight that spawns in [Neriak - 3rd Gate](/zone/42).



## Dialog

if(eq.get_current_expansion() >= 4.0) then


**You say:** `Hail`




>**Ulraz S-Lon says:** So you are the next pathetic maggot I have the displeasure of training to be a useful Shadowknight of the Lodge of the Dead. First you must get yourself outfitted in a suit of [armor]. those rags you wear can not even contain the stench of your miserable hide and will do no good protecting it from the edge of an enemy's blade.


**You say:** `armor`




>**Ulraz S-Lon says:** Seek Krivn S'Tai in the Commoner quarter of Neriak and give him this request parchment. Krivn S'Tai has been paid in advance by the Lodge of the Dead for the requested service. Simply give him the request parchment and he will instruct you further. When you have outfitted yourself in a suit of armor return to the Lodge of the Dead and I will grant you [another task].



 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_868.png" alt="" /> <a
                                href="/item/19584" data-url="19584" class="tooltip-link link">Request Parchment</a>


**You say:** `task`




>**Ulraz S-Lon says:** Ah. you are eager to advance further within the Lodge of the Dead. Although it is my duty to aid your training. do not allow your arrogance to blind you to your lowly position amongst the Queens most loyal subjects. Your next task is to assist the construction of a [weapon] and [shield] worthy of being wielded by a Shadowknight of the Lodge of the Dead.


**You say:** `weapon`




>**Ulraz S-Lon says:** Beyond the mouth of Neriak lies the Nektulos Forest. There the walking dead can be found digging their way from the ashen soil of the [Ultricle]. their flesh cured and hardened and bones strengthened from the minerals and volcanic ash in which they rested in death. Return some of these undead to the rest they have abandoned and bring to me some Leathered Zombie Flesh, a Petrified Humerus bone, and a Petrified Rib bone.


**You say:** `shield`




>**Ulraz S-Lon says:** The bones of the dead that dig from their graves at the [Ultricle] in the Nektulos Forest have been strengthened by the minerals and ashen soil. Return some of these walking dead to the rest they have abandoned and bring to me four Petrified Femurs.


**You say:** `Ultricle`




>**Ulraz S-Lon says:** In the Nektulos Forest near the pass to the Lavastorm Mountains is a gray region barren of life whose boundaries are marked by carved stones displaying runes the color of freshly spilt blood. The area the runed stones mark is called the Ultricle. It is where the weak. dead. and dying Teir'Dal that have not earned a noble burial are left to rot and one day if they are lucky join the ranks of the Undead.


**You say:** `forge`




>**Ulraz S-Lon says:** There is a forge near the Blue Flame Armory in the Neriak Commons and in the Ogre section of the Foreign Quarter. Sharpening stones can be purchased from vendors who deal in blacksmithing supplies.

end



## Turn-Ins



local expansion_flag = eq.get_current_expansion();

if(expansion_flag >= 4.0 and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_924.png" alt="" /> <a
                                href="/item/19574" data-url="19574" class="tooltip-link link">Leathered Zombie Flesh</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_905.png" alt="" /> <a
                                href="/item/16197" data-url="16197" class="tooltip-link link">Petrified Humerus</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_907.png" alt="" /> <a
                                href="/item/19554" data-url="19554" class="tooltip-link link">Petrified Rib</a>) then


>**Ulraz S-Lon says:** Well, you're not completely useless, afterall. Take this sword and sharpen it. Then, return it to me.


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_821.png" alt="" /> <a
                                href="/item/19572" data-url="19572" class="tooltip-link link">Rough Sword Blade</a> 

 

elseif(expansion_flag >= 4.0 and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_821.png" alt="" /> <a
                                href="/item/19573" data-url="19573" class="tooltip-link link">Sharpened Sword Blade</a>) then


>**Ulraz S-Lon says:** I'm surprised, I really am. I didn't think somebody like you could pull it off. Here, take this before I change my mind.


Your faction standing with [The Dead](/faction/239) got better (<span class='text-success'>+15</span>)


Your faction standing with [Queen Cristanos Thex](/faction/303) got better (<span class='text-success'>+2</span>)


Your faction standing with [King Naythox Thex](/faction/278) got worse (<span class='text-danger'>-2</span>)


Your faction standing with [Keepers of the Art](/faction/275) got worse (<span class='text-danger'>-2</span>)


Your faction standing with [Eldritch Collective](/faction/245) got worse (<span class='text-danger'>-2</span>)


Your faction standing with [Primordial Malice](/faction/1522) got worse (<span class='text-danger'>-30</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_590.png" alt="" /> <a
                                href="/item/19607" data-url="19607" class="tooltip-link link">Bone Hilted Long Sword</a> (+1000 exp)

 

elseif(expansion_flag >= 4.0 and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_905.png" alt="" /> <a
                                href="/item/19570" data-url="19570" class="tooltip-link link">Petrified Femur</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_905.png" alt="" /> <a
                                href="/item/19570" data-url="19570" class="tooltip-link link">Petrified Femur</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_905.png" alt="" /> <a
                                href="/item/19570" data-url="19570" class="tooltip-link link">Petrified Femur</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_905.png" alt="" /> <a
                                href="/item/19570" data-url="19570" class="tooltip-link link">Petrified Femur</a>) then


>*Ulraz S-Lon fashions the petrified femurs into a shield frame. This will be the frame of your new shield. Return now again to the Nektulos Forest, in the gray ashen region of the forest near the Lavastorm mountains the basilisks often come down from the fiery peaks to lay their eggs in the ashen soil. Basilisk hatchlings can be found there as they make their way towards the warmer interior of the mountains. Hunt these basilisk hatchlings and gather two Basilisk Hatchling Skins. Once this is done take the skins and frame to Medron Y'Lask at the Furrier Royale.*


Your faction standing with [The Dead](/faction/239) got better (<span class='text-success'>+15</span>)


Your faction standing with [Queen Cristanos Thex](/faction/303) got better (<span class='text-success'>+2</span>)


Your faction standing with [King Naythox Thex](/faction/278) got worse (<span class='text-danger'>-2</span>)


Your faction standing with [Keepers of the Art](/faction/275) got worse (<span class='text-danger'>-2</span>)


Your faction standing with [Eldritch Collective](/faction/245) got worse (<span class='text-danger'>-2</span>)


Your faction standing with [Primordial Malice](/faction/1522) got worse (<span class='text-danger'>-30</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_805.png" alt="" /> <a
                                href="/item/19571" data-url="19571" class="tooltip-link link">Petrified Femur Shield Frame</a> (+1000 exp)

 

**This NPC *should* return incorrect items given.**







