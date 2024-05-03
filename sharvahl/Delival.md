# Delival


## On NPC Spawn

**Set a timer** named *depop* for 300 seconds


## Signals

if(e.signal==1) then


>*Delival sighs and says, 'My hands are full right now hon.'  Delival looks your way curiously and asks, 'I don't suppose you would want to [tuck] her in for me if I give you a blanket?'*

elseif(e.signal==2) then


>**Delival says:** Yes, yes, goodnight now sweetheart.


**Delival despawns.**
end



## Dialog

**You say:** `tuck`



>**Delival says:** Thank you again, have been a great help.  Here is her favorite blanket, just give it to her and she should be fine.  G'night Shainai.


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1243.png" alt="" /> <a
                                href="/item/4478" data-url="4478" class="tooltip-link link">Shainais Blanket</a> 

 
end



## Turn-Ins



if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_691.png" alt="" /> <a
                                href="/item/4460" data-url="4460" class="tooltip-link link">Shainais Bag</a>) then


>**Delival says:** Well I wish there was more I could do to repay you. Take this old compass and what change I can spare with my most sincere thanks. Now off to bed Shainai, you have had a busy day.


Your faction standing with [Guardians of Shar Vahl](/faction/1513) got better (<span class='text-success'>+4</span>)


**Set a timer** named *goodnight* for 10 seconds


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_750.png" alt="" /> <a
                                href="/item/12000" data-url="12000" class="tooltip-link link">Compass</a> (+100 exp)

**You receive coin:** 0 <img src='/static/icons/item_644.png' width='14' height='14'/> 0 <img src='/static/icons/item_645.png' width='14' height='14'/> 9 <img src='/static/icons/item_646.png' width='14' height='14'/> 2 <img src='/static/icons/item_647.png' width='14' height='14'/> 

**This NPC *should* return incorrect items given.**



## Timer(s)

if(e.timer == "depop") then


**Stop timer** named *depop*


**Delival despawns.**

elseif(e.timer == "goodnight") then


**Signaled to:**  [Shainai](/npc/155339)
end
