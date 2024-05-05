# Brother Balatin



[Brother Balatin](/npc/86136) is a level 28 Skeleton Monk that spawns in [The Dreadlands](/zone/86).




## Dialog

**You say:** `hail`



>*Brother Balatin turns toward you. A transparent human face materializes upon the skull. As he speaks the smells of rotted rat corpses rushes into your face. You must fight the urge to vomit. 'What discipline do you [follow]?'*

**You say:** `lost circle`



>**Brother Balatin says:** Then we are one. The rebirth of our circle shall start with you. I have waited decades for your arrival. You should seek the living brothers within Tunaria. When you have earned your garb then you will be ready for the [true drape].

**You say:** `true drape`



>**Brother Balatin says:** Seek the broken flute of our master. Taken from us by the Iksar twins of Vistrei. To me they will come and to me your robe and you will come the dawning of the new brotherhood.
end



## Turn-Ins



local text = "May you have the correct items or lost forever will be all.";




if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_601.png" alt="" /> <a
                                href="/item/12979" data-url="12979" class="tooltip-link link">A Metal Pipe</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_601.png" alt="" /> <a
                                href="/item/12980" data-url="12980" class="tooltip-link link">A Metal Pipe</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_931.png" alt="" /> <a
                                href="/item/12256" data-url="12256" class="tooltip-link link">Robe of the Lost Circle</a>) then 


>*Brother Balatin holds his arms out and a fine robe materializes before your eyes. You grab it just in time to see the skeleton fade from existence.*


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_931.png" alt="" /> <a
                                href="/item/12970" data-url="12970" class="tooltip-link link">Robe of the Whistling Fists</a> 

 


elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_751.png" alt="" /> <a
                                href="/item/12429" data-url="12429" class="tooltip-link link">Ancient Thin Flute</a>) then


>*Brother Balatin quickly stashes the flute inside of his ribcage, where it joins another. 'If you want the true Flute of Zan-Fi, you'll have to take it from me!'* 


**Spawn NPC:**  [\#Brother Balatin](/npc/86004) at this location.


**Brother Balatin despawns.**

**This NPC *should* return incorrect items given.**






