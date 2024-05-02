# Diggins
## Dialog

**You say:** `hail`



if **Faction** >= Apprehensive then



>**Diggins says:** How is life treating you, bud? What are you doing around the mines? Either you are a [member of 628] or you are lost. If you are lost, I can't help you. I ain't no guide.


else



>**Diggins says:** The word around the mines is that you are not to be trusted. You'd best leave before my dagger finds a new home in your back.


**You say:** `628`



if **Faction** >= Amiable +100 then 



>**Diggins says:** It's my duty to assign [guild tasks] to all new members of Mining Guild 628.


elseif **Faction** >= Indifferent then



>**Diggins says:** Don't take this personally, but I can't quite trust you with such matters. Maybe a few less Butcherblock bandits would prove your worth.


else



>**Diggins says:** The word around the mines is that you are not to be trusted. You'd best leave before my dagger finds a new home in your back.


**You say:** `tasks`



if **Faction** >= Amiable +100 then 



>**Diggins says:** I see you are interested in helping out. Good! For starters, go into the surrounding territory of Kaladim and destroy all the goblins. We hear they sometimes carry necklaces of ornate design. 628 wants these Runnyeye warbeads. You bring me no fewer than four and I will pay you and maybe, just maybe, I may have an extra piercing weapon lying around which has your name on it.


elseif **Faction** >= Indifferent then



>**Diggins says:** Don't take this personally, but I can't quite trust you with such matters. Maybe a few less Butcherblock bandits would prove your worth.


else



>**Diggins says:** The word around the mines is that you are not to be trusted. You'd best leave before my dagger finds a new home in your back.


**You say:** `pick`



if **Faction** >= Amiable +100 then 



>**Diggins says:** So you want to earn a parrying pick? Consider it an honor that I am even speaking of this with you. The guild had these picks made just for us. It is a magic item used to fend off attacks. Before you can have one, you will have to do me a [great favor].


elseif **Faction** >= Indifferent then



>**Diggins says:** Don't take this personally, but I can't quite trust you with such matters. Maybe a few less Butcherblock bandits would prove your worth.


else



>**Diggins says:** The word around the mines is that you are not to be trusted. You'd best leave before my dagger finds a new home in your back.


**You say:** `great favor`



if **Faction** >= Amiable +100 then 



>**Diggins says:** Mater has asked me to exterminate the dwarven family of Dunfire. They were once members of our guild. They left and now use their talents to aid the Butcherblock bandits. We will not allow them to speak of the skills we taught them. Go and rip out their tongues. Return the tongues of Crytil, Rondo, Keldyn, and Barma Dunfire and the parrying pick is yours.


elseif **Faction** >= Indifferent then



>**Diggins says:** Don't take this personally, but I can't quite trust you with such matters. Maybe a few less Butcherblock bandits would prove your worth.


else



>**Diggins says:** The word around the mines is that you are not to be trusted. You'd best leave before my dagger finds a new home in your back.

end

## Turn-Ins



local text = "Didn't I explain to you that I will only reward you upon the return of FOUR Runnyeye warbeads?";

local text1 = "I called for the Tongues of Crytil, Rondo, Keldyn and Barma!";



if **Faction** >= Amiable +100 and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_848.png" alt="" /> <a
                                href="/item/13931" data-url="13931" class="tooltip-link link">RunnyEye Warbeads</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_848.png" alt="" /> <a
                                href="/item/13931" data-url="13931" class="tooltip-link link">RunnyEye Warbeads</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_848.png" alt="" /> <a
                                href="/item/13931" data-url="13931" class="tooltip-link link">RunnyEye Warbeads</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_848.png" alt="" /> <a
                                href="/item/13931" data-url="13931" class="tooltip-link link">RunnyEye Warbeads</a>) then 


>**Diggins says:** Good work. We shall add these to the stash. Here is your reward, as promised. Be happy with it and continue your work. Maybe soon you shall be able to [earn a parrying pick].





Your faction standing with [Miners Guild 628](/faction/322) got better (<span class='text-success'>+10</span>)


Your faction standing with [Circle of Unseen Hands](/faction/223) got worse (<span class='text-danger'>-1</span>)


Your faction standing with [Butcherblock Bandits](/faction/379) got worse (<span class='text-danger'>-1</span>)


Your faction standing with [Deeppockets](/faction/241) got better (<span class='text-success'>+1</span>)


Your faction standing with [Ebon Mask](/faction/244) got worse (<span class='text-danger'>-1</span>)


 &#127873; **You receive:** eq.ChooseRandom( <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_592.png" alt="" /> <a
                                href="/item/7007" data-url="7007" class="tooltip-link link">Rusty Dagger</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_762.png" alt="" /> <a
                                href="/item/7008" data-url="7008" class="tooltip-link link">Rusty Rapier</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_776.png" alt="" /> <a
                                href="/item/7009" data-url="7009" class="tooltip-link link">Rusty Spear</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_740.png" alt="" /> <a
                                href="/item/7010" data-url="7010" class="tooltip-link link">Rusty Shortened Spear</a>) (+5000 exp)

**You receive coin:** 0 <img src='/static/icons/item_644.png' width='14' height='14'/> 0 <img src='/static/icons/item_645.png' width='14' height='14'/> 0-5 <img src='/static/icons/item_646.png' width='14' height='14'/> 0-5 <img src='/static/icons/item_647.png' width='14' height='14'/> 

elseif **Faction** >= Amiable +100 and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1087.png" alt="" /> <a
                                href="/item/12170" data-url="12170" class="tooltip-link link">Crytils Tongue</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1087.png" alt="" /> <a
                                href="/item/12172" data-url="12172" class="tooltip-link link">Keldyns Tongue</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1087.png" alt="" /> <a
                                href="/item/12174" data-url="12174" class="tooltip-link link">Barmas Tongue</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1087.png" alt="" /> <a
                                href="/item/12178" data-url="12178" class="tooltip-link link">Rondos Tongue</a>) then 


>**Diggins says:** Excellent work!! You are quite an asset to this mining guild. Please accept this Parrying Pick 628 for your great service. If you truly wish to serve our guild. Go and speak with Mater. Tell him you are [ready to earn Mining Pick 628].


Your faction standing with [Miners Guild 628](/faction/322) got better (<span class='text-success'>+10</span>)


Your faction standing with [Circle of Unseen Hands](/faction/223) got worse (<span class='text-danger'>-1</span>)


Your faction standing with [Butcherblock Bandits](/faction/379) got worse (<span class='text-danger'>-1</span>)


Your faction standing with [Deeppockets](/faction/241) got better (<span class='text-success'>+1</span>)


Your faction standing with [Ebon Mask](/faction/244) got worse (<span class='text-danger'>-1</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_888.png" alt="" /> <a
                                href="/item/12166" data-url="12166" class="tooltip-link link">Parrying Pick 628</a> (+5000 exp)

 

**This NPC *should* return incorrect items given.**
