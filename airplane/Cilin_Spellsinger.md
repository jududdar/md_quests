# Cilin Spellsinger


## Dialog

**You say:** `Hail`



>**Cilin Spellsinger says:** Greetings Soandso.  Do you feel that you are ready to be tested in song?

**You say:** `tested`



>**Cilin Spellsinger says:** The test of songs holds both joy and sorrow. Choose who you wish to begin with, Denise or Clarisa

**You say:** `clarisa`



>**Cilin Spellsinger says:** Then Clarisa it shall be. Simply read the contents of this journal and return it to me when you are ready for your test. If you decide that perhaps Clarisa is not who you wish to test you, simply destroy the book and come back to me when you are ready.


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_778.png" alt="" /> <a
                                href="/item/18542" data-url="18542" class="tooltip-link link">The Flute</a>

**You say:** `denise`



>**Cilin Spellsinger says:** Then Denise it shall be. You will want to peruse the contents of this journal before your test. When you are ready, simply hand it back to me and I will call Denise forth. If you decide that perhaps Denise is not who you want to test you, then destroy the book and see me again when you are ready.


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_778.png" alt="" /> <a
                                href="/item/18543" data-url="18543" class="tooltip-link link">Dark Song</a>
end



## Turn-Ins



if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_778.png" alt="" /> <a
                                href="/item/18542" data-url="18542" class="tooltip-link link">The Flute</a>) then 


>**Cilin Spellsinger says:** Farewell.


**Spawn NPC:**  [Clarisa Spiritsong](/npc/71081) at (**y:** 1388.9, **x:** 660.7)


**Cilin Spellsinger despawns.**

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_778.png" alt="" /> <a
                                href="/item/18543" data-url="18543" class="tooltip-link link">Dark Song</a>) then 


>**Cilin Spellsinger says:** Farewell.


**Spawn NPC:**  [Denise Songweaver](/npc/71082) at (**y:** 1368.4, **x:** 660.7)


**Cilin Spellsinger despawns.**

**This NPC *should* return incorrect items given.**

end