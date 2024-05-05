# Konem Matse



[Konem Matse](/npc/4072) is a level 28 Human Monk that spawns in [Qeynos Hills](/zone/4).



## Dialog

**You say:** `hail`



>**Konem Matse says:** Ah, greetings, young Soandso, how are you on this fine day? Perfect day for a nice stroll through the hills, if I do say so myself.



## Arrive at Waypoint Script

if(e.wp == 2 or e.wp == 5) then


eq.set_anim(4072,1);

elseif(e.wp == 3) then


eq.set_anim(4072,0);
end



## Turn-Ins




if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/18921" data-url="18921" class="tooltip-link link">Message to Konem</a>) then 


>**Konem Matse says:** Oh I see.. Phin's always after me about something.  I mean, it's not my fault the order hasn't come in yet.  Hey, since I'm so busy right now, why don't you be a friend and take this back to Phin for me, huh?





Your faction standing with [Silent Fist Clan](/faction/309) got better (<span class='text-success'>+5</span>)


Your faction standing with [Guards of Qeynos](/faction/262) got better (<span class='text-success'>+1</span>)


Your faction standing with [Ashen Order](/faction/361) got better (<span class='text-success'>+1</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/18922" data-url="18922" class="tooltip-link link">Grathins Invoice</a> (+50 exp)

 

**This NPC *should* return incorrect items given.**
