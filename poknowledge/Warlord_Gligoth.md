# Warlord Gligoth

[Warlord Gligoth](/npc/202322) is a level 61 Ogre GM Warrior that spawns in [Plane of Knowledge](/zone/202).

Their primary faction is [Inhabitants of Tanaan](/faction/1636).


## Dialog
**You say:** `Hail`

>*Warlord Gligoth glares coldly, his mouth twisted in a gruesome sneer of disgust. 'Kartis is place of shadow, not gud for light crawlers. But yu here, yu want something from shadow? Yes, yu want shadow to teach yu - yu want shadow to feed yu secrets, but yu will only fuel shadow's power in learning from it. If yu still want to stay in Kartis, then yu will only give power to shadow that yu say yu hate. I will teach yu, light crawler, if yu still tink yu can outsmart shadow's soldiers. I'll make that puny stick-thing yu light crawlers call weapons into fierce tools of war and no matter who dey kill, yu will kill in the shadow's name.'*




## Turn-Ins

local count =  **You turn in:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_746.png" alt="" /> <a
                                href="/item/4911" data-url="4911" class="tooltip-link link">Indicolite Helm</a>, 4912, 4913, 4914, 4915, 4916, 4917 x 1
if(count > 0) then
repeat
>**Warlord Gligoth says:** Thank you, Soandso.
 &#127873; **You receive:** eq.ChooseRandom( <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_957.png" alt="" /> <a
                                href="/item/10028" data-url="10028" class="tooltip-link link">Peridot</a>,  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_966.png" alt="" /> <a
                                href="/item/10037" data-url="10037" class="tooltip-link link">Diamond</a>,  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_966.png" alt="" /> <a
                                href="/item/22503" data-url="22503" class="tooltip-link link">Blue Diamond</a>,  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_966.png" alt="" /> <a
                                href="/item/15981" data-url="15981" class="tooltip-link link">Raw Diamond</a>) (+300000 exp)

 
count = count - 1;
until count == 0;

**This NPC *should* return incorrect items given.**






