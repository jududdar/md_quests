# Master Xydoz


## Dialog

**You say:** `hail`



if **Faction** >= Amiable then



>**Master Xydoz says:** What is it you seek within the tower? Could it be that you are a new apprentice? If so, you are required to don the [apprentice skullcap]


elseif **Faction** >= Indifferent then



>**Master Xydoz says:** When you have shown more devotion to the Brood of Kotiz, we can discuss such things.


else



>**Master Xydoz says:** You are a true simpleton to think you can speak to me.  You are no ally to the Brood of Kotiz.  Begone, before I make your blood boil!


**You say:** `apprentice`



>**Master Xydoz says:** All new members of the Brood of Kotiz are required to don the [apprentice skullcap]. To earn one, a new apprentice is required to fetch four brains for further experiments. Not just any four brains, mind you, but the brains of [sarnak] hatchlings.

**You say:** `sarnak`



>**Master Xydoz says:** Sarnak ? Do not speak loudly, that name. If you seek information on the sarnak, read the tome of this tower. The tower librarian should be found within.

**You say:** `second rank skullcap`



>**Master Xydoz says:** Looking for the second rank skullcap ? Look no further, but be prepared to earn it. I seek a [faded tapestry]. Now, too, so do you.

**You say:** `faded tapestry`



>**Master Xydoz says:** I have heard reports of such a thing found upon Sarnak hatchlings. They must have scampered from the safety of their dwelling with their master's property. I would like to see this tapestry, but only when it has been mended. I need find a necromancer who is [adept at tailoring].

**You say:** `kor sha`



>**Master Xydoz says:** Do not become like the herbalist, Jondin.  He has many questions concerning Kor - Sha.  It is recorded in the tower tomes.  It was a laboratory of a once great Iksar.  It turned to rubble long ago.

**You say:** `adept at tailoring`



if **Faction** >= Amiable then



>**Master Xydoz says:** If you are a member of the Brood and wish to assist you may seek out this tapestry. Find the Torn and Ripped pieces and take them both to a sewing kit. Return with the mended tapestry and your first rank skullcap and I shall see that you are rewarded with coin and a second rank skullcap


elseif **Faction** >= Indifferent then



>**Master Xydoz says:** When you have shown more devotion to the Brood of Kotiz, we can discuss such things.


else



>**Master Xydoz says:** You are a true simpleton to think you can speak to me.  You are no ally to the Brood of Kotiz.  Begone, before I make your blood boil!

end





## Turn-Ins



local text1 = "I must have the mended tapestry and your first circle apprentice cap before I reward you."

local text2 = "Do not bother me unless you have all that I asked for, grunt. Two star rubies AND the book! Now get OUT of here!";

local text3 = "I will require four sarnak whelp brains for my experiment. When I have them, then you shall have the skullcap of the apprentice, first circle.";



if **Faction** >= Amiable and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1204.png" alt="" /> <a
                                href="/item/12408" data-url="12408" class="tooltip-link link">Sarnak Hatchling Brain</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1204.png" alt="" /> <a
                                href="/item/12408" data-url="12408" class="tooltip-link link">Sarnak Hatchling Brain</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1204.png" alt="" /> <a
                                href="/item/12408" data-url="12408" class="tooltip-link link">Sarnak Hatchling Brain</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1204.png" alt="" /> <a
                                href="/item/12408" data-url="12408" class="tooltip-link link">Sarnak Hatchling Brain</a>) then


>**Master Xydoz says:** Good work, my young apprentice. You will make a fine addition to our ranks. Here is your first apprentice skullcap. Wear it as a sign of our circle. Do not lose it. Someday you shall wear a necromancer skullcap, but next shall come the [second rank skullcap].


Your faction standing with [Brood of Kotiz](/faction/443) got better (<span class='text-success'>+2</span>)


Your faction standing with [Legion of Cabilis](/faction/441) got better (<span class='text-success'>+1</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1070.png" alt="" /> <a
                                href="/item/4260" data-url="4260" class="tooltip-link link">Apprentice Skullcap - 1st Rank</a> (+100 exp)

 

elseif **Faction** >= Amiable and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_648.png" alt="" /> <a
                                href="/item/18208" data-url="18208" class="tooltip-link link">Mended Tapestry</a>) then


>**Master Xydoz says:** A job well done, apprentice Soandso. Your fine service shall earn you the second circle apprentice skullcap. I would advise you to forget this tapestry, it is nothing more than an ancient rug of no importance.


Your faction standing with [Brood of Kotiz](/faction/443) got better (<span class='text-success'>+10</span>)


Your faction standing with [Legion of Cabilis](/faction/441) got better (<span class='text-success'>+2</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1070.png" alt="" /> <a
                                href="/item/4261" data-url="4261" class="tooltip-link link">Apprentice Skullcap - 2nd Rank</a> (+120 exp)

 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_777.png" alt="" /> <a
                                href="/item/14811" data-url="14811" class="tooltip-link link">Iron Bound Tome</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_961.png" alt="" /> <a
                                href="/item/10032" data-url="10032" class="tooltip-link link">Star Ruby</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_961.png" alt="" /> <a
                                href="/item/10032" data-url="10032" class="tooltip-link link">Star Ruby</a>) then


>**Master Xydoz says:** Well done


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_863.png" alt="" /> <a
                                href="/item/14831" data-url="14831" class="tooltip-link link">Glosk's Reference: Greaves</a> (+10000 exp)

 

**This NPC *should* return incorrect items given.**
