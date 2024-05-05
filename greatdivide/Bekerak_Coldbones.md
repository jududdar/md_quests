# Bekerak Coldbones



[Bekerak Coldbones](/npc/118011) is a level 35 Giant Warrior that spawns in [The Great Divide](/zone/118).



## Dialog

**You say:** `hail`



if **Faction** >= Apprehensive then



>**Bekerak Coldbones says:** Just another boring day waiting for supplies.  I wonder when they will arrive.


else



**Bekerak Coldbones says one of the following:**

>I didn't know Slime could speak common. Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here? Now go away!

>I wonder how much I could get for the tongue of a blithering fool? Leave before I decide to find out for myself.


**You say:** `supplies`



if **Faction** >= Indifferent then



>**Bekerak Coldbones says:** We are supposed to receive a shipment of supplies each month from Kael Drakkel.  This months seems to be late.  I hope Wenglawks has not forgotten us.


else



**Bekerak Coldbones says one of the following:**

>I didn't know Slime could speak common. Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here? Now go away!

>I wonder how much I could get for the tongue of a blithering fool? Leave before I decide to find out for myself.

end



## Turn-Ins





if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_776.png" alt="" /> <a
                                href="/item/25106" data-url="25106" class="tooltip-link link">Bekeraks New Spear</a>) then 


>**Bekerak Coldbones says:** Well, well, I see Wenglawks finally got around to sending me my new spear. I hope it's not as shoddy as the last one. Your payment? Bahaha, did Wenglawks not tell you? Payment was to be a giant icewurm tooth carved into an amulet. Come now, little one. I will find an ice wurm for us to slay together. Then you can pull one of its teeth out for me and I will fashion the talisman for that greedy merchant.


**Spawn NPC:**  [\#an angry shardwurm](/npc/118016) at (**y:** -3011, **x:** -2776)

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_800.png" alt="" /> <a
                                href="/item/25191" data-url="25191" class="tooltip-link link">Giant Shard Wurm Tooth</a>) then 


>*Bekerak Coldbones pulls out a large knife and begins to carve at the tooth. After a few minutes he pulls out a length of rope and fashions it into a very large necklace. 'Here is his payment. Tell him the spear is fine, and that I might reconsider his last offer to me. He will know what I mean.'*


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_800.png" alt="" /> <a
                                href="/item/25130" data-url="25130" class="tooltip-link link">Giant Icewurm Talisman</a> 

 

elseif **Faction** >= Indifferent and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_690.png" alt="" /> <a
                                href="/item/25266" data-url="25266" class="tooltip-link link">Giant Sack of Supplies</a>) then 


>**Bekerak Coldbones says:** Supplies from Svekk?  Where are the rest of them little one!  There must be more, we are here pushing the Coldain back into their hole in the wall and Svekk sends a " .. e.other:Race() .. " to deliver a small portion of supplies.  Take this note back to that fool.  Leave quickly before I take my rage out upon you.


Your faction standing with [Kromrif](/faction/419) got better (<span class='text-success'>+1</span>)


Your faction standing with [Kromzek](/faction/448) got better (<span class='text-success'>+1</span>)


Your faction standing with [Coldain](/faction/406) got worse (<span class='text-danger'>-1</span>)


Your faction standing with [Claws of Veeshan](/faction/430) got worse (<span class='text-danger'>-1</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_868.png" alt="" /> <a
                                href="/item/25267" data-url="25267" class="tooltip-link link">Bekerak's Letter to Svekk</a> (+250 exp)

 

Bekerak's Letter to Svekk

elseif **Faction** >= Indifferent and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_690.png" alt="" /> <a
                                href="/item/25269" data-url="25269" class="tooltip-link link">Large Supply Sack for Bekerak</a>) then 


>**Bekerak Coldbones says:** I am in your debt, " .. e.other:Race() .. ".  These supplies will help our effort to destroy the Coldain.  I wish I had more to give than what I do.'  Bekerak pulls a strange looking totem on a string from one of his pockets and hands it to you.  'May Lord Rallos smile upon you, Soandso.'


Your faction standing with [Kromrif](/faction/419) got better (<span class='text-success'>+1</span>)


Your faction standing with [Kromzek](/faction/448) got better (<span class='text-success'>+1</span>)


Your faction standing with [Coldain](/faction/406) got worse (<span class='text-danger'>-1</span>)


Your faction standing with [Claws of Veeshan](/faction/430) got worse (<span class='text-danger'>-1</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1007.png" alt="" /> <a
                                href="/item/25268" data-url="25268" class="tooltip-link link">Kromrif Battle Totem</a> (+250 exp)

 

Kromrif Battle Totem

**This NPC *should* return incorrect items given.**
