# Lashun Novashine



[Lashun Novashine](/npc/2032) is a level 5 Human Cleric that spawns in [North Qeynos](/zone/2).



## Dialog

**You say:** `hail`



>**Lashun Novashine says:** Well met, Soandso. My name is Lashun Novashine and I am a humble priest of [Rodcet Nife], the Prime Healer. I wish to spread His word to every corner of Norrath. My job gets more difficult each day with so many so willing to take lives rather than preserve them.

**You say:** `rodcet nife`



>**Lashun Novashine says:** Rodcet Nife is the Prime Healer. It is He who protects the health and well-being of the people of Norrath. The Temple of Life in North Qeynos is dedicated to His glory. I am but one of His loyal clerics who seek to cure all disease and heal all wounds.

**You say:** `heal`



>**Lashun Novashine says:** Rodcet wills us to cure and heal all who seek it. But He asks that you pay a price in return. I can cure diseases with a small donation of 2 gold pieces. I can also heal your wounds, but as proof of your desire to rid Norrath of the evil of Bertoxxulous and as an offering to the Prime Healer, you must bring me 2 bone chips from the undead that roam these hills.

**You say:** `bertoxxulous`



>**Lashun Novashine says:** Bertoxxulous is the fiend who rules the Plane of Disease. His followers are the Temple of Life's greatest foes. We believe a sect of his disciples known as the Bloodsabers are at this moment planning to make Qeynos a breeding ground for all sorts of terrible plagues.

**You say:** `temple`



>**Lashun Novashine says:** The lost shall find salvation in the Temple of Life! Follow me if you wish. I was just on my way back there.



eq.move_to(0,0,4,0,false);
end



## Arrive at Waypoint Script

if(e.wp == 13 or e.wp == 14 or e.wp == 15) then


**Lashun Novashine shouts:** <span class="text-danger">Cease this endless conflict and seek salvation in the Temple of Life! The glory of Rodcet Nife awaits you!</span>

elseif(e.wp == 57) then


>**Lashun Novashine says:** Greetings, people of Qeynos! Are you lost? Has the chaotic life of an adventurer left you empty and alone? Seek redemption in the glorious light of the Prime Healer. Only through Rodcet Nife and the Temple of Life will you find true health and salvation.
end



## Turn-Ins







if( **You turn in:** gold = 2) then


>**Lashun Novashine says:** Thank you for the donation to the Temple of Life. May Rodcet Nife cleanse your body of all ills.


**Lashun Novashine casts:** [Cure Disease](/spell/213) on target.





Your faction standing with [Priests of Life](/faction/341) got better (<span class='text-success'>+1</span>)


Your faction standing with [Knights of Thunder](/faction/280) got better (<span class='text-success'>+1</span>)


Your faction standing with [Guards of Qeynos](/faction/262) got better (<span class='text-success'>+1</span>)


Your faction standing with [Bloodsabers](/faction/221) got worse (<span class='text-danger'>-1</span>)


Your faction standing with [Antonius Bayle](/faction/219) got better (<span class='text-success'>+1</span>)




 &#127873; **You receive:** 0 (+1 exp)

 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_804.png" alt="" /> <a
                                href="/item/13073" data-url="13073" class="tooltip-link link">Bone Chips</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_804.png" alt="" /> <a
                                href="/item/13073" data-url="13073" class="tooltip-link link">Bone Chips</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_804.png" alt="" /> <a
                                href="/item/13073" data-url="13073" class="tooltip-link link">Bone Chips</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_804.png" alt="" /> <a
                                href="/item/13073" data-url="13073" class="tooltip-link link">Bone Chips</a>) then 


local times = 2


repeat



>**Lashun Novashine says:** Very well, young one. May the light of the Prime Healer wash away your scars.



**Lashun Novashine casts:** [Minor Healing](/spell/200) on target.







Your faction standing with [Priests of Life](/faction/341) got better (<span class='text-success'>+1</span>)



Your faction standing with [Knights of Thunder](/faction/280) got better (<span class='text-success'>+1</span>)



Your faction standing with [Guards of Qeynos](/faction/262) got better (<span class='text-success'>+1</span>)



Your faction standing with [Bloodsabers](/faction/221) got worse (<span class='text-danger'>-1</span>)



Your faction standing with [Antonius Bayle](/faction/219) got better (<span class='text-success'>+1</span>)





 &#127873; **You receive:** 0 (+200 exp)

 



times = times - 1


until times <= 0




elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_804.png" alt="" /> <a
                                href="/item/13073" data-url="13073" class="tooltip-link link">Bone Chips</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_804.png" alt="" /> <a
                                href="/item/13073" data-url="13073" class="tooltip-link link">Bone Chips</a>) then


>**Lashun Novashine says:** Very well, young one. May the light of the Prime Healer wash away your scars.


**Lashun Novashine casts:** [Minor Healing](/spell/200) on target.





Your faction standing with [Priests of Life](/faction/341) got better (<span class='text-success'>+1</span>)


Your faction standing with [Knights of Thunder](/faction/280) got better (<span class='text-success'>+1</span>)


Your faction standing with [Guards of Qeynos](/faction/262) got better (<span class='text-success'>+1</span>)


Your faction standing with [Bloodsabers](/faction/221) got worse (<span class='text-danger'>-1</span>)


Your faction standing with [Antonius Bayle](/faction/219) got better (<span class='text-success'>+1</span>)




 &#127873; **You receive:** 0 (+200 exp)

 

**This NPC *should* return incorrect items given.**
