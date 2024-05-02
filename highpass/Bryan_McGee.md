# Bryan McGee
## Dialog

**You say:** `hail`



>**Bryan McGee says:** I do not know what you are doing up here, but I am a busy man. Please return to the bar downstairs and enjoy the atmosphere.


**Signaled to:**  [Beef](/npc/5055)

**You say:** `oblong bottle`



>**Bryan McGee says:** The oblong bottle is a legend. They say one drink and you're off to oblivion, but just before that you feel the best you've ever felt and relive all your finest memories in the blink of an eye. The last I heard, some guy by the name of Turgin Swillfod turned up in Freeport spouting that he had found it. He was never heard from again.

**You say:** `never stop chopping`



>**Bryan McGee says:** Hey!! You must be the one I traded my axe to. Funny.. I thought you were much shorter. If you have my axe I will return your gem to you. Well..? Let's have it!


end

## Signals

if(e.signal == 1) then


>**Bryan McGee says:** The boss might need some help!


local stanos = eq.get_entity_list():GetMobByNpcTypeID(5088); 


if ( stanos.valid ) then



e.self:MoveTo(stanos:GetX(), stanos:GetY(), stanos:GetZ(), -1, false);

end

## Turn-Ins




if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_569.png" alt="" /> <a
                                href="/item/12366" data-url="12366" class="tooltip-link link">never stop chopping</a>) then 


>**Bryan McGee says:** On second thought.. You can do a little favor for me first. An associate of mine has asked me to acquire a case of spirits for him. Take this box and seek out what is needed to fill it. Inside you will combine the spirits of Lendel's Grand Lager, Gator Gulp Ale, Blackburrow Swig, Tunare's Finest, Underfoot Triple Bock, Frozen Toe Rum, Blood Spirit, Vasty Deep Ale, Clockwork Oil Stout and the legendary..[Oblong Bottle].





Your faction standing with [Coalition of Tradefolk Underground](/faction/336) got better (<span class='text-success'>+10</span>)


Your faction standing with [Coalition of Tradefolk](/faction/229) got better (<span class='text-success'>+10</span>)


Your faction standing with [Carson McCabe](/faction/329) got better (<span class='text-success'>+1</span>)


Your faction standing with [Corrupt Qeynos Guards](/faction/230) got better (<span class='text-success'>+1</span>)


Your faction standing with [The Freeport Militia](/faction/330) got better (<span class='text-success'>+1</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_608.png" alt="" /> <a
                                href="/item/17984" data-url="17984" class="tooltip-link link">Bottle Crate</a> (+15000 exp)

 


**Signaled to:**  [Beef](/npc/5055)

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_608.png" alt="" /> <a
                                href="/item/12365" data-url="12365" class="tooltip-link link">Case of Spirits</a>) then


>**Bryan McGee says:** I cannot believe you actually acquired all those drinks!! You do good work, kid. Here is the gem as I promised. And a few plat for good measure. Don't let it be said that the Axe doesn't treat his friends right.


Your faction standing with [Coalition of Tradefolk Underground](/faction/336) got better (<span class='text-success'>+25</span>)


Your faction standing with [Coalition of Tradefolk](/faction/229) got better (<span class='text-success'>+25</span>)


Your faction standing with [Carson McCabe](/faction/329) got better (<span class='text-success'>+2</span>)


Your faction standing with [Corrupt Qeynos Guards](/faction/230) got better (<span class='text-success'>+1</span>)


Your faction standing with [The Freeport Militia](/faction/330) got better (<span class='text-success'>+3</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_968.png" alt="" /> <a
                                href="/item/12348" data-url="12348" class="tooltip-link link">Gem of Stamina</a> (+15000 exp)

**You receive coin:** 1-10 <img src='/static/icons/item_644.png' width='14' height='14'/> 0 <img src='/static/icons/item_645.png' width='14' height='14'/> 0 <img src='/static/icons/item_646.png' width='14' height='14'/> 0 <img src='/static/icons/item_647.png' width='14' height='14'/> 

**This NPC *should* return incorrect items given.**
