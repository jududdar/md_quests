# Crusader Quarg



[Crusader Quarg](/npc/78072) is a level 50 Iksar Shadow Knight that spawns in [Field of Bone](/zone/78).






## Dialog

**You say:** `hail`



>*Crusader Quarg stands at attention and salutes you.  It would seem that he takes his job quite seriously.  'Do not fear, feeble soul.  The Crusaders of Greenmist are on duty.*

**You say:** `collect.* rok nilok`



if **Faction** >= Amiable then



>**Crusader Quarg says:** Take this chest.  Inside, you shall combine the skull of their leader and at least five of the caste members.  You must then go to the swamp garrison and deliver the full chest along with your iron cudgel of the mystic to Mystic Dovan.  Go to him now and inquire of the crusaders of Rok Nilok.



 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_608.png" alt="" /> <a
                                href="/item/17035" data-url="17035" class="tooltip-link link">A Skull Chest</a>


elseif **Faction** >= Indifferent then



>**Crusader Quarg says:** Show greater devotion to the Crusaders of Greenmist and you will obtain that which you seek.


else



>*Crusader Quarg eye's glare red and gnashes his teeth.  'You had best avoid all members of the Temple of Terror.*

end



## Turn-Ins





if **Faction** >= Amiable and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_868.png" alt="" /> <a
                                href="/item/18054" data-url="18054" class="tooltip-link link">The Bone Garrison</a>) then


>**Crusader Quarg says:** Ah, i see you have proven yourself to Zand and he wishes to see more of your prowess.  go to the Tower of Kurn and bring him the Skulls of the Caste of Bone Brethren, a caste of powerful shamans who perished fighting undead in the Field of Bone several decades ago.


Your faction standing with [Scaled Mystics](/faction/445) got better (<span class='text-success'>+10</span>)


Your faction standing with [Legion of Cabilis](/faction/441) got better (<span class='text-success'>+10</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_608.png" alt="" /> <a
                                href="/item/17034" data-url="17034" class="tooltip-link link">A Skull Chest</a> (+10000 exp)

 



elseif **Faction** >= Amiable and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_578.png" alt="" /> <a
                                href="/item/5142" data-url="5142" class="tooltip-link link">Iron Cudgel of the Seer</a>) then


>**Crusader Quarg says:** The temple shall be pleased. As instructed by the Hierophants, here is your Iron Cudgel of the Mystic. You have done well that I must ask you to [collect the Crusaders of Rok Nilok].


Your faction standing with [Scaled Mystics](/faction/445) got better (<span class='text-success'>+10</span>)


Your faction standing with [Legion of Cabilis](/faction/441) got better (<span class='text-success'>+10</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_578.png" alt="" /> <a
                                href="/item/5143" data-url="5143" class="tooltip-link link">Iron Cudgel of the Mystic</a> (+20000 exp)

 

**This NPC *should* return incorrect items given.**
 




