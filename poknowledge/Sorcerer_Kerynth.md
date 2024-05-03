# Sorcerer Kerynth



## Dialog

**You say:** `Hail`



if(e.other:Race() == "Dark Elf" or e.other:Race() == "Iksar" or e.other:Race() == "Troll" or e.other:Race() == "Ogre" or e.other:Class() == "Shadowknight" or e.other:Class() == "Necromancer") then



e.self:DoAnim(60)



e.self:Emote("inhales sharply in a very stern study of the dark one before him. 'You travel lightly, I see. Perhaps you are merely lost and my reaction is one of preconceived notions. In any event, the district of Kartis is not too distant a travel from where you stand now and I'm certain that your own kind would be more than helpful in accommodating your immediate needs while within this fair city. If for one reason or another you are here by intent, then we reluctantly welcome you upon the condition that you uphold our ways of neutrality 


else



e.self:DoAnim(48);



e.self:Emote("gives a deep nod of his head in formal and polite recognition of Soandso before him. 'Greetings, traveler, and welcome to the district of Tanaan. In light of your presence among us, we have gathered our knowledge and memories of lives past upon Norrath in hopes that our experiences would benefit you in the present. Do not hesitate to approach all citizens of this district, for we are equally fair and willing to grant you the aid that is within our individual power to provide. In my own personal experience upon Norrath, I was a wizard of some power 

end



## Turn-Ins



local count =  **You turn in:**  { <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1121.png" alt="" /> <a
                                href="/item/1225" data-url="1225" class="tooltip-link link">Carmine Turban</a>,  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_931.png" alt="" /> <a
                                href="/item/1226" data-url="1226" class="tooltip-link link">Carmine Robe</a>,  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_634.png" alt="" /> <a
                                href="/item/1227" data-url="1227" class="tooltip-link link">Carmine Sleeves</a>,  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1044.png" alt="" /> <a
                                href="/item/1228" data-url="1228" class="tooltip-link link">Carmine Trinket</a>,  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_636.png" alt="" /> <a
                                href="/item/1229" data-url="1229" class="tooltip-link link">Carmine Gloves</a>,  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_635.png" alt="" /> <a
                                href="/item/1230" data-url="1230" class="tooltip-link link">Carmine Pants</a>,  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_633.png" alt="" /> <a
                                href="/item/1231" data-url="1231" class="tooltip-link link">Carmine Boots</a>}

if(count > 0) then


repeat



>**Sorcerer Kerynth says:** Thank you, Soandso.



 &#127873; **You receive:** eq.ChooseRandom( <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_957.png" alt="" /> <a
                                href="/item/10028" data-url="10028" class="tooltip-link link">Peridot</a>,  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_966.png" alt="" /> <a
                                href="/item/10037" data-url="10037" class="tooltip-link link">Diamond</a>,  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_966.png" alt="" /> <a
                                href="/item/22503" data-url="22503" class="tooltip-link link">Blue Diamond</a>,  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_966.png" alt="" /> <a
                                href="/item/15981" data-url="15981" class="tooltip-link link">Raw Diamond</a>) (+300000 exp)

 



count = count - 1;


until count == 0;

**This NPC *should* return incorrect items given.**
