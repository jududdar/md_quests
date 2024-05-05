# Cain Darkmoore



[Cain Darkmoore](/npc/9092) is a level 61 Human GM Warrior that spawns in [West Freeport](/zone/9).



## Dialog

**You say:** `hail`



>**Cain Darkmoore says:** Hail, Soandso! We are the Steel Warriors of Freeport. Our training disciplines have created some of the finest warriors ever to walk upon Norrath. Perhaps the bards shall sing songs of you one day. Let your first mission be the extermination of [Clan Deathfist].

**You say:** `clan deathfist`



>**Cain Darkmoore says:** The orcs of the Commonlands call themselves Clan Deathfist. They have committed many vile acts upon the residents of the Commonlands as well as persons traveling to and from Freeport. They must be destroyed. Go forth to slay them. I shall pay a bounty for every two Deathfist belts. If you are a true warrior of the bunker. perhaps you can begin with [the green and blue].

**You say:** `bigger problem`



>**Cain Darkmoore says:** The bigger problem is the Freeport Militia. Go to the Hall of Truth and speak with the Knights of Truth about that. They have already started their campaign to rid the city of the militia. The so-called Freeport Militia is not to be trusted.

**You say:** `green and blue`



>**Cain Darkmoore says:** The green and blue was a test for all skilled warriors. But we have no more bunker battle blades to spare, and I can not offer you the green and the blue. We must prepare for war!!

**You say:** `bunker battle blade`



>**Cain Darkmoore says:**  The bunker battle blade was crafted and enchanted for use by warriors only. It has the power to strike down those creatures which hide behind their magic. Once bestowed upon a warrior, it cannot leave your side or it shall vanish from this realm forever. One must perform the [green and blue] to earn such a blade.

**You say:** `opal`



>**Cain Darkmoore says:** Opal. Beautiful Opal Darkbriar. Never have I gazed upon a more beautiful creature. She works as a librarian at the Academy of Arcane Science. Some day she shall be mine. A warrior as bold as myself deserves the very best and she is truly that.
end



## Turn-Ins




local count =  **You turn in:**  { <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_564.png" alt="" /> <a
                                href="/item/13916" data-url="13916" class="tooltip-link link">Deathfist Slashed Belt</a>}, 2

if(count > 0) then


repeat



>**Cain Darkmoore says:** Very fine work Soandso. With your help, we shall soon rid the commonlands of the orcs. Then we can move on to a [bigger problem].



Your faction standing with [Steel Warriors](/faction/311) got better (<span class='text-success'>+5</span>)



Your faction standing with [Guards of Qeynos](/faction/262) got better (<span class='text-success'>+1</span>)



Your faction standing with [Corrupt Qeynos Guards](/faction/230) got worse (<span class='text-danger'>-1</span>)



Your faction standing with [The Freeport Militia](/faction/330) got worse (<span class='text-danger'>-1</span>)



Your faction standing with [Knights of Truth](/faction/281) got better (<span class='text-success'>+1</span>)



 &#127873; **You receive:** 0 (+17750 exp)

**You receive coin:** 0 <img src='/static/icons/item_644.png' width='14' height='14'/> 8 <img src='/static/icons/item_645.png' width='14' height='14'/> 0 <img src='/static/icons/item_646.png' width='14' height='14'/> 0 <img src='/static/icons/item_647.png' width='14' height='14'/> 



count = count - 1;


until count == 0;

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/18748" data-url="18748" class="tooltip-link link">A tattered note</a>) then 


>**Cain Darkmoore says:** Welcome to the Steel Warriors, young warrior. It is time to prove your mettle. Look to the outskirts of Freeport and join the fray. Show Clan Deathfist what a warrior of the bunker can do.


Your faction standing with [Steel Warriors](/faction/311) got better (<span class='text-success'>+100</span>)


Your faction standing with [Guards of Qeynos](/faction/262) got better (<span class='text-success'>+20</span>)


Your faction standing with [Corrupt Qeynos Guards](/faction/230) got worse (<span class='text-danger'>-15</span>)


Your faction standing with [The Freeport Militia](/faction/330) got worse (<span class='text-danger'>-15</span>)


Your faction standing with [Knights of Truth](/faction/281) got better (<span class='text-success'>+20</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_678.png" alt="" /> <a
                                href="/item/13572" data-url="13572" class="tooltip-link link">Dirty Training Tunic*</a> (+20 exp)

 

**This NPC *should* return incorrect items given.**
;

