# Keeper Pain


## Dialog

**You say:** `hail`



>*Keeper Pain raises his gaze from his tomes to greet you. 'Ahh!! Welcome, seeker of knowledge! Come to fill your brains, have you? Look closer, adventurer. I have scribed some very powerful spells.*

**You say:** `wand of pain`



if **Faction** >= Amiable then



>*Keeper Pain drops his tome and monocle and looks at you sharply. 'What?!! Have you seen Revenant Vytrix? I let him borrow my wand for a quest. That was half a season ago!! I fear he is dust and my precious wand is lost.*


elseif **Faction** >= Indifferent then



>**Keeper Pain says:** No Iksar resident will have anything to do with you!


else



>**Keeper Pain says:** No Iksar resident will have anything to do with you!   Away from here before you find yourself dead.

end



## Turn-Ins



if **Faction** >= Amiable and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_809.png" alt="" /> <a
                                href="/item/12869" data-url="12869" class="tooltip-link link">Wand of Pain</a>) then


>*Keeper Pain begins jumping for joy. 'Yoohoo!! My wand!! Thank you. You must be some powerful adventurer. You can help me collect a few components. Fill this chest with a frost crystal, a cockatrice egg, a giant hornet egg and a plains pebble. Return the full chest to me and I shall offer you a spell I recently researched.*


Your faction standing with [Brood of Kotiz](/faction/443) got better (<span class='text-success'>+5</span>)




Your faction standing with [Legion of Cabilis](/faction/441) got better (<span class='text-success'>+1</span>)



 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_608.png" alt="" /> <a
                                href="/item/17041" data-url="17041" class="tooltip-link link">Component Chest</a> (+100 exp)

**You receive coin:** 0 <img src='/static/icons/item_644.png' width='14' height='14'/> 1-5 <img src='/static/icons/item_645.png' width='14' height='14'/> 0 <img src='/static/icons/item_646.png' width='14' height='14'/> 0 <img src='/static/icons/item_647.png' width='14' height='14'/> 

elseif **Faction** >= Amiable and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_836.png" alt="" /> <a
                                href="/item/12885" data-url="12885" class="tooltip-link link">Full Component Chest</a>) then


>**Keeper Pain says:** Yes this is exactly what I wanted. Here is your spell.


Your faction standing with [Brood of Kotiz](/faction/443) got better (<span class='text-success'>+5</span>)




Your faction standing with [Legion of Cabilis](/faction/441) got better (<span class='text-success'>+1</span>)



 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/15444" data-url="15444" class="tooltip-link link">Spell: Renew Bones</a> 

 


**This NPC *should* return incorrect items given.**
