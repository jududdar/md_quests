# Avatar of Dread



[Avatar of Dread](/npc/48391) is a level 60 Golem Warrior that spawns in [Paineel](/zone/75).

count = 0;



## On NPC Spawn

**Set a timer** named *shout* for 17 seconds


## Timer(s)

if(e.timer == "shout") then


count = count + 1;

if(count) then


**avatar of dread shouts:** <span class="text-danger">Grrrraaaaarrrrrg! The stench of fear permeates the walls of this city! I will forge one item for the faithful of our Lord Cazic-Thule! Make haste!  My time here is short!</span>

if(count == 10) then


**avatar of dread despawns.**
end



## Turn-Ins





if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_805.png" alt="" /> <a
                                href="/item/14105" data-url="14105" class="tooltip-link link">Mundane Shield</a>) then


>**avatar of dread says:** Wear this shield imbued with my very essence. Wear it in honor of your great services to our Lord Cazic-Thule!


Your faction standing with [Heretics](/faction/265) got better (<span class='text-success'>+50</span>)


Your faction standing with [Deepwater Knights](/faction/242) got worse (<span class='text-danger'>-50</span>)


Your faction standing with [Gate Callers](/faction/254) got worse (<span class='text-danger'>-50</span>)


Your faction standing with [Craftkeepers](/faction/231) got worse (<span class='text-danger'>-50</span>)


Your faction standing with [Crimson Hands](/faction/233) got worse (<span class='text-danger'>-50</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_976.png" alt="" /> <a
                                href="/item/14107" data-url="14107" class="tooltip-link link">Dread Forged Shield</a> (+1000 exp)

 


**avatar of dread despawns.**

**This NPC *should* return incorrect items given.**
