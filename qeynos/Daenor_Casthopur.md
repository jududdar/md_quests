# Daenor Casthopur



[Daenor Casthopur](/npc/1053) is a level 61 Human GM Wizard that spawns in [South Qeynos](/zone/1).



## Dialog

local fac = e.other:GetFaction(e.self);

**You say:** `hail`



>**Daenor Casthopur says:** Ah, hello there, Soandso, and welcome to the Hall of Sorcery! I'm Daenor, a wizard of the Order of Three. I can help you practice your skills and learn some new ones.

**You say:** `neclo`



if(fac < 6) then 



>**Daenor Casthopur says:** Neclo Rheslar is an old friend of mine. Right now, he's out working in the Qeynos Hills. In fact, if you have some free time, you should go out and meet him. Here, if you go, take this note to him for me. Thanks, friend.



 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/18823" data-url="18823" class="tooltip-link link">Note to Neclo</a>


else



>**Daenor Casthopur says:** The Order of Three has been monitoring your recent activities, and we are appalled by you and your actions! Now, begone!

end



## Turn-Ins



**This NPC *should* return incorrect items given.**
