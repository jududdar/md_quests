# Ionat



[Ionat](/npc/120017) is a level 56 Dragon Warrior that spawns in [Western Wastes](/zone/120).



## Dialog

**You say:** `hail`



if **Faction** >= Kindly then



>**Ionat says:** Hello Soandso. It is good to see that you have traveled so far to be in my presence. I do believe that you are the one chosen to aid us in our fight against the giants. If you are then I am sure that you will need my rune for your research.


elseif **Faction** >= Indifferent then



>**Ionat says:** You seem like a decent sort for a snack food, but there is nothing you can do for me this day.  Come back when you have done more work for the Claws.


else



>**Ionat says:** We do have many living enemies.  Let me correct this oversight.


**You say:** `jualicn`



if **Faction** >= Kindly then



>**Ionat says:** You are the one that Jualicn speaks of?  Surely you must have something to symbolize your dediciation to our cause.



elseif **Faction** >= Indifferent then



>**Ionat says:** You seem like a decent sort for a snack food, but there is nothing you can do for me this day.  Come back when you have done more work for the Claws.


else



>**Ionat says:** We do have many living enemies.  Let me correct this oversight.


**You say:** `rune`




if **Faction** >= Kindly then



>**Ionat says:** I see. Many seek this rune that I keep for whatever magics they practice, however I can only release it to the one that aids Jualicn.


elseif **Faction** >= Indifferent then



>**Ionat says:** You seem like a decent sort for a snack food, but there is nothing you can do for me this day.  Come back when you have done more work for the Claws.


else



>**Ionat says:** We do have many living enemies.  Let me correct this oversight.

end



## Turn-Ins





if(**You possess item:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_967.png" alt="" /> <a
                                href="/item/1894" data-url="1894" class="tooltip-link link">Rune of Revenge</a> x 1


>**Ionat says:** Take this Rune of Revenge, Soandso. You will need it to extract retribution in remembrance of our dear Hsagra. I thank you for your contributions to our cause. It is good to have you amongst our ranks.


Your faction standing with [Claws of Veeshan](/faction/430) got better (<span class='text-success'>+5</span>)


Your faction standing with [Yelinak](/faction/436) got better (<span class='text-success'>+1</span>)


Your faction standing with [Kromzek](/faction/448) got worse (<span class='text-danger'>-2</span>)


 &#127873; **You receive:** GiveAll( <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_646.png" alt="" /> <a
                                href="/item/1908" data-url="1908" class="tooltip-link link">Jualicns Token</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_967.png" alt="" /> <a
                                href="/item/1894" data-url="1894" class="tooltip-link link">Rune of Revenge</a>) (+1000 exp)

 


**Ionat despawns.**

**This NPC *should* return incorrect items given.**
