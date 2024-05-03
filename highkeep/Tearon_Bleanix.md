# Tearon Bleanix


## Dialog

local fac = e.other:GetFaction(e.self);

local expansion_flag = eq.get_current_expansion();

**You say:** `hail`



>**Tearon Bleanix says:** Hello sir. Are you a citizen of Highpass?

**You say:** `I am not a citizen`



>**Tearon Bleanix says:** Nor am I. I find this city's love of greed appalling. Do not you?

**You say:** `appalling`



>**Tearon Bleanix says:** Yes. This city of vices is second only to Neriak. And it is trouble with Neriak that has sent me here, in search of my people's princess.

**You say:** `princess`



>**Tearon Bleanix says:** The Princess Lenya Thex is the daughter of His Royal Majesty, King Tearis Thex of Felwithe. She was on her way to Qeynos when we believe she was kidnapped by Carson McCabe, the governor of this vile city. I await the paladin from Felwithe.

**You say:** `all is not bright above the clouds`



if **Faction** >= Kindly then



>**Tearon Bleanix says:** Taken from this place she has been.  Seek the Highpass hussy.  Ask of her.  Only she knows where.  Find the Princess.  Give her this.  Show your allegiance.  This and her key. Then return the room key to me with the prize from the princess.  Become a hero!!



 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_516.png" alt="" /> <a
                                href="/item/13108" data-url="13108" class="tooltip-link link">Tearons Bracer</a>


elseif **Faction** >= Indifferent then



>**Tearon Bleanix says:** When you have furthered your service to the Paladins of Tunare, we shall make conversation.


else



>**Tearon Bleanix says:** You have some nerve to approach a loyal member of the Paladins of Tunare! Run, while you can!




**You say:** `become a hero`



if(fac < 4) then



>**Tearon Bleanix says:** Well let's get started on making you a hero. You must take the Elite Guard Bracer. Look for Princess Lenya. When you find her give her the bracer to prove you are with the Koada'dal. She should trust you then. Then return to me with Princess Lenya and return my bracer. Be safe my friend.



 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_516.png" alt="" /> <a
                                href="/item/13108" data-url="13108" class="tooltip-link link">Tearons Bracer</a>


else



>**Tearon Bleanix says:** When you have furthered your service to the Paladins of Tunare, we shall make conversation.

end



## Turn-Ins




if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1077.png" alt="" /> <a
                                href="/item/12267" data-url="12267" class="tooltip-link link">Highkeep Royal Suite</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1058.png" alt="" /> <a
                                href="/item/13109" data-url="13109" class="tooltip-link link">Royal Amulet of Thex</a>) then


>**Tearon Bleanix says:** Peace..  I can rest now.  You now hold my Silent Watch Shield.  Protect Felwithe..


Your faction standing with [Clerics of Tunare](/faction/226) got better (<span class='text-success'>+25</span>)


Your faction standing with [King Tearis Thex](/faction/279) got better (<span class='text-success'>+25</span>)


Your faction standing with [Anti-mage](/faction/5002) got better (<span class='text-success'>+18</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_542.png" alt="" /> <a
                                href="/item/9312" data-url="9312" class="tooltip-link link">Silent Watch Shield</a> (+0 exp)

 


**Tearon Bleanix despawns.**


if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_516.png" alt="" /> <a
                                href="/item/13112" data-url="13112" class="tooltip-link link">Tearon's Bracer</a>) then


>**Tearon Bleanix says:** King Tearis Thex thanks you my friend. Could you please hand the princess this amulet. It is hers. I pryed it from the hands of some beggar.


Your faction standing with [Clerics of Tunare](/faction/226) got better (<span class='text-success'>+25</span>)


Your faction standing with [King Tearis Thex](/faction/279) got better (<span class='text-success'>+25</span>)


Your faction standing with [Anti-mage](/faction/5002) got better (<span class='text-success'>+25</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1058.png" alt="" /> <a
                                href="/item/13109" data-url="13109" class="tooltip-link link">Royal Amulet of Thex</a> (+0 exp)

 


**Spawn NPC:**  [\#Princess Lenya](/npc/6573) at (**y:** 13.0, **x:** 52.0)

**This NPC *should* return incorrect items given.**
