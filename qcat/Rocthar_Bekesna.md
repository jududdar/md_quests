# Rocthar Bekesna



[Rocthar Bekesna](/npc/45080) is a level 61 Human GM Warrior that spawns in [Qeynos Aqueduct System](/zone/45).



## Dialog

if(eq.get_current_expansion() >= 4.0) then


**You say:** `hail`




>**Rocthar Bekesna says:** I've little time for banter, unless you have come to me for training as a [new warrior] of the Bloodsabers move along.


**You say:** `new warrior`




>**Rocthar Bekesna says:** A warrior want to be is more like it. You've got a lot of work to do if you're going to be a valued member of the temple of Bertoxxulous, the Plague Bringer. That pompous ruler Antonius Bayle IV has this city in a tight grip with the support of our enemies, the temples of Rodcet Nife and Karana. It is not safe for us to walk the streets of Qeynos openly. You must learn to hold your tongue when not within the walls of our temple here in the Qeynos Catacombs. Should the Qeynos Guards discover your devotion to the Plague Bringer they would surely execute you. We have enemies all about and you must [learn to defend] yourself.


**You say:** `learn to defend`




>**Rocthar Bekesna says:** Take this note to Illie Roln. She will help get you outfitted in a suit of armor. Once you have been properly outfitted return to me and I will tell you how you can make yourself useful. I have a [small task] in mind.



 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_864.png" alt="" /> <a
                                href="/item/20205" data-url="20205" class="tooltip-link link">Note to Illie Roln</a>


**You say:** `small task`




>**Rocthar Bekesna says:** The Priests of Life and Knights of Thunder often travel the roads from Qeynos carrying messages for the farmers of the Plains of Karana and the Knights of Truth in Freeport on the opposite coast of Antonica. We have recently been sending Bloodsabers to the Plains of Karana in search of a possible location for a new hidden temple should the need arise. One of the messengers of the Knights of Thunder has alerted the peasants of the plains the possibility of a Bloodsaber presence there and is using them to track our motions. Find the messenger, Lukas Hergo, and bring me his head.

end



## Turn-Ins



local expansion_flag = eq.get_current_expansion();

if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_864.png" alt="" /> <a
                                href="/item/18853" data-url="18853" class="tooltip-link link">Blood Stained Note</a>) then 


Your faction standing with [Bloodsabers](/faction/221) got better (<span class='text-success'>+100</span>)


Your faction standing with [Guards of Qeynos](/faction/262) got worse (<span class='text-danger'>-15</span>)


Your faction standing with [Opal Darkbriar](/faction/296) got better (<span class='text-success'>+10</span>)


Your faction standing with [Priests of Life](/faction/341) got worse (<span class='text-danger'>-25</span>)


Your faction standing with [Corrupt Qeynos Guards](/faction/230) got better (<span class='text-success'>+5</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_678.png" alt="" /> <a
                                href="/item/13598" data-url="13598" class="tooltip-link link">Ruined Training Tunic*</a> (+20 exp)

 

elseif(expansion_flag >= 4.0 and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_982.png" alt="" /> <a
                                href="/item/20175" data-url="20175" class="tooltip-link link">Lukas Hergo's Head</a>) then


>**Rocthar Bekesna says:** Well done Soandso. Now take this Rusty Scourge Warrior Broadsword to a forge and sharpen it with a sharpening stone. It may take you several attempts if you are unfamiliar with the process. Once that is done take the Tarnished Scourge Warrior Sword and a Giant King Snake Skin to Illie Roln and he will put the finishing touches on the weapon.


Your faction standing with [Bloodsabers](/faction/221) got better (<span class='text-success'>+10</span>)


Your faction standing with [Guards of Qeynos](/faction/262) got worse (<span class='text-danger'>-1</span>)


Your faction standing with [Opal Darkbriar](/faction/296) got worse (<span class='text-danger'>-1</span>)


Your faction standing with [Priests of Life](/faction/341) got worse (<span class='text-danger'>-2</span>)


Your faction standing with [Corrupt Qeynos Guards](/faction/230) got better (<span class='text-success'>+1</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_590.png" alt="" /> <a
                                href="/item/20176" data-url="20176" class="tooltip-link link">Rusty Scourge Warrior Broadsword</a> (+500 exp)

 

**This NPC *should* return incorrect items given.**
