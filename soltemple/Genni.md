# Genni



[Genni](/npc/80024) is a level 34 Erudite Wizard that spawns in [Temple of Solusek Ro](/zone/80).





## Dialog

if **Faction** >= Indifferent then



**You say:** `hail`




>**Genni says:** I am Genni of the temple of Solusek Ro. I serve as custodian of the [lambent stones].


**You say:** `lambent stones`




>**Genni says:** Lambent stones are receptacles of power. Alone they are not useful, but when combined with other gemstones they can be used for making magic items. I know of [star ruby] lambent, [ruby] lambent, [sapphire] lambent and [fire opal] lambent.


**You say:** `what.* star ruby`




>**Genni says:** To make a star ruby lambent stone, you must give me two star rubies and a lambent stone. Lambent stones can be found on hill giants, sand giants and griffons.




**You say:** `what ruby`




>**Genni says:** My Sister Vilissia holds the secrets to making ruby lambent stones. Though she will not speak of it, if you give her two rubies and a lambent stone, she will make you ruby lambent.


**You say:** `what.* sapphire`




>**Genni says:** My Brother Gardern holds the secret to making sapphire lambent stones. Though he will not speak of it, if you give him two sapphires and a lambent stone, he will make you sapphire lambent.


**You say:** `what.* fire opal`




>**Genni says:** My Brother Ostorm holds the secret to making fire opal lambent stones. Though he will not speak of it, if you give him two fire opals and a lambent stone, he will make you fire opal lambent. If you are interested, I can [sell] you a [fire opal].


**You say:** `sell`




>**Genni says:** I will sell you a fire opal for 550 golden coins. Remember, gold! The metal of fire for a gem of fire.


else


**Genni says one of the following:**

>I didn't know Slime could speak common.  Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here?  Now go away!

>I wonder how much I could get for the tongue of a blithering fool?  Leave before I decide to find out for myself.

>Oh look..a talking lump of refuse..how novel!
end



## Turn-Ins



local text = "Solusek Ro does not believe in half measures.";



if **Faction** >= Indifferent and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_961.png" alt="" /> <a
                                href="/item/10032" data-url="10032" class="tooltip-link link">Star Ruby</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_961.png" alt="" /> <a
                                href="/item/10032" data-url="10032" class="tooltip-link link">Star Ruby</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_945.png" alt="" /> <a
                                href="/item/10000" data-url="10000" class="tooltip-link link">Lambent Stone</a>) then


>**Genni says:** Here is your prize - a lambent star ruby.


Your faction standing with [Temple of Solusek Ro](/faction/415) got better (<span class='text-success'>+1</span>)


Your faction standing with [Shadowed Men](/faction/416) got worse (<span class='text-danger'>-1</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_961.png" alt="" /> <a
                                href="/item/10117" data-url="10117" class="tooltip-link link">Lambent Star Ruby</a> 

 

elseif **Faction** >= Indifferent and  **You turn in:** gold = 550) then


Your faction standing with [Temple of Solusek Ro](/faction/415) got better (<span class='text-success'>+1</span>)


Your faction standing with [Shadowed Men](/faction/416) got worse (<span class='text-danger'>-1</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_960.png" alt="" /> <a
                                href="/item/10031" data-url="10031" class="tooltip-link link">Fire Opal</a> 

 

elseif **Faction** >= Indifferent and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1092.png" alt="" /> <a
                                href="/item/16507" data-url="16507" class="tooltip-link link">Enchanted Platinum Bar</a>) then


>**Genni says:** I see that Gavel has sent you to me. Very well, I have galvanized your platinum bar - take it.


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1138.png" alt="" /> <a
                                href="/item/19047" data-url="19047" class="tooltip-link link">Galvanized Platinum Bar</a> 

 

**This NPC *should* return incorrect items given.**





