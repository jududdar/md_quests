# Lenka Stoutheart


## Dialog

local fac = e.other:GetFaction(e.self);


**You say:** `hail`



>**Lenka Stoutheart says:** Hi, kid! You seem to be a stranger in these parts. Heed my words, this city is dangerous to new blood!


**Signaled to:**  [Bronto Thudfoot](/npc/10135)

**You say:** `hail`



>**Lenka Stoutheart says:** Run while ye still can!!  The Wolves o' the North will not tolerate yer presence!

**You say:** `toala sent me`



>**Lenka Stoutheart says:** She does not even have the courtesy to come herself. Some old friend!! Listen, some rogue in this city broke into the [Beast] and stole a pouch containing a voucher ticket for a part I need to repair the Beast. I can't get the part back without the ticket. I did not see the rogue. I did not sleep on the Beast that night. Bronto was there. Ask him if he saw the rogue.

**You say:** `beast`



>**Lenka Stoutheart says:** You're joking, right? You have never heard of the Blue Beast?!! She is the fastest ship in Norrath. She made the [Kunark run] in under three weeks. She was designed by [Bronto].

**You say:** `kunark run`



>**Lenka Stoutheart says:** The Kunark run is the most dangerous run between Freeport and [Firiona Vie], in Kunark. If the seas don't rip your hull to splinters and the pirates and sea wyrms don't kill you, you can make a quick run back and forth, avoiding any unwanted inspections.

**You say:** `Firiona Vie`



>**Lenka Stoutheart says:** Firiona Vie is an elven outpost on the continent of Kunark. Every so often I run supplies to and from there. Do not even think about asking me to take you there. It will be months before I can make improvements on the Blue Beast to make it impervious to aerial attacks.

**You say:** `journal strongbox`



>**Lenka Stoutheart says:** You must be from the Academy of Arcane Science.  Well, kid, bad news.  I was docked at the isle in the Ocean of Tears when I was boarded by the Freeport Militia.  To say the least, I panicked and dropped all my cargo.  It is still there.  Mostly illegal alcohol, but the strongbox is still out there, too.  Directly out from the dock.


eq.set_global("strongbox","1",7,"H1");

**You say:** `Bronto`



>**Lenka Stoutheart says:** My trusted friend. Together we travel the world aboard the [Beast]. He is quite skilled at boat making and other mechanical skills. He has a heart and brain far superior to any ogre I have ever met, as well as most other races.
end



## Turn-Ins




if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_728.png" alt="" /> <a
                                href="/item/13818" data-url="13818" class="tooltip-link link">Boat Beacon</a>) then 


>**Lenka Stoutheart says:** Oh!! You must work for that Erudite named Palatos. I guess he won't have to spend anymore money drinking in Freeport. Here. Here is the portrait I kept until he could get me a new boat beacon.





Your faction standing with [Wolves of the North](/faction/320) got better (<span class='text-success'>+5</span>)


Your faction standing with [Shamen of Justice](/faction/327) got better (<span class='text-success'>+1</span>)


Your faction standing with [Heretics](/faction/265) got better (<span class='text-success'>+1</span>)


Your faction standing with [High Guard of Erudin](/faction/267) got better (<span class='text-success'>+1</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_653.png" alt="" /> <a
                                href="/item/12146" data-url="12146" class="tooltip-link link">AkAnons Portrait</a> (+20000 exp)

 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_749.png" alt="" /> <a
                                href="/item/13922" data-url="13922" class="tooltip-link link">Snapped Pole</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_886.png" alt="" /> <a
                                href="/item/13923" data-url="13923" class="tooltip-link link">Moggoks Right Eye</a>) (+200 exp)

**You receive coin:** 0 <img src='/static/icons/item_644.png' width='14' height='14'/> 0 <img src='/static/icons/item_645.png' width='14' height='14'/> 1-10 <img src='/static/icons/item_646.png' width='14' height='14'/> 0 <img src='/static/icons/item_647.png' width='14' height='14'/> 

**This NPC *should* return incorrect items given.**
