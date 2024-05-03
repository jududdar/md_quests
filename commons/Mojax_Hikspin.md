# Mojax Hikspin


## Dialog

**You say:** `hail`



>**Mojax Hikspin says:** Hi. How are you? The fish are biting pretty good. That is what Skipynn tells me. I sure wish I had a different [job]. If I did, I could fish all day long.

**You say:** `job`



>**Mojax Hikspin says:** I am a messenger for [Antonius Bayle], ruler of the great city of [Qeynos].

**You say:** `qeynos`



>**Mojax Hikspin says:** Huh?! Have you been living in a cave? The great city of Qeynos is the mightiest nation in Antonica! You'd best journey toward the west and visit the city whose influence stretches beyond the horizons.

**You say:** `hall of truth`



>**Mojax Hikspin says:** I have been expecting you. I am very parched. Could you please get me a bottle of milk? Once you do that will show you where I hid the note.

**You say:** `antonius bayle`



>**Mojax Hikspin says:** How can it be that you do not know of Antonius Bayle? Was it not he who named this great continent of Antonica? Is it not he who rules over the most powerful city on Norrath? Surely you jest!
end



## Turn-Ins



local milk =  **You turn in:**  { <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_856.png" alt="" /> <a
                                href="/item/13087" data-url="13087" class="tooltip-link link">Bottle of Milk</a>}



if(not e.self:IsMoving() and milk > 0) then


repeat



>**Mojax Hikspin says:** Aaahhhh. Now that is refreshing. Just let me rest for a bit. The note is safe and sound in my bedroll inside the inn.



Your faction standing with [Knights of Truth](/faction/281) got better (<span class='text-success'>+1</span>)



Your faction standing with [Dismal Rage](/faction/271) got worse (<span class='text-danger'>-1</span>)



Your faction standing with [The Freeport Militia](/faction/330) got worse (<span class='text-danger'>-1</span>)



Your faction standing with [Steel Warriors](/faction/311) got better (<span class='text-success'>+1</span>)



Your faction standing with [Priests of Marr](/faction/362) got better (<span class='text-success'>+1</span>)



 &#127873; **You receive:** 0 (+1 exp)

 



milk = milk - 1;


until milk == 0;



**Spawn NPC:**  [Duggin Scumber](/npc/21136) at (**y:** -520, **x:** 2720)


if (e.self:GetGrid() == 0) then



eq.start(eq.ChooseRandom(9,10));


**This NPC *should* return incorrect items given.**



## Arrive at Waypoint Script

if((e.self:GetGrid() == 9 and e.wp == 22) or (e.self:GetGrid() == 10 and e.wp == 46)) then


>**Mojax Hikspin says:** Here you are.  I hid it in this box behind the marker.  Take it to Eastyana of the Temple of Marr. Goodbye.


**Spawns on ground:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/18822" data-url="18822" class="tooltip-link link">A Note</a> at (**y:** -520, **x:** 3641)
end
