# Noxhil V-Sek
## Dialog

**You say:** `hail`



>**Noxhil V-Sek says:** Greetings, Soandso!  We of the Dead are proud to have you among us.  Your lineage is well known.  Still, you must learn to claw your way to the upper echelon.  There are many [menial tasks] to be performed before you can truly be inducted as a member.

**You say:** `menial tasks`



>**Noxhil V-Sek says:** You cannot avoid the toil of peons. We have all spent our time in the lower ranks. There are duties such as [collecting beetle eyes].

**You say:** `beetle eye`



if **Faction** >= Amiable then



>**Noxhil V-Sek says:** Take this chest.  It has been fitted with a mold designed to hold ten beetle eyes.  We require them for further experiments.  Do not return until you fill the chest.



 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_608.png" alt="" /> <a
                                href="/item/17930" data-url="17930" class="tooltip-link link">Empty Box</a>


elseif **Faction** >= Indifferent then



>**Noxhil V-Sek says:** When you learn to serve the Dead, then I will find the time to speak of such things.


else



>**Noxhil V-Sek says:** How dare you enter my presence?!  In the name of the Dead I should strike you down!




**You say:** `other components`



if **Faction** >= Amiable then



>**Noxhil V-Sek says:** Take this chest. This one must be filled with [Kerra Isle beetle] eyes. When you finish filling the chest, be sure to return to me with a [wooly mammoth] tusk also. Be quick about it and I just may reward you with something special.



 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_608.png" alt="" /> <a
                                href="/item/17932" data-url="17932" class="tooltip-link link">Empty Chest</a>


elseif **Faction** >= Indifferent then



>**Noxhil V-Sek says:** When you learn to serve the Dead, then I will find the time to speak of such things.


else



>**Noxhil V-Sek says:** How dare you enter my presence?!  In the name of the Dead I should strike you down!




**You say:** `kerra isle beetle`



>**Noxhil V-Sek says:** The shipping route between Qeynos and Erudin includes a stop on an island filled with friendly catpeople. Also on this isle is the Kerra Isle beetle. It is indigenous to Kerra Isle and the catpeople are very protective of them.

**You say:** `mammoth`



>**Noxhil V-Sek says:** I hear that wooly mammoths can be found in the peaks of Everfrost. They are fierce beasts. I would hate to annoy one.
end

## Turn-Ins



local randomloot = math.random(1,3);

local text = "I was expecting a mammoth tusk and the combined beetle eye box!";



if **Faction** >= Amiable and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_608.png" alt="" /> <a
                                href="/item/13389" data-url="13389" class="tooltip-link link">Box of Beetle Eyes</a>) then


>**Noxhil V-Sek says:** Fantastic work, my child! We shall store these for further experiments. Take this as extra payment for a fine job. You have done so well I believe you can assist in obtaining two [other components].


Your faction standing with [The Dead](/faction/239) got better (<span class='text-success'>+10</span>)


Your faction standing with [Queen Cristanos Thex](/faction/303) got better (<span class='text-success'>+1</span>)


Your faction standing with [King Naythox Thex](/faction/278) got worse (<span class='text-danger'>-1</span>)


Your faction standing with [Keepers of the Art](/faction/275) got worse (<span class='text-danger'>-1</span>)


Your faction standing with [Eldritch Collective](/faction/245) got worse (<span class='text-danger'>-1</span>)


Your faction standing with [Primordial Malice](/faction/1522) got worse (<span class='text-danger'>-20</span>)


if(randomloot == 1) then



 &#127873; **You receive:** GiveAll( <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_825.png" alt="" /> <a
                                href="/item/13021" data-url="13021" class="tooltip-link link">Neriak Nectar</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_832.png" alt="" /> <a
                                href="/item/13022" data-url="13022" class="tooltip-link link">Rotgrub Rye</a>) (+17150 exp)

**You receive coin:** 0 <img src='/static/icons/item_644.png' width='14' height='14'/> 0 <img src='/static/icons/item_645.png' width='14' height='14'/> 6 <img src='/static/icons/item_646.png' width='14' height='14'/> 0 <img src='/static/icons/item_647.png' width='14' height='14'/> 


elseif(randomloot == 2) then



 &#127873; **You receive:** GiveAll( <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_825.png" alt="" /> <a
                                href="/item/13021" data-url="13021" class="tooltip-link link">Neriak Nectar</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_825.png" alt="" /> <a
                                href="/item/13021" data-url="13021" class="tooltip-link link">Neriak Nectar</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_832.png" alt="" /> <a
                                href="/item/13022" data-url="13022" class="tooltip-link link">Rotgrub Rye</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_832.png" alt="" /> <a
                                href="/item/13022" data-url="13022" class="tooltip-link link">Rotgrub Rye</a>) (+17150 exp)

**You receive coin:** 0 <img src='/static/icons/item_644.png' width='14' height='14'/> 0 <img src='/static/icons/item_645.png' width='14' height='14'/> 6 <img src='/static/icons/item_646.png' width='14' height='14'/> 0 <img src='/static/icons/item_647.png' width='14' height='14'/> 


elseif(randomloot == 3) then



 &#127873; **You receive:** 0 (+17150 exp)

**You receive coin:** 0 <img src='/static/icons/item_644.png' width='14' height='14'/> 0 <img src='/static/icons/item_645.png' width='14' height='14'/> 6 <img src='/static/icons/item_646.png' width='14' height='14'/> 0 <img src='/static/icons/item_647.png' width='14' height='14'/> 


elseif **Faction** >= Amiable and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_608.png" alt="" /> <a
                                href="/item/13395" data-url="13395" class="tooltip-link link">Beetle Eye Chest</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_807.png" alt="" /> <a
                                href="/item/10124" data-url="10124" class="tooltip-link link">Mammoth Tusks</a>) then 


>**Noxhil V-Sek says:** Excellent work, young one! You are sure to be an asset to our faction. Let us see if we can help you on your journey to power. I believe this can be of assistance to a young necromancer of the Dead.


Your faction standing with [The Dead](/faction/239) got better (<span class='text-success'>+20</span>)


Your faction standing with [Queen Cristanos Thex](/faction/303) got better (<span class='text-success'>+3</span>)


Your faction standing with [King Naythox Thex](/faction/278) got worse (<span class='text-danger'>-3</span>)


Your faction standing with [Keepers of the Art](/faction/275) got worse (<span class='text-danger'>-3</span>)


Your faction standing with [Eldritch Collective](/faction/245) got worse (<span class='text-danger'>-3</span>)


Your faction standing with [Primordial Malice](/faction/1522) got worse (<span class='text-danger'>-40</span>)


 &#127873; **You receive:** eq.ChooseRandom( <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/15035" data-url="15035" class="tooltip-link link">Spell: Bind Affinity</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/15362" data-url="15362" class="tooltip-link link">Spell: Convoke Shadow</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/15445" data-url="15445" class="tooltip-link link">Spell: Lifedraw</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/15355" data-url="15355" class="tooltip-link link">Spell: Engulfing Darkness</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/15360" data-url="15360" class="tooltip-link link">Spell: Heat Blood</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/15363" data-url="15363" class="tooltip-link link">Spell: Wave of Enfeeblement</a>) (+17150 exp)

 

**This NPC *should* return incorrect items given.**






