# Datur Nightseer



[Datur Nightseer](/npc/67029) is a level 61 Dwarf GM Paladin that spawns in [North Kaladim](/zone/67).



## Dialog

**You say:** `hail`



>**Datur Nightseer says:** Welcome to our temple. We are the paladins of the Church of Underfoot. I am lord of our holy order. I call upon you to assist us in the defense of Kaladim. Speak with the master paladins or priests and find ways to prove your allegiance to Brell.

**You say:** `honored member`



if **Faction** >= Indifferent +50 then



>**Datur Nightseer says:** Yes.  The light of righteousness shines from within you.


elseif **Faction** >= Indifferent then



>**Datur Nightseer says:** The Clerics of Underfoot have yet to see your faith directed towards our wills.  Perhaps you should assist Master Gunlok Jure in the crusade against the undead.


else



>**Datur Nightseer says:** How dare you approach a member of the Clerics of Underfoot?!  Dogs such as you lie in the same bed as aviaks and ogres!

end



## Turn-Ins



if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/18768" data-url="18768" class="tooltip-link link">Folded Parchment</a>) then


>**Datur Nightseer says:** Welcome, we are the Paladins of the Underfoot. I am Datur, and I will help teach you the word and will of the Duke of Below, Brell Serilis. Here is our guild tunic. Let's get started, shall we?


Your faction standing with [Clerics of Underfoot](/faction/227) got better (<span class='text-success'>+100</span>)


Your faction standing with [Kazon Stormhammer](/faction/274) got better (<span class='text-success'>+100</span>)


Your faction standing with [Miners Guild 249](/faction/293) got better (<span class='text-success'>+75</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_678.png" alt="" /> <a
                                href="/item/13514" data-url="13514" class="tooltip-link link">Dusty Tunic*</a> (+20 exp)

 

elseif(( **Faction is** > Indifferent) and ( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_609.png" alt="" /> <a
                                href="/item/12279" data-url="12279" class="tooltip-link link">Chalice Case</a>)) then


>**Datur Nightseer says:** The chalice is returned!! Praise be to Brell!! You have proven yourself to our church and have earned our respect. Let me welcome you into our brotherhood with the Cape of Underfoot. Wear it with pride as all of our finest paladins do.





Your faction standing with [Clerics of Underfoot](/faction/227) got better (<span class='text-success'>+15</span>)


Your faction standing with [Kazon Stormhammer](/faction/274) got better (<span class='text-success'>+15</span>)


Your faction standing with [Miners Guild 249](/faction/293) got better (<span class='text-success'>+11</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_658.png" alt="" /> <a
                                href="/item/12281" data-url="12281" class="tooltip-link link">Cape of Underfoot</a> (+2500 exp)

**You receive coin:** 1-5 <img src='/static/icons/item_644.png' width='14' height='14'/> 0 <img src='/static/icons/item_645.png' width='14' height='14'/> 0 <img src='/static/icons/item_646.png' width='14' height='14'/> 0 <img src='/static/icons/item_647.png' width='14' height='14'/> 

**This NPC *should* return incorrect items given.**
