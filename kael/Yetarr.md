# Yetarr


## Dialog

**You say:** `hail`



if **Faction** >= Apprehensive then



>**Yetarr says:** Soandso, your name has reached my ears more than a few times. Rumors fly that your kind will be the downfall of both the dragons and the Coldain.


else



**Yetarr says one of the following:**

>I didn't know Slime could speak common. Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here? Now go away!

>I wonder how much I could get for the tongue of a blithering fool? Leave before I decide to find out for myself.


**You say:** `dragon`



if **Faction** >= Amiable +300 then



>**Yetarr says:** The dragons are not my primary concern, Kyenka has a greater hatred for them. I leave matters regarding to them in his capable hands. My worries are of the Coldain.


elseif **Faction** >= Indifferent then



>**Yetarr says:** You need to prove your dedication to our cause before I can discuss such matters with you.




else



**Yetarr says one of the following:**

>I didn't know Slime could speak common. Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here? Now go away!

>I wonder how much I could get for the tongue of a blithering fool? Leave before I decide to find out for myself.


**You say:** `coldain`



if **Faction** >= Amiable +300 then



>**Yetarr says:** I do not fully trust the Kromrif to keep Kael Drakkel protected from the menace of the tiny savages. The Kromrif do not actively seek to kill them. If the Coldain are left to breed they will one day swarm over Kael and no number of Kromzek warriors will be able to save us.


elseif **Faction** >= Indifferent then



>**Yetarr says:** You need to prove your dedication to our cause before I can discuss such matters with you.




else



**Yetarr says one of the following:**

>I didn't know Slime could speak common. Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here? Now go away!

>I wonder how much I could get for the tongue of a blithering fool? Leave before I decide to find out for myself.


**You say:** `kromrif`



if **Faction** >= Amiable +300 then



>**Yetarr says:** The Frost giants who call Kael their home have grown far too lax. So few of them train daily and actively seek out the Coldain to slay. I have advised King Tormax to send Kromzek raiding parties to raze Thurgadin, however, each time he reminds me that our strongest warriors must stay to guard against the dragon menace. What I need is a band of mercenaries to seek out and assassinate key Coldain leaders. We must destroy their ability to make war.


elseif **Faction** >= Indifferent then



>**Yetarr says:** You need to prove your dedication to our cause before I can discuss such matters with you.




else



**Yetarr says one of the following:**

>I didn't know Slime could speak common. Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here? Now go away!

>I wonder how much I could get for the tongue of a blithering fool? Leave before I decide to find out for myself.


**You say:** `assassinate`



if **Faction** >= Amiable +300 then



>**Yetarr says:** Perhaps assassinate is not the best word. I simply wish the death of some of the more compitent (sic) advisors of that foolish Dain. Within the halls of Icewell keep dwells a huntsman that has stood by the Dains side since he was a mere child. The court scribe is also more then he appears to be. Bring me their heads, I will reward you for each one. That is the only proof I will take of their deaths.


elseif **Faction** >= Indifferent then



>**Yetarr says:** You need to prove your dedication to our cause before I can discuss such matters with you.




else



**Yetarr says one of the following:**

>I didn't know Slime could speak common. Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here? Now go away!

>I wonder how much I could get for the tongue of a blithering fool? Leave before I decide to find out for myself.

end



## Turn-Ins





if **Faction** >= Amiable +300 and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_990.png" alt="" /> <a
                                href="/item/25122" data-url="25122" class="tooltip-link link">Head of the Huntsman</a>) then 


>**Yetarr says:** The death of this one must be causing great strife amoung the Coldain. Your work is greatly appreciated. I wish I could reward you with more, but these boots are among the few things I have to give.


Your faction standing with [Kromzek](/faction/448) got better (<span class='text-success'>+30</span>)


Your faction standing with [Kromrif](/faction/419) got better (<span class='text-success'>+7</span>)


Your faction standing with [King Tormax](/faction/429) got better (<span class='text-success'>+7</span>)


Your faction standing with [Claws of Veeshan](/faction/430) got worse (<span class='text-danger'>-15</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_633.png" alt="" /> <a
                                href="/item/25027" data-url="25027" class="tooltip-link link">Coldain Skin Boots</a> (+75000 exp)

 

elseif **Faction** >= Amiable +300 and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_990.png" alt="" /> <a
                                href="/item/25123" data-url="25123" class="tooltip-link link">Head of the Royal Scribe</a>) then 


>**Yetarr says:** Take these gloves and continue to strike fear into the heart of the Coldain.  A daring raid upon Icewell Keep itself deserves no less.


Your faction standing with [Kromzek](/faction/448) got better (<span class='text-success'>+30</span>)


Your faction standing with [Kromrif](/faction/419) got better (<span class='text-success'>+7</span>)


Your faction standing with [King Tormax](/faction/429) got better (<span class='text-success'>+7</span>)


Your faction standing with [Claws of Veeshan](/faction/430) got worse (<span class='text-danger'>-15</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_636.png" alt="" /> <a
                                href="/item/25026" data-url="25026" class="tooltip-link link">Coldain Skin Gloves</a> (+75000 exp)

 

**This NPC *should* return incorrect items given.**



## Combat


if (not e.joined) then


e.self:SetRunning(false);
end
