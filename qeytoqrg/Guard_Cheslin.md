# Guard Cheslin



[Guard Cheslin](/npc/4081) is a level 2 Human Warrior that spawns in [Qeynos Hills](/zone/4).



## Dialog

**You say:** `hail`



>**Guard Cheslin says:** Hail, mighty adventurer! I am Guard Cheslin Sydwend and I am here to serve and protect. Feel safe when we Qeynos guards are on watch. We are the best!

**You say:** `father sent me`



>**Guard Cheslin says:** My father has no need to worry and I do not need a baby sitter. I may be in training still, but a Qeynos guard in training is still a formidable opponent. EVIL, BEWARE!!   HAIL ANTONIUS BAYLE! 

**You say:** `donation.* temple.* thunder`





>**Guard Cheslin says:** Of course I shall donate to that esteemed order. Here you are, my good friend. Now run along before you are injured by some nasty creature. By the way, you should speak with my fellow guard, Leopold. He also would donate.


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_644.png" alt="" /> <a
                                href="/item/13295" data-url="13295" class="tooltip-link link">A Donation</a>

**You say:** `drop`



>**Guard Cheslin says:** Yes!! I seem to have dropped some of my [Illusion] cards.

**You say:** `illusion`



>**Guard Cheslin says:** Oh!! Do you play Illusion, too? I love that game. I have some very rare cards in my deck. I seem to have dropped four of them somewhere during my last patrol. Darn it! They probably blew away the minute I dropped them! I will never find those cards again.
end



## Turn-Ins




if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_650.png" alt="" /> <a
                                href="/item/13904" data-url="13904" class="tooltip-link link">Ebon Lotus</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_653.png" alt="" /> <a
                                href="/item/13905" data-url="13905" class="tooltip-link link">Library of Erudin</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_649.png" alt="" /> <a
                                href="/item/13906" data-url="13906" class="tooltip-link link">Chrono Cyclone</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_652.png" alt="" /> <a
                                href="/item/13907" data-url="13907" class="tooltip-link link">Diamond Vale</a>) then


>**Guard Cheslin says:** Oh great! I have all my cards back. Here is a little something for assisting a Qeynos guard. And any time you are in trouble, just call on Cheslin, master swordsman. Take it to my father, Master Chesgard of the Knights of Thunder in Qeynos. No doubt he sent you to follow me on my watch.


Your faction standing with [Guards of Qeynos](/faction/262) got better (<span class='text-success'>+20</span>)


Your faction standing with [Antonius Bayle](/faction/219) got better (<span class='text-success'>+3</span>)


Your faction standing with [Corrupt Qeynos Guards](/faction/230) got worse (<span class='text-danger'>-3</span>)


Your faction standing with [Circle of Unseen Hands](/faction/223) got worse (<span class='text-danger'>-5</span>)


Your faction standing with [Merchants of Qeynos](/faction/291) got better (<span class='text-success'>+2</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_866.png" alt="" /> <a
                                href="/item/18839" data-url="18839" class="tooltip-link link">A Sealed Letter</a> (+1500 exp)

**You receive coin:** 0 <img src='/static/icons/item_644.png' width='14' height='14'/> 1-2 <img src='/static/icons/item_645.png' width='14' height='14'/> 1-9 <img src='/static/icons/item_646.png' width='14' height='14'/> 1-9 <img src='/static/icons/item_647.png' width='14' height='14'/> 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_650.png" alt="" /> <a
                                href="/item/13904" data-url="13904" class="tooltip-link link">Ebon Lotus</a> or  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_653.png" alt="" /> <a
                                href="/item/13905" data-url="13905" class="tooltip-link link">Library of Erudin</a> or  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_649.png" alt="" /> <a
                                href="/item/13906" data-url="13906" class="tooltip-link link">Chrono Cyclone</a> or  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_652.png" alt="" /> <a
                                href="/item/13907" data-url="13907" class="tooltip-link link">Diamond Vale</a>) then


>**Guard Cheslin says:** Wow!! I thought I lost this for good. All together I lost the [illusion] cards: Ebon Lotus, Library of Erudin, Chrono Cyclone and Diamond Vale. Man!! Those are rare cards!


**This NPC *should* return incorrect items given.**



## Arrive at Waypoint Script

local xloc = e.self:GetX();

local yloc = e.self:GetY();

local zloc = e.self:GetZ();

if(e.wp == 1) then


>**Guard Cheslin says:** Hail, fellow guards! I am off to protect the travelers of the hills from evil. I shall return!


**Signaled to:**  [Hefax Tinmar](/npc/4142)


**Signaled to:**  [Mogan Delfin](/npc/4001)

elseif(e.wp == 3) then


>**Guard Cheslin says:** Fear not, simple travelers. Cheslin the masterful is here to protect you.


eq.create_ground_object( <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_653.png" alt="" /> <a
                                href="/item/13905" data-url="13905" class="tooltip-link link">Library of Erudin</a>,xloc,yloc,zloc,0,300000); 


>**Guard Cheslin says:** Hey! Did I just drop something?

elseif(e.wp == 4) then


>**Guard Cheslin says:** Fear not, simple travelers. Cheslin the masterful is here to protect you.


eq.create_ground_object( <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_650.png" alt="" /> <a
                                href="/item/13904" data-url="13904" class="tooltip-link link">Ebon Lotus</a>,xloc,yloc,zloc,0,300000); 


>**Guard Cheslin says:** Hey! Did I just drop something?

elseif(e.wp == 7) then


>**Guard Cheslin says:** Fear not, simple travelers. Cheslin the masterful is here to protect you.


eq.create_ground_object( <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_652.png" alt="" /> <a
                                href="/item/13907" data-url="13907" class="tooltip-link link">Diamond Vale</a>,xloc,yloc,zloc,0,300000); 


>**Guard Cheslin says:** Hey! Did I just drop something?

elseif(e.wp == 9) then


>**Guard Cheslin says:** Fear not, simple travelers. Cheslin the masterful is here to protect you.


eq.create_ground_object( <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_649.png" alt="" /> <a
                                href="/item/13906" data-url="13906" class="tooltip-link link">Chrono Cyclone</a>,xloc,yloc,zloc,0,300000); 


>**Guard Cheslin says:** Hey! Did I just drop something?

elseif(e.wp == 11) then


>**Guard Cheslin says:** I lost some of my [illusion] playing cards. And they were the rare ones too! Darn it! If anyone finds them, please return them to me.
end
