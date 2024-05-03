# Miranda


## Dialog

**You say:** `hail`



if **Faction** >= Dubious +300 then



>**Miranda says:** I'm not supposed to talk to strangers but if my parents let you in here I guess it's ok. Do you like [candy]? I could give you some candy to play a game with me but my [dice] are gone now.


else



>**Miranda says:** You have done much to anger the spirits thus you are not accepted by our people.


**You say:** `candy`



if **Faction** >= Dubious +300 then



>**Miranda says:** Khonza Ayssla went away one time and came back with chocolate covered cherries and pixie powder cinnesticks for my sister and I. I like the chocolates the best.


else



>**Miranda says:** You have done much to anger the spirits thus you are not accepted by our people.


**You say:** `dice`



if **Faction** >= Dubious +300 then



>**Miranda says:** I had my dice in a little bag and lost it outside the walls of the village. I think the kobolds must have found it.


else



>**Miranda says:** You have done much to anger the spirits thus you are not accepted by our people.

end



## Turn-Ins





if **Faction** >= Dubious +300 and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_911.png" alt="" /> <a
                                href="/item/19992" data-url="19992" class="tooltip-link link">Chocolate Marr Cherries</a>) then


>*Miranda claps her hands with excitement 'Chocolate cherries! My favorite! Here try some of this!'*


Your faction standing with [Kejek Village](/faction/5011) got better (<span class='text-success'>+1</span>)


Your faction standing with [Peace Keepers](/faction/298) got better (<span class='text-success'>+1</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1145.png" alt="" /> <a
                                href="/item/20115" data-url="20115" class="tooltip-link link">Pouch of Kejek Catnip</a> (+1000 exp)

 

elseif **Faction** >= Dubious +300 and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_539.png" alt="" /> <a
                                href="/item/2088" data-url="2088" class="tooltip-link link">Tiny Pouch of Bone Dice</a>) then


>**Miranda says:** You found my dice!!! Thank you Soandso!!


Your faction standing with [Kejek Village](/faction/5011) got better (<span class='text-success'>+2</span>)


Your faction standing with [Peace Keepers](/faction/298) got better (<span class='text-success'>+1</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1140.png" alt="" /> <a
                                href="/item/20116" data-url="20116" class="tooltip-link link">Ball of Burlap Yarn</a> (+1000 exp)

 


**This NPC *should* return incorrect items given.**
