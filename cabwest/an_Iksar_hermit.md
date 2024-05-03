# an Iksar hermit


## Dialog

**You say:** `hail`



>*an Iksar hermit looks at you with one good eye.  His left eye is covered with pus.  'I seek a [great sorcerer].*

**You say:** `great sorcerer`



if **Faction** >= Amiable +200 then



>*an Iksar hermit hands you a flaxen hilt or handle of sorts. It has four round slots on one 'Insert within what used to be. Return it to me when all is complete. With it shall you gain your Sorcerer's Skullcap. Go and prove your knowledge.*



 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1140.png" alt="" /> <a
                                href="/item/17195" data-url="17195" class="tooltip-link link">A Flaxen Hilt</a>


else



>**an Iksar hermit says:** Greatness comes from many deeds.  You have more work to do.

end



## Turn-Ins



local text = "All is not complete. A cap and the rest, which was asked for, is required.";



if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_596.png" alt="" /> <a
                                href="/item/12886" data-url="12886" class="tooltip-link link">Barbed Scaled Whip</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1070.png" alt="" /> <a
                                href="/item/4266" data-url="4266" class="tooltip-link link">Sorcerer Skullcap</a>) then


>*an Iksar hermit takes the flail and vanishes with a brilliant flash!! Within your hands appears a skullcap. You hear a voice echo through the cave. Well done. You are a formidable necromancer. We thank you.*


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1070.png" alt="" /> <a
                                href="/item/4267" data-url="4267" class="tooltip-link link">Necromancer Skullcap</a> (+10000 exp)

 


Your faction standing with [Brood of Kotiz](/faction/443) got better (<span class='text-success'>+15</span>)


Your faction standing with [Legion of Cabilis](/faction/441) got better (<span class='text-success'>+5</span>)


**an Iksar hermit despawns.**

**This NPC *should* return incorrect items given.**
 