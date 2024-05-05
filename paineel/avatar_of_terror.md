# Avatar of Terror



[Avatar of Terror](/npc/48393) is a level 60 Golem Warrior that spawns in [Paineel](/zone/75).

count = 0;



## On NPC Spawn

**Set a timer** named *shout* for 17 seconds


## Timer(s)

if(e.timer == "shout") then


count = count + 1;

if(count) then


**avatar of terror shouts:** <span class="text-danger">Grrrraaaaarrrrrg! The stench of fear permeates the walls of this city! I will forge one item for the faithful of our Lord Cazic-Thule! Make haste!  My time here is short!</span>

if(count == 10) then


**avatar of terror despawns.**
end



## Turn-Ins





if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_528.png" alt="" /> <a
                                href="/item/14106" data-url="14106" class="tooltip-link link">Mundane Mask</a>) then 


>**avatar of terror says:** I grant you a mask crafted with my own essence! Wear it in honor of your devotion to our Lord Cazic-Thule!


Your faction standing with [Heretics](/faction/265) got better (<span class='text-success'>+50</span>)


Your faction standing with [Deepwater Knights](/faction/242) got worse (<span class='text-danger'>-50</span>)


Your faction standing with [Gate Callers](/faction/254) got worse (<span class='text-danger'>-50</span>)


Your faction standing with [Craftkeepers](/faction/231) got worse (<span class='text-danger'>-50</span>)


Your faction standing with [Crimson Hands](/faction/233) got worse (<span class='text-danger'>-50</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_528.png" alt="" /> <a
                                href="/item/14108" data-url="14108" class="tooltip-link link">Terror Forged Mask</a> (+5000 exp)

 


**avatar of terror despawns.**

**This NPC *should* return incorrect items given.**
