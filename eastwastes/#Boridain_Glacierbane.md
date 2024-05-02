# Boridain Glacierbane


## Turn-Ins





if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_554.png" alt="" /> <a
                                href="/item/30266" data-url="30266" class="tooltip-link link">Rabid Kodiak Skin</a>) then


>**Boridain Glacierbane says:** Yes! I've done it! The vile beast is finally dead. I will at last be revered as the mighty hunter I am. Here is your axe back, I broke it on the killing blow. Take it as proof that you are a friend of the greatest hunter in the history of the Coldain!


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_568.png" alt="" /> <a
                                href="/item/30267" data-url="30267" class="tooltip-link link">Broken Axe</a> (+5000 exp)

 

**This NPC *should* return incorrect items given.**

## Arrive at Waypoint Script

if(e.wp == 1) then


>**Boridain Glacierbane says:** Hmmm, fresh prints. They're HUGE! This must be it! This hunting stuff is easier than I thought.

elseif(e.wp == 2) then


>**Boridain Glacierbane says:** Hmm, that wasn't him.  Let's see now, if I were a rabid tundra beast where would I go? This way!

elseif(e.wp == 3) then


e.self:SetAppearance(1);

elseif(e.wp == 4) then


>**Boridain Glacierbane says:** Ahh, that's better. Back to the hunt... I think I hear something over yonder. Stay low.

elseif(e.wp == 5) then


>**Boridain Glacierbane says:** Where did that vile beast go now? Wait, what's that over there? Could it be? Only one way to find out!

elseif(e.wp == 6) then


e.self:SetAppearance(1);


>**Boridain Glacierbane says:** All this tracking is makin me mighty sleepy. Time for a little nap. You keep a lookout.

elseif(e.wp == 7) then


>**Boridain Glacierbane says:** Ahh, refreshing! Back to work... I think I smell the beast! This way.

elseif(e.wp == 8) then


>**Boridain Glacierbane says:** I just don't get it. I thought that was him for sure. I don't see any sign of him now.

elseif(e.wp == 9) then


>**Boridain Glacierbane says:** Who am I kidding, I'm no hunter. I'll never be a hunter. I may as well give up and become a miner like dad.


e.self:SetAppearance(1);


**Spawn NPC:**  [Rabid Tundra Kodiak](/npc/116017) at (**y:** -2532, **x:** 1510)
end