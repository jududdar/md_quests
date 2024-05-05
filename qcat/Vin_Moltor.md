# Vin Moltor



[Vin Moltor](/npc/45111) is a level 24 Beggar Warrior that spawns in [Qeynos Aqueduct System](/zone/45).



## Dialog

**You say:** `hail`



>**Vin Moltor says:** Heh?? .. BURRP!.. Leave me be will ya.

**You say:** `paw`



>**Vin Moltor says:** Paw ya say? Yeah.. Yeah .. I got this ratty old thing still. You want it? Its yours for a Bottle of Kalish and hm.. .. How bad you want it?  Hm..  Two..  No no..  Three Gold..  Er..  NO! Wait. Pie..  Yes! Rat Ear Pie is what I want.. Three Bottles of Kalish and a Rat Eat Pie. If you want the Paw that is my price.

**You say:** `ring`



>**Vin Moltor says:** Rings?  I don't know anything about no rings...  My [father] prob'ly sold them or lost them.  They could be anywhere.

**You say:** `father`



>**Vin Moltor says:** My father was a drunk and a loser just like me.  He traveled all of Antonica, though.  He even went to Odus once or twice, I think.  He died a long time ago.
end



## Turn-Ins



local text = "What are you trying to do, cheat me?!  I need three bottles of Kalish and a rat ear pie before I'll give up the paw."



if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_831.png" alt="" /> <a
                                href="/item/13016" data-url="13016" class="tooltip-link link">Bottle of Kalish</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_831.png" alt="" /> <a
                                href="/item/13016" data-url="13016" class="tooltip-link link">Bottle of Kalish</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_831.png" alt="" /> <a
                                href="/item/13016" data-url="13016" class="tooltip-link link">Bottle of Kalish</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_783.png" alt="" /> <a
                                href="/item/13192" data-url="13192" class="tooltip-link link">Rat Ear Pie</a>) then


>**Vin Moltor says:** Ah. Come to ol'Vin my dear sweet Kalish.. Mmmm.. And Rat Ear Pie.. I am going to eat and drink like a KING! Huh? Oh.. The Paw.. Here you go.. Hope it brings you more luck then it did me..


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_743.png" alt="" /> <a
                                href="/item/17014" data-url="17014" class="tooltip-link link">Severed Paw</a> 

 

**This NPC *should* return incorrect items given.**



## Arrive at Waypoint Script

if((e.wp > 15 and e.wp < 34) or (e.wp > 50 and e.wp < 70)) then


e.self:SetRunning(true);

else


e.self:SetRunning(false);
end
