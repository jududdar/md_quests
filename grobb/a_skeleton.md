# a skeleton


## Dialog

**You say:** `hail`



>**a skeleton says:** Sorry. Nothing t' sell at this time. Maybe later. Good day.

**You say:** `back to the closet`



if **Faction** >= Amiable +100 then 




>**a skeleton says:** Back to the closet?! I just got out. I would go back if I had a pair of oven mittens.


elseif **Faction** >= Indifferent then



>**a skeleton says:** You're going to have to prove yourself a stronger aid to my masters, the Darkones.


else



>**a skeleton says:** I would like to assist you, but my masters say you are no friend of the Darkones and would rather see you dead.




end



## Turn-Ins





if **Faction** >= Amiable +100 and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_636.png" alt="" /> <a
                                href="/item/12211" data-url="12211" class="tooltip-link link">Grobb Oven Mittens</a>) then 


>**a skeleton says:** Ahh! Oven mittens! Kinda' large, don't you think?! Oh well, now I can bake all I want without burning my hands. OKAY! Lets go. I overheard some basher named Nanrum saying he spotted my friend, the butcher. You should ask him [where the skeleton] is.


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1070.png" alt="" /> <a
                                href="/item/12213" data-url="12213" class="tooltip-link link">The Baker</a> (+25 exp)

 


**a skeleton despawns.**

**This NPC *should* return incorrect items given.**

end