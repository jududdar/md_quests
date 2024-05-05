# Narex T\`Vem



[Narex T\`Vem](/npc/41030) is a level 61 Dark Elf GM Warrior that spawns in [Neriak - Commons](/zone/41).






## Dialog

**You say:** `Hail`



>**Narex T-Vem says:** Welcome to the Cauldron of Hate. If you are a young warrior, you have come to the right place. There are many [duties] to be performed. If you are a veteran of the blade, we welcome your return to service. Perhaps you return with a [Leatherfoot] skullcap?

**You say:** `duties`



if **Faction** >= Amiable then



>**Narex T-Vem says:** I am so glad you asked. There is one matter of importance with which you may be able to assist. It seems an Erudite has made camp in Lavastorm. He is powerful and we do not expect you to slay him. Your mission is to cut off his supply line. I hope you will [accept the mission].


elseif **Faction** >= Indifferent then



>**Narex T-Vem says:** Go! Return when you have done more to serve the Indigo Brotherhood of Neriak. Fewer Leatherfoot Raiders in Nektulos and a few Leatherfoot skullcaps in the palms of Master Narex shall prove your true warrior nature and loyalty to our house.


else



>**Narex T-Vem says:** Your head will make a fine trophy in the halls of the Indigo Brotherhood.




**You say:** `accept the mission`



if **Faction** >= Amiable then



>**Narex T-Vem says:** Go to the Lavastorm Mountain Range. It is a dangerous place, but the one you seek must leave by the direction you entered. He is a goblin. Apparently the Erudite is employing their strength. The fire goblin runner shall be an easy kill for you. At least, he should be. Return his runner pouch to me.


elseif **Faction** >= Indifferent then



>**Narex T-Vem says:** Go! Return when you have done more to serve the Indigo Brotherhood of Neriak. Fewer Leatherfoot Raiders in Nektulos and a few Leatherfoot skullcaps in the palms of Master Narex shall prove your true warrior nature and loyalty to our house.


else



>**Narex T-Vem says:** Your head will make a fine trophy in the halls of the Indigo Brotherhood.




**You say:** `leatherfoot`



if **Faction** >= Amiable then



>**Narex T-Vem says:** Where have you been? The halflings of Rivervale have an elite force of warriors. They are called the Leatherfoot Raiders. They have been infiltrating our glorious city of Neriak for quite some time. They must be exterminated! I must hire strong warriors who wish to [collect the bounty].


elseif **Faction** >= Indifferent then



>**Narex T-Vem says:** Go! Return when you have done more to serve the Indigo Brotherhood of Neriak. Fewer Leatherfoot Raiders in Nektulos and a few Leatherfoot skullcaps in the palms of Master Narex shall prove your true warrior nature and loyalty to our house.


else



>**Narex T-Vem says:** Your head will make a fine trophy in the halls of the Indigo Brotherhood.




**You say:** `collect the bounty`



if **Faction** >= Amiable then



>**Narex T-Vem says:** So you wish to collect the bounty on Leatherfoot Raiders? Then go into Nektulos and hunt them down. I shall pay a reward for no fewer than four Leatherfoot Raider skullcaps.


elseif **Faction** >= Indifferent then



>**Narex T-Vem says:** Go! Return when you have done more to serve the Indigo Brotherhood of Neriak. Fewer Leatherfoot Raiders in Nektulos and a few Leatherfoot skullcaps in the palms of Master Narex shall prove your true warrior nature and loyalty to our house.


else



>**Narex T-Vem says:** Your head will make a fine trophy in the halls of the Indigo Brotherhood.



end



## Turn-Ins



local text = "Fool! There shall be no reward until I have four skullcaps in my hands!";



if **Faction** >= Amiable and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_690.png" alt="" /> <a
                                href="/item/13886" data-url="13886" class="tooltip-link link">Goblin Supply Pouch</a>) then 


>**Narex T-Vem says:** Fine work. I trust the denizens of Lavastorm were not unkind. Please take this featherweight pouch as a reward. May it keep you fleet of foot.


Your faction standing with [Indigo Brotherhood](/faction/270) got better (<span class='text-success'>+25</span>)


Your faction standing with [Emerald Warriors](/faction/326) got worse (<span class='text-danger'>-3</span>)


Your faction standing with [Steel Warriors](/faction/311) got worse (<span class='text-danger'>-1</span>)


Your faction standing with [Primordial Malice](/faction/1522) got worse (<span class='text-danger'>-50</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_690.png" alt="" /> <a
                                href="/item/17972" data-url="17972" class="tooltip-link link">Featherweight Pouch</a> (+17150 exp)

 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_640.png" alt="" /> <a
                                href="/item/13113" data-url="13113" class="tooltip-link link">Leatherfoot Raider Skullcap</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_640.png" alt="" /> <a
                                href="/item/13113" data-url="13113" class="tooltip-link link">Leatherfoot Raider Skullcap</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_640.png" alt="" /> <a
                                href="/item/13113" data-url="13113" class="tooltip-link link">Leatherfoot Raider Skullcap</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_640.png" alt="" /> <a
                                href="/item/13113" data-url="13113" class="tooltip-link link">Leatherfoot Raider Skullcap</a>) then 


>**Narex T-Vem says:** I had my doubts, but you have proven them false. You are a fine warrior. You must continue to refine you talents. I reward you with the footman's voulge! Welcome into our house of warriors. Let us share skills as we share foes.


Your faction standing with [Indigo Brotherhood](/faction/270) got better (<span class='text-success'>+50</span>)


Your faction standing with [Emerald Warriors](/faction/326) got worse (<span class='text-danger'>-7</span>)


Your faction standing with [Steel Warriors](/faction/311) got worse (<span class='text-danger'>-2</span>)


Your faction standing with [Primordial Malice](/faction/1522) got worse (<span class='text-danger'>-100</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_736.png" alt="" /> <a
                                href="/item/12257" data-url="12257" class="tooltip-link link">Footmans Voulge</a> (+25000 exp)

**You receive coin:** 0 <img src='/static/icons/item_644.png' width='14' height='14'/> 7 <img src='/static/icons/item_645.png' width='14' height='14'/> 0 <img src='/static/icons/item_646.png' width='14' height='14'/> 0 <img src='/static/icons/item_647.png' width='14' height='14'/> 

**This NPC *should* return incorrect items given.**






