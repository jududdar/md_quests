# Tykar Renlin



[Tykar Renlin](/npc/10157) is a level 19 Beggar Rogue that spawns in [East Freeport](/zone/10).



## Dialog

**You say:** `hail`



>**Tykar Renlin says:** Do you have any spare coppers for a thirsty soul?

**You say:** `lucan`



>**Tykar Renlin says:** That man is no just ruler. He has jailed me and my friend Zimel for merely begging.

**You say:** `zimel`



>**Tykar Renlin says:** What?! You know my friend Zimel?! I would like to speak of him, but my mouth is so parched. Maybe a fine grog would loosen my lips. I am uncertain which flavor shall do the trick.
end



## Turn-Ins



local text = "Oooh!! That is the taste. My lips are almost loose. Maybe another will do the trick.";



if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_831.png" alt="" /> <a
                                href="/item/13829" data-url="13829" class="tooltip-link link">Drom's Champagne</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_831.png" alt="" /> <a
                                href="/item/13829" data-url="13829" class="tooltip-link link">Drom's Champagne</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_831.png" alt="" /> <a
                                href="/item/13829" data-url="13829" class="tooltip-link link">Drom's Champagne</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_831.png" alt="" /> <a
                                href="/item/13829" data-url="13829" class="tooltip-link link">Drom's Champagne</a>) then 


>**Tykar Renlin says:** Ahh!! That was good. Now where were we?. Oh yes. My friend Zimel is a fellow beggar. He was locked up in the arena. They were going to let him go when the Freeport Militia came for him. Ha!! He is crazy as a troll now. I took this blanket from his cell before I was released. I no longer need it and my guilt has reached its peak. I do not want crazy old Zimel to freeze. Perhaps you can return it to him.


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_790.png" alt="" /> <a
                                href="/item/12196" data-url="12196" class="tooltip-link link">Bunker Cell \#1</a> (+10 exp)

 

**This NPC *should* return incorrect items given.**



## Signals

if ( e.self:IsEngaged() ) then


return;


local turn, bard;



if ( e.signal == 1 ) then


>**Tykar Renlin says:** Yes. Let us all live together in peace and tranquility. That is the only way.


turn = true;

elseif ( e.signal == 2 ) then


>**Tykar Renlin says:** Ogres smell like..<Sniff..Sniff..> .. like me!!


turn = true;

elseif ( e.signal == 5 ) then


>**Tykar Renlin says:** What a waste of grog and lunch.


turn = true;

elseif ( e.signal == 7 ) then


>**Tykar Renlin says:** That man is no just ruler. He has jailed me and my friend Zimel for merely begging.


turn = true;


if ( turn ) then


bard = eq.get_entity_list():GetMobByNpcTypeID(10141);





if ( not bard.valid ) then



bard = eq.get_entity_list():GetMobByNpcTypeID(10158);





if ( not bard.valid ) then 



bard = eq.get_entity_list():GetMobByNpcTypeID(10165);





if ( bard.valid ) then



e.self:FaceTarget(bard);

end

