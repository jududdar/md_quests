# Bronin Higginsbot



[Bronin Higginsbot](/npc/33079) is a level 9 Halfling Rogue that spawns in [Misty Thicket](/zone/33).



## Dialog

**You say:** `hail`



>**Bronin Higginsbot says:** Hello. It is dangerous out in the woods. You should go to Rivervale. It's at theof the path. You will find good times there. Travel safely, my friend!

**You say:** `shard`



>**Bronin Higginsbot says:** Searching for that blasted emerald shard, are you? That thing has done nothing but bring me bad luck!! I would gladly give it to you if you would do a [small favor] for me.

**You say:** `small favor`



if( **Faction is** > Indifferent) then



>**Bronin Higginsbot says:** I have been tracked here by a bounty hunter named Slaythe. I have heard reports of his presence beyond the Great Wall. Please seek him out and bring me some body part of his as proof of his passing. Do this and the emerald shard is yours.



if(**spawned NPC:**  [Slaythe](/npc/33146) == false) then




 **Spawn NPC:**  [Slaythe](/npc/33146) at (**y:** 664.00, **x:** 893.00)




elseif( **Faction is** > Apprehensive) then



>**Bronin Higginsbot says:** When the blood of many Runnyeye goblins has covered your blade, then I shall find you worthy to speak of such matters.


else



>**Bronin Higginsbot says:** You are no ally of the Rivervale Deeppockets!! Leave at once!!


**You say:** `second piece of the gem`



if( **Faction is** > Indifferent) then



>**Bronin Higginsbot says:** The second emerald shard was hidden in the forest near Kelethin. I heard one of the local guilds found it and now call it the Gem of Tunare. You will have to ask around in Kelethin about it. Good luck.


elseif( **Faction is** > Apprehensive) then



>**Bronin Higginsbot says:** When the blood of many Runnyeye goblins has covered your blade, then I shall find you worthy to speak of such matters.


else



>**Bronin Higginsbot says:** You are no ally of the Rivervale Deeppockets!! Leave at once!!

end



## Turn-Ins



if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_592.png" alt="" /> <a
                                href="/item/13110" data-url="13110" class="tooltip-link link">Bloody Shank</a>) then 


>**Bronin Higginsbot says:** AHH!! You have been sent by the Highkeep Guards!! You will never take Bronin Higginsbot alive!!


Your faction standing with [Deeppockets](/faction/241) got worse (<span class='text-danger'>-50</span>)


Your faction standing with [Circle of Unseen Hands](/faction/223) got worse (<span class='text-danger'>-2</span>)


Your faction standing with [Merchants of Rivervale](/faction/292) got better (<span class='text-success'>+2</span>)


Your faction standing with [Coalition of Tradefolk Underground](/faction/336) got worse (<span class='text-danger'>-2</span>)


Your faction standing with [Carson McCabe](/faction/329) got worse (<span class='text-danger'>-2</span>)


e.self:AddItem(13111,0);


**Bronin Higginsbot attacks you.**

elseif(( **Faction is** > Indifferent) and ( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1068.png" alt="" /> <a
                                href="/item/12192" data-url="12192" class="tooltip-link link">A Froglok Leg</a>)) then 


>**Bronin Higginsbot says:** So I see you have defeated Slaythe. I shall sleep much better now that he is gone. I placed the emerald shard in one of the Highkeep strongboxes in Highpass. Give the Bank Clerk this key. There is a [second piece of the gem] which I hid near Kelethin. You will need it to complete the gem. I hope it brings you better luck than I.


Your faction standing with [Deeppockets](/faction/241) got better (<span class='text-success'>+10</span>)


Your faction standing with [Circle of Unseen Hands](/faction/223) got better (<span class='text-success'>+1</span>)


Your faction standing with [Merchants of Rivervale](/faction/292) got worse (<span class='text-danger'>-1</span>)


Your faction standing with [Coalition of Tradefolk Underground](/faction/336) got better (<span class='text-success'>+1</span>)


Your faction standing with [Carson McCabe](/faction/329) got better (<span class='text-success'>+1</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1081.png" alt="" /> <a
                                href="/item/12193" data-url="12193" class="tooltip-link link">H.K. 106</a> (+500 exp)

 

**This NPC *should* return incorrect items given.**





