# Dyth X-Teria





## Dialog

**You say:** `Hail`



>*Dyth X-Teria appears to be the local master of wizardry. His garb clearly comes from the dark city of Neriak as it bears a black sun emblem.*


>**Dyth X-Teria says:** Speak!! I am dispatched from Neriak to this land by order of the king. I shall research [new spells] and aid the adventuring wizards. My knowledge of wizardry is offered to all in hopes of gaining information about Kunark.

**You say:** `new spells`



>**Dyth X-Teria says:** Within this lost land could lie the knowledge of extinct civilizations. I am ordered to seek out this knowledge for the empire of Neriak. So far, all I have discovered is a way to create a spell of my own design. I call it [Brain Bite].

**You say:** `brain bite`



>**Dyth X-Teria says:** If you wish to own a copy of MY spell, Brain Bite, I would be glad to give you one. All I ask is that you [gather a few souls] for me.

**You say:** `gather a few souls`



>*Dyth X-Teria reveals three ornate bottles.*


>**Dyth X-Teria says:** While I finished my research on Brain Bite, I encountered three [interlopers] who wished to steal my spell. I had the dragoon garrison track them down and dispatch them. Unfortunately, I forgot to instruct them to trap their souls with these bottles. Do you want to [take the bottles] and finish the job?

**You say:** `interlopers`



>**Dyth X-Teria says:** The garrison report was sloppy, to say the least. They informed me that Hampton was slain near some ruins within a jungle infested by raptors. Mardon was slain in an ancient city found deep in a jungle. Ryla was killed in a hidden fortress guarded by fierce armored wolves who walked on their hind legs.

**You say:** `take the bottles`



>**Dyth X-Teria says:** The bottles also require a gem. You will fetch me the three gems and I will prepare the bottles and give them to you to finish the job. I need an onyx, a peridot and a star rose quartz.
end



## Turn-Ins



local text = "Only three souls will get you my knowledge, wizard.";



if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_956.png" alt="" /> <a
                                href="/item/10027" data-url="10027" class="tooltip-link link">Onyx</a>) then


>**Dyth X-Teria says:** Identify this when the time comes. It is Ryla's prison.


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1006.png" alt="" /> <a
                                href="/item/12964" data-url="12964" class="tooltip-link link">an Ornate Bottle</a> (+0 exp)

 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_957.png" alt="" /> <a
                                href="/item/10028" data-url="10028" class="tooltip-link link">Peridot</a>) then


>**Dyth X-Teria says:** This bottle is for the one called Hampton. If you look well, you can see his name.


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1006.png" alt="" /> <a
                                href="/item/12962" data-url="12962" class="tooltip-link link">an Ornate Bottle</a> (+0 exp)

 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_950.png" alt="" /> <a
                                href="/item/10021" data-url="10021" class="tooltip-link link">Star Rose Quartz</a>) then



>**Dyth X-Teria says:** This bottle is for Mardon. You may be able to identify his name upon it.


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1006.png" alt="" /> <a
                                href="/item/12963" data-url="12963" class="tooltip-link link">an Ornate Bottle</a> (+0 exp)

 


elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1006.png" alt="" /> <a
                                href="/item/12965" data-url="12965" class="tooltip-link link">bottle of swirling smoke</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1006.png" alt="" /> <a
                                href="/item/12966" data-url="12966" class="tooltip-link link">bottle of swirling smoke</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1006.png" alt="" /> <a
                                href="/item/12967" data-url="12967" class="tooltip-link link">bottle of swirling smoke</a>) then


>*Dyth X-Teria empties the bottle's smoke into a very large glass urn filled with similar swirling smoke. You think you hear the cries of a thousand tortured souls. He then closes the urn and hands you a scroll. 'Here is your reward. It will blast a foe's brain and hopefully, they may forget their hatred.*


Your faction standing with [Venril Sathir](/faction/318) got better (<span class='text-success'>+30</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/12968" data-url="12968" class="tooltip-link link">Scroll of Brain Bite</a> (+3322176 exp)

 

**This NPC *should* return incorrect items given.**





