# Kandin Firepot



[Kandin Firepot](/npc/68109) is a level 54 Gnome Magician that spawns in [Butcherblock Mountains](/zone/68).



## Dialog

**You say:** `hail`



>**Kandin Firepot says:** Hello, there! Don't have time to talk. I'm workin', workin', workin'! Careful! Don't slip in the oil!

**You say:** `what oil`



if **Faction** >= Apprehensive +40 then



>**Kandin Firepot says:** Ah the oil! I recently sent a specially crafted golem to explore through a huge portal to another plane. It's instructions were to collect special oil that I suspect existed in the plane. What I think is the golem broke down. This looks like a good task for one like you. Go see what's wrong with the golem. Here is spare gears of mine incase it's broken. Be careful though, if you put it in wrong it could explode or worse!



 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_731.png" alt="" /> <a
                                href="/item/14319" data-url="14319" class="tooltip-link link">Golem Sprocket</a>


else



**Kandin Firepot says one of the following:**

>I didn't know Slime could speak common.  Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here?  Now go away!

>I wonder how much I could get for the tongue of a blithering fool?  Leave before I decide to find out for myself.

>Oh look..a talking lump of refuse..how novel!

end



## Turn-Ins





if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/18169" data-url="18169" class="tooltip-link link">Note from Arantir</a>) then


>**Kandin Firepot says:** Brother! I have one of those. He's great, but he's dead. His name was Gabstik and he was a really powerful wizard. I still have one of his greatest possesions! You look like you could use it. I've added another thing to my shopping list. I require a dry brittle skin that I can mold or a rare oil found in the planes that I can soak the fuse in. Get me one of these things and I'll trade it for my bother's stick.


Your faction standing with [Truespirit](/faction/404) got better (<span class='text-success'>+10</span>)

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_697.png" alt="" /> <a
                                href="/item/14349" data-url="14349" class="tooltip-link link">Green Oil</a>) then


if **Faction** >= Apprehensive +40 then



>**Kandin Firepot says:** Oh wow! You found the oil! Where is the golem? You didn't hurt him did you? I am very fond of him. Anyways, here is your reward a note and staff to give to that guy you were asking me about.



Your faction standing with [Truespirit](/faction/404) got better (<span class='text-success'>+10</span>)



 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_887.png" alt="" /> <a
                                href="/item/14339" data-url="14339" class="tooltip-link link">Staff of Gabstik</a> 

 



 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/18168" data-url="18168" class="tooltip-link link">Note to Arantir</a> 

 


else



>**Kandin Firepot says:** I have no need for this item Soandso. You can have it back.



 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_697.png" alt="" /> <a
                                href="/item/14349" data-url="14349" class="tooltip-link link">Green Oil</a> 

 


**This NPC *should* return incorrect items given.**





