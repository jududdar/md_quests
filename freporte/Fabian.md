# Fabian



[Fabian](/npc/10114) is a level 25 Human Bard that spawns in [East Freeport](/zone/10).



## Dialog

**You say:** `hail`




if( **Faction is** > Amiable) then



>**Fabian says:** Greetings, merry gentlefolk! If you enjoy the music, please feel free to cross my palm with gold.


else



>**Fabian says:** Oh look, a talking lump of refuse. How novel!

end



## Turn-Ins



local etched = 0;



if( **You turn in:** gold = 2) then


>**Fabian says:** Rat spittle! Busted another string! You seem like a good music loving citizen, could you please run to the Wind Spirit's Song and grab me a fresh set of lute strings?


e.other:Ding();





Your faction standing with [League of Antonican Bards](/faction/284) got better (<span class='text-success'>+2</span>)


Your faction standing with [Knights of Truth](/faction/281) got better (<span class='text-success'>+1</span>)


Your faction standing with [Guards of Qeynos](/faction/262) got better (<span class='text-success'>+1</span>)


Your faction standing with [Ring of Scale](/faction/304) got worse (<span class='text-danger'>-1</span>)


Your faction standing with [Mayong Mistmoore](/faction/285) got worse (<span class='text-danger'>-1</span>)

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_853.png" alt="" /> <a
                                href="/item/13709" data-url="13709" class="tooltip-link link">Lute Strings</a>) then 


>**Fabian says:** 'Many thanks, merry gentlefolk! Let me cross your palm in gratitude for your kindness. Hmmmm where did my lucky coin go?





Your faction standing with [League of Antonican Bards](/faction/284) got better (<span class='text-success'>+2</span>)


Your faction standing with [Knights of Truth](/faction/281) got better (<span class='text-success'>+1</span>)


Your faction standing with [Guards of Qeynos](/faction/262) got better (<span class='text-success'>+1</span>)


Your faction standing with [Ring of Scale](/faction/304) got worse (<span class='text-danger'>-1</span>)


Your faction standing with [Mayong Mistmoore](/faction/285) got worse (<span class='text-danger'>-1</span>)


if(math.random(1,3) == 3) then 



 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_646.png" alt="" /> <a
                                href="/item/13710" data-url="13710" class="tooltip-link link">An Etched Silver Coin</a> 

 



note = You only get the coin sometimes



 &#127873; **You receive:** 0 (+5000 exp)

**You receive coin:** 1 <img src='/static/icons/item_644.png' width='14' height='14'/> 1-10 <img src='/static/icons/item_645.png' width='14' height='14'/> 1-20 <img src='/static/icons/item_646.png' width='14' height='14'/> 0 <img src='/static/icons/item_647.png' width='14' height='14'/> 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_646.png" alt="" /> <a
                                href="/item/13710" data-url="13710" class="tooltip-link link">An Etched Silver Coin</a>) then 


>**Fabian says:** 'My lucky coin! How did it get in there? Well, never mind that. You are an honest person and although honesty is its own reward, I feel obligated to return the favor. Take this to Dionna if you enjoy music. Farewell friend!


Your faction standing with [League of Antonican Bards](/faction/284) got better (<span class='text-success'>+2</span>)


Your faction standing with [Knights of Truth](/faction/281) got better (<span class='text-success'>+1</span>)


Your faction standing with [Guards of Qeynos](/faction/262) got better (<span class='text-success'>+1</span>)


Your faction standing with [Ring of Scale](/faction/304) got worse (<span class='text-danger'>-1</span>)


Your faction standing with [Mayong Mistmoore](/faction/285) got worse (<span class='text-danger'>-1</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/13708" data-url="13708" class="tooltip-link link">Note from Fabian</a> (+5000 exp)

 

**This NPC *should* return incorrect items given.**
