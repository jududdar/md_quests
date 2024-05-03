# Kazlo Naedra


## Dialog

local fac = e.other:GetFaction(e.self);

**You say:** `hail`



>**Kazlo Naedra says:** Hail, Soandso.  I'm Kazlo Naedra of the Order of Three.  We always seem to be running out of [supplies] around here, which is, of course, very distracting to our studies.

**You say:** `blank scroll sheets`



>**Kazlo Naedra says:** These blank sheets seem harder to find every month. All the local merchants are out of them. Hopefully, one of the merchants out in Surefall will have some.

**You say:** `supplies`



if(fac < 5) then



>**Kazlo Naedra says:** Yes, we're almost out of [blank scroll sheets]. Gahlith will be very upset, unless I can replenish our inventory soon.


else



>**Kazlo Naedra says:** The Order of Three has been monitoring your recent activities, and we are appalled by you and your actions! Now, begone!

end



## Turn-Ins







if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/18006" data-url="18006" class="tooltip-link link">Blank Scroll Sheets</a>) then


>**Kazlo Naedra says:** Good work, Soandso! Here's a little something for your troubles. Your quick work and loyalty will be noted by the Order of Three.


Your faction standing with [Order of Three](/faction/342) got better (<span class='text-success'>+5</span>)


Your faction standing with [Guards of Qeynos](/faction/262) got better (<span class='text-success'>+1</span>)


Your faction standing with [Bloodsabers](/faction/221) got worse (<span class='text-danger'>-1</span>)


Your faction standing with [Opal Darkbriar](/faction/296) got worse (<span class='text-danger'>-1</span>)


 &#127873; **You receive:** 0 (+200 exp)

**You receive coin:** 0 <img src='/static/icons/item_644.png' width='14' height='14'/> 0 <img src='/static/icons/item_645.png' width='14' height='14'/> 0 <img src='/static/icons/item_646.png' width='14' height='14'/> 1-10 <img src='/static/icons/item_647.png' width='14' height='14'/> 

**This NPC *should* return incorrect items given.**



## Arrive at Waypoint Script

if(e.wp == 10) then


>**Kazlo Naedra says:** Hey guys, you got any blank scroll sheets for sale? Or know where I could get some around here?


**Signaled to:**  [Barthal](/npc/1115)
end
