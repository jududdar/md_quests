# Vilissia



[Vilissia](/npc/80014) is a level 35 Human Wizard that spawns in [Temple of Solusek Ro](/zone/80).



## Dialog

if **Faction** >= Indifferent then



**You say:** `hail`




>**Vilissia says:** I am Vilissia, chosen of Solusek Ro.  I am a practitioner in the wizardly arts, and keeper of lore for the [runescale cloak], [Tishan's kilt] and the [acumen mask].


**You say:** `runescale cloak`




>**Vilissia says:** The Runescale cloak is a wonderful item of defense for any wizard.  Are you [interested] in the [cloak]?


**You say:** `interested.* cloak`




>**Vilissia says:** I can assemble for you a runescale cloak, but I will need you to bring me the necessary components.  I will need a lizardscale cloak from the temple of Cazic-Thule and the three Runes of Scale.  All three can be found on crocodiles - saltwater crocodiles in the caverns of Guk, deepwater crocodiles in the Oasis of Marr and firescale crocodiles in the mountains of Lavastorm.  Bring me these items, and I will make you a runescale cloak.


**You say:** `acumen mask`




>**Vilissia says:** The acumen mask, as its name suggests, confers to its wearer certain powers of insight and knowledge.  Are you [interested] in obtaining a [mask]?


**You say:** `interested.* mask`




>**Vilissia says:** I can make an acumen mask for you, but you will need to bring me the proper components.  I will need a glowing mask from a skeletal monk in the caverns of Guk, a patch of Shadow from our mortal enemies, the shadowed men, a darkbone Skull from a darkbone skeleton in the Estate of Unrest, and a bonechipped mask from a goblin headmaster in the Ocean of Tears.  Bring me these four items, and I will make for you an acumen mask.


**You say:** `tishan.* kilt`




>**Vilissia says:** Tishan was once counted among the mightiest of wizards, and his items are items of power.  If you are interested in acquiring Tishan's kilt, you must take a shadowed ball from our mortal enemies, the shadowed men, and bring it to Trankia in the Everfrost Mountains.


else


**Vilissia says one of the following:**

>I didn't know Slime could speak common.  Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here?  Now go away!

>I wonder how much I could get for the tongue of a blithering fool?  Leave before I decide to find out for myself.

>Oh look..a talking lump of refuse..how novel!
end



## Turn-Ins



local text = "Solusek Ro does not believe in half measures.";


if **Faction** >= Indifferent and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_771.png" alt="" /> <a
                                href="/item/2352" data-url="2352" class="tooltip-link link">Glowing Mask</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_528.png" alt="" /> <a
                                href="/item/2367" data-url="2367" class="tooltip-link link">Bonechipped Mask</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_595.png" alt="" /> <a
                                href="/item/2368" data-url="2368" class="tooltip-link link">Patch of Shadow</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1070.png" alt="" /> <a
                                href="/item/10558" data-url="10558" class="tooltip-link link">Darkbone Skull</a>) then


>**Vilissia says:** Mask, patch, skull and mask. All of the items necessary for me to make an acumen mask.  Excellent.  All praise Solusek Ro!


Your faction standing with [Temple of Solusek Ro](/faction/415) got better (<span class='text-success'>+10</span>)


Your faction standing with [Shadowed Men](/faction/416) got worse (<span class='text-danger'>-1</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1063.png" alt="" /> <a
                                href="/item/2366" data-url="2366" class="tooltip-link link">Acumen Mask</a> (+1000 exp)

 

elseif **Faction** >= Indifferent and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_945.png" alt="" /> <a
                                href="/item/10000" data-url="10000" class="tooltip-link link">Lambent Stone</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_964.png" alt="" /> <a
                                href="/item/10035" data-url="10035" class="tooltip-link link">Ruby</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_964.png" alt="" /> <a
                                href="/item/10035" data-url="10035" class="tooltip-link link">Ruby</a>) then 


e.other:Say("Here is your prize - a lambent ruby.");


Your faction standing with [Temple of Solusek Ro](/faction/415) got better (<span class='text-success'>+1</span>)


Your faction standing with [Shadowed Men](/faction/416) got worse (<span class='text-danger'>-1</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_964.png" alt="" /> <a
                                href="/item/10118" data-url="10118" class="tooltip-link link">Lambent Ruby</a> (+1000 exp)

 

elseif **Faction** >= Indifferent and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_841.png" alt="" /> <a
                                href="/item/2332" data-url="2332" class="tooltip-link link">Lizardscale Cloak</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_967.png" alt="" /> <a
                                href="/item/10553" data-url="10553" class="tooltip-link link">Rune of Scale</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_967.png" alt="" /> <a
                                href="/item/10554" data-url="10554" class="tooltip-link link">Rune of Scale</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_967.png" alt="" /> <a
                                href="/item/10555" data-url="10555" class="tooltip-link link">Rune of Scale</a>) then 


e.other:Say("You impress me, adventurer! I had not expected you to return with all of the runes. Very well, I shall keep my half of the bargain. Here is your Runescale Cloak.");


Your faction standing with [Temple of Solusek Ro](/faction/415) got better (<span class='text-success'>+10</span>)


Your faction standing with [Shadowed Men](/faction/416) got worse (<span class='text-danger'>-1</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_663.png" alt="" /> <a
                                href="/item/2364" data-url="2364" class="tooltip-link link">Runescale Cloak</a> (+1000 exp)

 

elseif **Faction** >= Indifferent and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1092.png" alt="" /> <a
                                href="/item/16507" data-url="16507" class="tooltip-link link">Enchanted Platinum Bar</a>) then 


e.other:Say("I see that Gavel has sent you to me.  Very well, I have vulcanized your platinum bar - take it.");


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1135.png" alt="" /> <a
                                href="/item/19048" data-url="19048" class="tooltip-link link">Vulcanized Platinum Bar</a> (+1000 exp)

 


**This NPC *should* return incorrect items given.**
