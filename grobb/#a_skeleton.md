# a skeleton


## Dialog

**You say:** `hail`



>**a skeleton says:** Step right up! I am the best butcher you have ever seen. Well, are you the next to be fileted?

**You say:** `back to the closet`



if **Faction** >= Amiable +100 then 




>**a skeleton says:** Darn! I was just starting to have fun. Tell you what, you find me a nice ogre butcher apron and I will gladly go back to my cramped quarters.


elseif **Faction** >= Indifferent then



>**a skeleton says:** You're going to have to prove yourself a stronger aid to my masters, the Darkones.


else



>**a skeleton says:** I would like to assist you, but my masters say you are no friend of the Darkones and would rather see you dead.


end



## Turn-Ins





if **Faction** >= Amiable +100 and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_632.png" alt="" /> <a
                                href="/item/12217" data-url="12217" class="tooltip-link link">Ogre Butcher Apron</a>) then 


>**a skeleton says:** Great! Thanks a lot, pal. Lets get moving. I hear my bonehead roomie called the Captain was spotted by Basher Sklama. Go ask [where the Captain] is.


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1070.png" alt="" /> <a
                                href="/item/12214" data-url="12214" class="tooltip-link link">The Butcher</a> (+25 exp)

 


**a skeleton despawns.**

**This NPC *should* return incorrect items given.**

end