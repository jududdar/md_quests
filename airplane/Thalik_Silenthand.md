# Thalik Silenthand


## Dialog

**You say:** `hail`



>**Thalik Silenthand says:** Greetings, Soandso.  Do you believe you are a great rogue?

**You say:** `great rogue`



>**Thalik Silenthand says:** I will not take your word for it!  You must prove your greatness to one of my apprentices.  Do you wish to be tested by Rayne or by Kendrick?

**You say:** `Rayne`



>**Thalik Silenthand says:** Rayne it shall be.  Take this book and read it.  When you are finished, hand it back to me and I shall summon the mighty rogue Rayne to test you.


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_778.png" alt="" /> <a
                                href="/item/18522" data-url="18522" class="tooltip-link link">Tome of Shadows</a>

**You say:** `Kendrick`



>**Thalik Silenthand says:** Kendrick it shall be.  Take this book and read it.  When you are finished, hand it back to me and I shall summon the mighty rogue Kendrick to test you.


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_778.png" alt="" /> <a
                                href="/item/18523" data-url="18523" class="tooltip-link link">Silent Strider</a>
end




## Turn-Ins



if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_778.png" alt="" /> <a
                                href="/item/18522" data-url="18522" class="tooltip-link link">Tome of Shadows</a>) then 



>**Thalik Silenthand says:** Farewell.


**Spawn NPC:**  [Rayne](/npc/71061) at (**y:** 1372.6, **x:** 563.3)


**Thalik Silenthand despawns.**

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_778.png" alt="" /> <a
                                href="/item/18523" data-url="18523" class="tooltip-link link">Silent Strider</a>) then 


>**Thalik Silenthand says:** Farewell.


**Spawn NPC:**  [Kendrick](/npc/71068) at (**y:** 1372.6, **x:** 563.3)


**Thalik Silenthand despawns.**

**This NPC *should* return incorrect items given.**

end