# Entariz



[Entariz](/npc/120018) is a level 57 Dragon Paladin that spawns in [Western Wastes](/zone/120).



## Dialog

**You say:** `hail`



if **Faction** >= Kindly then



>**Entariz says:** Greetings, Soandso. I have heard that one is amongst us in the lands which will aid us in our cause. If you are the one that seeks my ancient rune for your studies please make sure it is not used in vain. I do not talk to many that pass through here and I feel in my heart that it is you that shall help us.


elseif **Faction** >= Indifferent then



>**Entariz says:** You seem like a decent sort for a snack food, but there is nothing you can do for me this day.  Come back when you have done more work for the Claws.


else



>**Entariz says:** We do have many living enemies.  Let me correct this oversight.


**You say:** `rune`




if **Faction** >= Kindly then



>**Entariz says:** This rune is very powerful and I will not release it to just anyone. Are you the one that Jualicn sends?


elseif **Faction** >= Indifferent then



>**Entariz says:** You seem like a decent sort for a snack food, but there is nothing you can do for me this day.  Come back when you have done more work for the Claws.


else



>**Entariz says:** We do have many living enemies.  Let me correct this oversight.


**You say:** `jualicn`



if **Faction** >= Kindly then



>**Entariz says:** That is excellent. Jualicn is very wise indeed however he does not send just anyone on such an important task. If you are the one that he has informed me will come I am sure he must have given you something to present to me.



elseif **Faction** >= Indifferent then



>**Entariz says:** You seem like a decent sort for a snack food, but there is nothing you can do for me this day.  Come back when you have done more work for the Claws.


else



>**Entariz says:** We do have many living enemies.  Let me correct this oversight.

end



## Turn-Ins





if(**You possess item:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_967.png" alt="" /> <a
                                href="/item/1893" data-url="1893" class="tooltip-link link">Rune of Eradication</a> x 1


>**Entariz says:** Ah of course, Soandso. You will need a Rune of Eradication for your lexicon. We are counting on your loyalty. Remember that you will need to bring the teachings of Relinar to Lawyla for further instructions, as she requires them to pass on the magic to those worthy of it. I bid you farewell, Soandso.


Your faction standing with [Claws of Veeshan](/faction/430) got better (<span class='text-success'>+5</span>)


Your faction standing with [Yelinak](/faction/436) got better (<span class='text-success'>+1</span>)


Your faction standing with [Kromzek](/faction/448) got worse (<span class='text-danger'>-2</span>)


 &#127873; **You receive:** GiveAll( <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_646.png" alt="" /> <a
                                href="/item/1908" data-url="1908" class="tooltip-link link">Jualicns Token</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_967.png" alt="" /> <a
                                href="/item/1893" data-url="1893" class="tooltip-link link">Rune of Eradication</a>) (+1000 exp)

 


**Entariz despawns.**

**This NPC *should* return incorrect items given.**
