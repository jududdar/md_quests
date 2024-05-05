# Kaxon Frennor



[Kaxon Frennor](/npc/55122) is a level 61 Gnome GM Rogue that spawns in [Ak'Anon](/zone/55).





## Dialog

local expansion_flag = eq.get_current_expansion();

if(eq.get_current_expansion() >= 4.0) then


**You say:** `hail`




>**Kaxon Frennor says:** Hail Soandso. I am Kaxon Frennor, master assassin of the Dark Reflection. I train talented gnomes that feel the calling of the Plaguelord, Bertoxxulous, and wish to [serve as a rogue] of the Dark Reflection. Disease and decay are powerful forces in Norrath that crumble kingdoms and silently kill even the mightiest of heros. It is the calling of the Dark Reflection to sow the seeds of destruction as a catalyst to change. What progress would there be if rulers did not die and clockworks did not malfunction, giving way to greater rulers and better clockworks.


**You say:** `serve as a rogue`




>**Kaxon Frennor says:** We are the spreaders of disease, the masters of poison, the death that comes silently from the shadows. You must outfit yourself with the tools of a rogue, crafted from the disassembled remains of clockworks that are finished serving the purpose for which they were built. Take this parchment to Rebbie Romblerum, he will assist you in the construction of a suit of armor. When you have been properly outfitted return to me for your [next task].



 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_868.png" alt="" /> <a
                                href="/item/10988" data-url="10988" class="tooltip-link link">Parchment to Rebbie</a>


**You say:** `next task`




>**Kaxon Frennor says:** There are many of our kind that do not understand the necessity of the Dark Reflection. The Eldrich Collective and The Deep Muses seek to root us out and have us put to death or exiled from Ak'Anon. In the Steamfont Mountains a Rogue of the Deep Muses, Jibble Blexnik, has been hunting and killing young members of the Dark Reflection that venture from Ak'Anon. Find this self-righteous rogue and eliminate him. When you have accomplished this task bring me Jibble's Stiletto.


else


**You say:** `hail`




>**Kaxon Frennor says:** Hail Soandso. I am Kaxon Frennor, master assassin of the Dark Reflection. I train talented gnomes that feel the calling of the Plaguelord, Bertoxxulous, and wish to serve as a rogue of the Dark Reflection. Disease and decay are powerful forces in Norrath that crumble kingdoms and silently kill even the mightiest of heros. It is the calling of the Dark Reflection to sow the seeds of destruction as a catalyst to change. What progress would there be if rulers did not die and clockworks did not malfunction, giving way to greater rulers and better clockworks.



end



## Turn-Ins

local expansion_flag = eq.get_current_expansion();



if (expansion_flag >= 4.0 and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_591.png" alt="" /> <a
                                href="/item/10992" data-url="10992" class="tooltip-link link">Jibble's Stiletto</a>) then


>**Kaxon Frennor says:** At last that haughty rogue has met his Take this Dull Dark Reflection Stiletto and sharpen it in a forge with a sharpening stone. It may take several attempts if you are unfamiliar with the process. Once the blade has been sharpened take the sharpened stiletto to Clockwork Smith XIII with a Giant Rat Pelt and he will put the finishing touches on your new weapon.


Your faction standing with [Dark Reflection](/faction/238) got better (<span class='text-success'>+10</span>)



Your faction standing with [Eldritch Collective](/faction/245) got worse (<span class='text-danger'>-1</span>)



Your faction standing with [Gem Choppers](/faction/255) got worse (<span class='text-danger'>-1</span>)


Your faction standing with [Deepmuses](/faction/240) got worse (<span class='text-danger'>-1</span>)



 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_591.png" alt="" /> <a
                                href="/item/10997" data-url="10997" class="tooltip-link link">Dull Dark Reflection Stiletto</a> (+100 exp)

 

elseif ( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/18705" data-url="18705" class="tooltip-link link">Old Folded Letter</a>) then 


Your faction standing with [Dark Reflection](/faction/238) got better (<span class='text-success'>+100</span>)



Your faction standing with [Eldritch Collective](/faction/245) got worse (<span class='text-danger'>-10</span>)



Your faction standing with [Gem Choppers](/faction/255) got worse (<span class='text-danger'>-10</span>)


Your faction standing with [Deepmuses](/faction/240) got worse (<span class='text-danger'>-10</span>)



 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_678.png" alt="" /> <a
                                href="/item/13518" data-url="13518" class="tooltip-link link">Tin Patched Tunic*</a> (+20 exp)

 


**This NPC *should* return incorrect items given.**
