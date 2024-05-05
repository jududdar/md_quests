# Kyenka



[Kyenka](/npc/113133) is a level 57 Giant Shaman that spawns in [Kael Drakkel](/zone/113).



## Dialog

**You say:** `hail`



if **Faction** >= Indifferent then



>**Kyenka says:** My, it is the great Soandso who stands before me! Rumors of your greatness have spread even to the court of King Tormax. I am Kyenka, Duke of Kael Drakkel. I advise King Tormax on matters concerning the nefarious dragons.


else



**Kyenka says one of the following:**

>I didn't know Slime could speak common. Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here? Now go away!

>I wonder how much I could get for the tongue of a blithering fool? Leave before I decide to find out for myself.


**You say:** `dragon`



if **Faction** >= Amiable +300 then



>**Kyenka says:** The living dragons of this realm are the bane of Kael Drakkel and its people. Eventually they will be gone and only we Kromzek will remain. We will purge this land of their menace.


elseif **Faction** >= Indifferent then



>**Kyenka says:** You need to prove your dedication to our cause before I can discuss such matters with you.




else



**Kyenka says one of the following:**

>I didn't know Slime could speak common. Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here? Now go away!

>I wonder how much I could get for the tongue of a blithering fool? Leave before I decide to find out for myself.


**You say:** `purge`



if **Faction** >= Amiable +300 then



>**Kyenka says:** The beasts must be slain. They only bring strife to this world. You are a powerful mercenary, and are sympathetic to my cause, I would assume. You could become rich beyond your wildest dreams by assisting King Tormax and me.


elseif **Faction** >= Indifferent then



>**Kyenka says:** You need to prove your dedication to our cause before I can discuss such matters with you.




else



**Kyenka says one of the following:**

>I didn't know Slime could speak common. Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here? Now go away!

>I wonder how much I could get for the tongue of a blithering fool? Leave before I decide to find out for myself.


**You say:** `assist`



if **Faction** >= Amiable +300 then



>**Kyenka says:** Rally together a band of adventurers and track down and slay the elder dragons of this continent. For each head you return to me I will impart a gift to you.


elseif **Faction** >= Indifferent then



>**Kyenka says:** You need to prove your dedication to our cause before I can discuss such matters with you.




else



**Kyenka says one of the following:**

>I didn't know Slime could speak common. Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here? Now go away!

>I wonder how much I could get for the tongue of a blithering fool? Leave before I decide to find out for myself.

end



## Turn-Ins





if **Faction** >= Amiable +300 and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1231.png" alt="" /> <a
                                href="/item/25119" data-url="25119" class="tooltip-link link">Great Dragon's Head</a>) then


>**Kyenka says:** This beast must have taken quite a force to slay. These boots have been crafted to reward your kind for such great efforts. Take them and wear them with pride. They will be a warning to other dragons that you are a great slayer of their kind.


Your faction standing with [Kromzek](/faction/448) got better (<span class='text-success'>+30</span>)


Your faction standing with [Kromrif](/faction/419) got better (<span class='text-success'>+7</span>)


Your faction standing with [King Tormax](/faction/429) got better (<span class='text-success'>+7</span>)


Your faction standing with [Claws of Veeshan](/faction/430) got worse (<span class='text-danger'>-15</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_633.png" alt="" /> <a
                                href="/item/25029" data-url="25029" class="tooltip-link link">Barbed Dragonscale Boots</a> (+75000 exp)

 

elseif **Faction** >= Amiable +300 and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1231.png" alt="" /> <a
                                href="/item/25118" data-url="25118" class="tooltip-link link">Greater Dragon's Head</a>) then


>**Kyenka says:** You serve the crown well, Soandso. This is one less beast to ruin our lands. Take these pauldrons which I have fashioned from the first dragon scales brought to King Tormax's court.


Your faction standing with [Kromzek](/faction/448) got better (<span class='text-success'>+30</span>)


Your faction standing with [Kromrif](/faction/419) got better (<span class='text-success'>+7</span>)


Your faction standing with [King Tormax](/faction/429) got better (<span class='text-success'>+7</span>)


Your faction standing with [Claws of Veeshan](/faction/430) got worse (<span class='text-danger'>-15</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_798.png" alt="" /> <a
                                href="/item/25028" data-url="25028" class="tooltip-link link">Barbed Dragonscale Pauldrons</a> (+75000 exp)

 

**This NPC *should* return incorrect items given.**



## Combat


if (not e.joined) then


e.self:SetRunning(false);

else


**Signaled to:**  [\#Sentinel Weldren](/npc/113137)


**Signaled to:**  [\#Sentinel Drakeslayer](/npc/113136)
end
