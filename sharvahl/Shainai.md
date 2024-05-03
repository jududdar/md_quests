# Shainai


## Dialog

**You say:** `Hail`



>**Shainai says:** Oh hi.  I am on my way home now, but we can maybe talk later, ok?
end



## Arrive at Waypoint Script

if(e.wp==21) then


>**Shainai says:** Yup yup, I definitely know the way from here.

if(e.wp==36) then


>**Shainai says:** Ahhh, home at last.


**Signaled to:**  [\#Delival](/npc/155041)
end



## Signals

if(e.signal==1) then


>**Shainai says:** Daddy I'm sleepy, could you come tuck me in ?


**Signaled to:**  [Delival](/npc/155340)


e.self:SetAppearance(3);
end



## Turn-Ins



if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1243.png" alt="" /> <a
                                href="/item/4478" data-url="4478" class="tooltip-link link">Shainais Blanket</a>) then


>*Shainai settles comfortably in for restful afternoon nap, 'Thank you for walking me home, it was ever so nice of you.  Goodnight.'*


e.other:Ding();


**Signaled to:**  [Delival](/npc/155340)


**Shainai despawns.**

**This NPC *should* return incorrect items given.**





