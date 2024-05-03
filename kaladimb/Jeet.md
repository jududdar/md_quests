# Jeet


## Dialog

**You say:** `hail`



if **Faction** >= Dubious +200 then



>**Jeet says:** What business do you have here?!! This here is the mine and that means if you ain't a [member of Miner's Guild 628], you'd best be moving on!!


else



>**Jeet says:** The word around the mines is that you are not to be trusted. You'd best leave before my dagger finds a new home in your back.


**You say:** `cleaner`



if **Faction** >= Amiable +100 then 



>**Jeet says:** Darn that blasted clockwork cleaner!! No one in Kaladim even knows what it is! They all think it's some kinda rat in armor!! Rat paladins?!! The name fits. We miners have seen many like it in the gnome city during heists, err.. visits. We have to get rid of this one in Kaladim!! If you smash it and get its scrap metal, I am authorized to give you a mining cap, if you are a member of Miner's Guild 628.


elseif **Faction** >= Indifferent then



>**Jeet says:** Don't take this personally, but I can't quite trust you with such matters. Maybe a few less Butcherblock bandits would prove your worth.


else



>**Jeet says:** The word around the mines is that you are not to be trusted. You'd best leave before my dagger finds a new home in your back.


**You say:** `628`



if **Faction** >= Amiable then 




>**Jeet says:** Well, then, get off yer rump and give us a hand! If you don't have a mining pick, then get down there and use your fingernails!! If you're new and you want to earn a pick, you can [volunteer to exterminate the rats] that have been infesting the mines!!


elseif **Faction** >= Indifferent then



>**Jeet says:** Don't take this personally, but I can't quite trust you with such matters. Maybe a few less Butcherblock bandits would prove your worth.


else



>**Jeet says:** The word around the mines is that you are not to be trusted. You'd best leave before my dagger finds a new home in your back.


**You say:** `volunteer`



if **Faction** >= Amiable then 




>**Jeet says:** Well, someone has to do the dirty work around here. Let it be you new miners. Go patrol the mines and if you see any rats, bash them good!! Return to me with four rat pelts and I will give you some armor as payment. If you want a 628 mining cap, yer gonna have to smash that infernal [cleaner]!!


elseif **Faction** >= Indifferent then



>**Jeet says:** Don't take this personally, but I can't quite trust you with such matters. Maybe a few less Butcherblock bandits would prove your worth.


else



>**Jeet says:** The word around the mines is that you are not to be trusted. You'd best leave before my dagger finds a new home in your back.


**You say:** `run`



if **Faction** >= Amiable then 




>**Jeet says:** Well, as you most likely know, we are a non-profit organization, at least here in Kaladim. We need to make our profit elsewhere and that means a little bit of thieving. Presently we need loyal members to [collect the gnome profit].


elseif **Faction** >= Indifferent then



>**Jeet says:** Don't take this personally, but I can't quite trust you with such matters. Maybe a few less Butcherblock bandits would prove your worth.


else



>**Jeet says:** The word around the mines is that you are not to be trusted. You'd best leave before my dagger finds a new home in your back.


**You say:** `collect`



if **Faction** >= Amiable then 




>**Jeet says:** Take this key. Don't lose it!! You will need to use it on a metal rat called a scrubber. They are all over Ak'Anon. You must find the one that responds to the number, '628'. If it responds, use the key on it. It will hand over a bag with the 'gnome take'. Return it to me. Get moving!!



 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1079.png" alt="" /> <a
                                href="/item/12164" data-url="12164" class="tooltip-link link">Scrubber Key</a>


elseif **Faction** >= Indifferent then



>**Jeet says:** Don't take this personally, but I can't quite trust you with such matters. Maybe a few less Butcherblock bandits would prove your worth.


else



>**Jeet says:** The word around the mines is that you are not to be trusted. You'd best leave before my dagger finds a new home in your back.

end



## Turn-Ins



local text = "What are you?! Some kinda' slacker?! I told you to return with FOUR rat pelts!";



if **Faction** >= Amiable and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_554.png" alt="" /> <a
                                href="/item/13054" data-url="13054" class="tooltip-link link">Giant Rat Pelt</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_554.png" alt="" /> <a
                                href="/item/13054" data-url="13054" class="tooltip-link link">Giant Rat Pelt</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_554.png" alt="" /> <a
                                href="/item/13054" data-url="13054" class="tooltip-link link">Giant Rat Pelt</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_554.png" alt="" /> <a
                                href="/item/13054" data-url="13054" class="tooltip-link link">Giant Rat Pelt</a>) then 


>**Jeet says:** It's about time you managed to smash these four!! Here. You do good work. We could use someone like you to [run to the gnome city].


Your faction standing with [Miners Guild 628](/faction/322) got better (<span class='text-success'>+20</span>)


Your faction standing with [Circle of Unseen Hands](/faction/223) got worse (<span class='text-danger'>-1</span>)


Your faction standing with [Butcherblock Bandits](/faction/379) got worse (<span class='text-danger'>-1</span>)


Your faction standing with [Deeppockets](/faction/241) got better (<span class='text-success'>+1</span>)


Your faction standing with [Ebon Mask](/faction/244) got worse (<span class='text-danger'>-3</span>)


 &#127873; **You receive:** eq.ChooseRandom( <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_640.png" alt="" /> <a
                                href="/item/2113" data-url="2113" class="tooltip-link link">Small Tattered Skullcap</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_771.png" alt="" /> <a
                                href="/item/2114" data-url="2114" class="tooltip-link link">Small Tattered Mask</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_643.png" alt="" /> <a
                                href="/item/2115" data-url="2115" class="tooltip-link link">Small Tattered Gorget</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_632.png" alt="" /> <a
                                href="/item/2116" data-url="2116" class="tooltip-link link">Small Patchwork Tunic</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_668.png" alt="" /> <a
                                href="/item/2117" data-url="2117" class="tooltip-link link">Small Tattered Shoulderpads</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_660.png" alt="" /> <a
                                href="/item/2118" data-url="2118" class="tooltip-link link">Small Patchwork Cloak</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_564.png" alt="" /> <a
                                href="/item/2119" data-url="2119" class="tooltip-link link">Small Tattered Belt</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_634.png" alt="" /> <a
                                href="/item/2120" data-url="2120" class="tooltip-link link">Small Patchwork Sleeves</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_637.png" alt="" /> <a
                                href="/item/2121" data-url="2121" class="tooltip-link link">Small Tattered Wristbands</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_636.png" alt="" /> <a
                                href="/item/2122" data-url="2122" class="tooltip-link link">Small Tattered Gloves</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_635.png" alt="" /> <a
                                href="/item/2123" data-url="2123" class="tooltip-link link">Small Patchwork Pants</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_633.png" alt="" /> <a
                                href="/item/2124" data-url="2124" class="tooltip-link link">Small Patchwork Boots</a>) (+4000 exp)

 

elseif **Faction** >= Amiable and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1031.png" alt="" /> <a
                                href="/item/13282" data-url="13282" class="tooltip-link link">Scrap Metal</a>) then 


>**Jeet says:** Great work!! We need this junk for something and we sure didn't need this rat sucking up any of our gems. Here. This is a Mining Cap 628. It's not much, but it is the mark of our miners and provides light for mining purposes. Hold onto it. You never know when we may call upon you to produce it.


Your faction standing with [Miners Guild 628](/faction/322) got better (<span class='text-success'>+15</span>)


Your faction standing with [Circle of Unseen Hands](/faction/223) got worse (<span class='text-danger'>-1</span>)


Your faction standing with [Butcherblock Bandits](/faction/379) got worse (<span class='text-danger'>-1</span>)


Your faction standing with [Deeppockets](/faction/241) got better (<span class='text-success'>+1</span>)


Your faction standing with [Ebon Mask](/faction/244) got worse (<span class='text-danger'>-2</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_625.png" alt="" /> <a
                                href="/item/12165" data-url="12165" class="tooltip-link link">Miners Cap 628</a> (+5000 exp)

 

elseif **Faction** >= Amiable and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_690.png" alt="" /> <a
                                href="/item/12167" data-url="12167" class="tooltip-link link">Gnome Take</a>) then 


>**Jeet says:** What is all this junk!! That blasted tin rat is supposed to be heisting expensive goods from rich gnomes - not all this garbage!! Here. This is your cut of this junk.





Your faction standing with [Miners Guild 628](/faction/322) got better (<span class='text-success'>+5</span>)


Your faction standing with [Circle of Unseen Hands](/faction/223) got worse (<span class='text-danger'>-1</span>)


Your faction standing with [Butcherblock Bandits](/faction/379) got worse (<span class='text-danger'>-1</span>)


Your faction standing with [Deeppockets](/faction/241) got better (<span class='text-success'>+1</span>)


Your faction standing with [Ebon Mask](/faction/244) got worse (<span class='text-danger'>-1</span>)


 &#127873; **You receive:** eq.ChooseRandom( <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_848.png" alt="" /> <a
                                href="/item/10009" data-url="10009" class="tooltip-link link">Bead Necklace</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_944.png" alt="" /> <a
                                href="/item/10015" data-url="10015" class="tooltip-link link">Malachite</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1135.png" alt="" /> <a
                                href="/item/10500" data-url="10500" class="tooltip-link link">Small Piece of Ore</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_507.png" alt="" /> <a
                                href="/item/13220" data-url="13220" class="tooltip-link link">Iony's Absorber</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1135.png" alt="" /> <a
                                href="/item/10500" data-url="10500" class="tooltip-link link">Small Piece of Ore</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_945.png" alt="" /> <a
                                href="/item/10016" data-url="10016" class="tooltip-link link">Lapis Lazuli</a>) (+5000 exp)

**You receive coin:** 0 <img src='/static/icons/item_644.png' width='14' height='14'/> 0 <img src='/static/icons/item_645.png' width='14' height='14'/> 1-5 <img src='/static/icons/item_646.png' width='14' height='14'/> 0 <img src='/static/icons/item_647.png' width='14' height='14'/> 

elseif **Faction** >= Amiable and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_690.png" alt="" /> <a
                                href="/item/12162" data-url="12162" class="tooltip-link link">Gnome Take</a>) then 


>**Jeet says:** Good work miner. This is a fantastic haul!! Those wrinkly little gnomes don't know what is going on. Here is your cut. Now get back to work.





Your faction standing with [Miners Guild 628](/faction/322) got better (<span class='text-success'>+25</span>)


Your faction standing with [Circle of Unseen Hands](/faction/223) got worse (<span class='text-danger'>-1</span>)


Your faction standing with [Butcherblock Bandits](/faction/379) got worse (<span class='text-danger'>-1</span>)


Your faction standing with [Deeppockets](/faction/241) got better (<span class='text-success'>+1</span>)


Your faction standing with [Ebon Mask](/faction/244) got worse (<span class='text-danger'>-3</span>)


 &#127873; **You receive:** eq.ChooseRandom( <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_544.png" alt="" /> <a
                                href="/item/10005" data-url="10005" class="tooltip-link link">Silver Stud</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_675.png" alt="" /> <a
                                href="/item/10038" data-url="10038" class="tooltip-link link">Silver Ring</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_946.png" alt="" /> <a
                                href="/item/10017" data-url="10017" class="tooltip-link link">Turquoise</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_949.png" alt="" /> <a
                                href="/item/10020" data-url="10020" class="tooltip-link link">Jasper</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_544.png" alt="" /> <a
                                href="/item/10006" data-url="10006" class="tooltip-link link">Silver Earring</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1042.png" alt="" /> <a
                                href="/item/10320" data-url="10320" class="tooltip-link link">Golden Ear Stud</a>) (+5000 exp)

 

**This NPC *should* return incorrect items given.**



## Signals

if(e.signal == 1) then


>**Jeet says:** I am working on it, Mater!!
end





