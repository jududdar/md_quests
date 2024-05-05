# Medicine Man Veetra



[Medicine Man Veetra](/npc/71044) is a level 55 Efreeti Warrior that spawns in [Plane of Sky (Instanced)](/zone/1071).



## Dialog

**You say:** `Hail`



>**Medicine Man Veetra says:** Good day to you, Soandso. Are you a shaman of [much experience]?

**You say:** `much experience`



>**Medicine Man Veetra says:** Then welcome to the tests of the medicine man. I have two tomes, each tells of a shaman of great accomplishment. They are Gina MacStargan and Ooga. Simply tell me the name of the shaman you want to be tested by.

**You say:** `gina`



>**Medicine Man Veetra says:** Return this tome to me if you wish me to call forth Gina. Destroy it if you do not.


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_778.png" alt="" /> <a
                                href="/item/18544" data-url="18544" class="tooltip-link link">Spirits Among Us</a>

**You say:** `ooga`



>**Medicine Man Veetra says:** Return this tome if you wish me to summon Ooga to assist you. Destroy it if you do not.


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_778.png" alt="" /> <a
                                href="/item/18545" data-url="18545" class="tooltip-link link">Alkeme</a>
end



## Turn-Ins



if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_778.png" alt="" /> <a
                                href="/item/18544" data-url="18544" class="tooltip-link link">Spirits Among Us</a>) then 


>**Medicine Man Veetra says:** I am no longer needed and will take my leave.


**Spawn NPC:**  [Gina McStargan](/npc/71087) at (**y:** 1401.9, **x:** 631.9)


**Medicine Man Veetra despawns.**

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_778.png" alt="" /> <a
                                href="/item/18545" data-url="18545" class="tooltip-link link">Alkeme</a>) then 


>**Medicine Man Veetra says:** I am no longer needed and will take my leave.


**Spawn NPC:**  [Ooga](/npc/71093) at (**y:** 1399.0, **x:** 653.4)


**Medicine Man Veetra despawns.**

**This NPC *should* return incorrect items given.**

end