# Yeolarn Bronzeleaf



[Yeolarn Bronzeleaf](/npc/61025) is a level 61 High Elf GM Cleric that spawns in [Northern Felwithe](/zone/61).



## Dialog

**You say:** `hail`



if **Faction** >= Indifferent then




>**Yeolarn Bronzeleaf says:** Hail, Soandso! We of Tunare are charged with protecting the Great Mother from the forces of Innoruuk. Even now, the evil minions of this foul deity are despoiling our great forest. Will you help us [protect the Mother]?


else



>**Yeolarn Bronzeleaf says:** One such as yourself has nothing to offer the Clerics of Tunare. Remove yourself from this sacred temple!


**You say:** `protect`



if **Faction** >= Indifferent then



>**Yeolarn Bronzeleaf says:** Just outside the gates of Felwithe, the forces of Innoruuk gather in the guise of decaying skeletons. Bring me four sets of bone chips as proof of your vigilance. I assure you, your faith shall not go unrewarded.


else



>**Yeolarn Bronzeleaf says:** One such as yourself has nothing to offer the Clerics of Tunare. Remove yourself from this sacred temple!


**You say:** `initiate of tunare`



>**Yeolarn Bronzeleaf says:** The Teir'Dal behind the undead plague in our forest have discovered a means of creating a terrible undead called a Ghast. These Ghasts have been sighted in the Lesser Faydark and must be destroyed. Bring me four of the vile creatures hearts.

**You say:** `slay the necromancer`



>**Yeolarn Bronzeleaf says:** The Fier'Dal rangers that inhabit the Lesser Faydark have spotted a courier making deliveries to the Teir'Dal camp near Castle Mistmoore and to a necromancer that lingers near the ancient obelisk. We believe that the crates he carries are supplies needed for the creation of more Ghasts. Another shipment should be arriving soon. Seek out the necromancer at the obelisk and take his head then take the head of the courier and return them to me with the crate that the courier carries and your Initiate Symbol of Tunare.

**You say:** `warden of tunare`



>**Yeolarn Bronzeleaf says:** The crate that the you recovered from the Courier contained this black candlestick that radiates an aura of great magical power. I request that you deliver the candlestick to Lady Trilani who is studying with the High Men in Erudin. Perhaps she can divine the nature of the candlestick and offer aid in defeating its power. The remaining contents of the crate have been given to Crusader Swiftmoon to be delivered to a gnome in steamfont that is purchasing them on behalf of the Eldrich Collective. When you return be sure to present your Disciple Symbol to me with anything that Trilani may ask you to deliver.


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1128.png" alt="" /> <a
                                href="/item/1598" data-url="1598" class="tooltip-link link">Black Stone Candlestick</a>
end



## Turn-Ins



local text1 = "I requested four Ghast hearts!";


if **Faction** >= Indifferent and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_804.png" alt="" /> <a
                                href="/item/13073" data-url="13073" class="tooltip-link link">Bone Chips</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_804.png" alt="" /> <a
                                href="/item/13073" data-url="13073" class="tooltip-link link">Bone Chips</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_804.png" alt="" /> <a
                                href="/item/13073" data-url="13073" class="tooltip-link link">Bone Chips</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_804.png" alt="" /> <a
                                href="/item/13073" data-url="13073" class="tooltip-link link">Bone Chips</a>) then 


>**Yeolarn Bronzeleaf says:** Praise Tunare! I knew you would be victorious. I reward you with this spell, and pray that it will help you in your fight against the unholy forces of Innoruuk. When you are ready you will make a fine [Initiate of Tunare].


Your faction standing with [Clerics of Tunare](/faction/226) got better (<span class='text-success'>+2</span>)


Your faction standing with [King Tearis Thex](/faction/279) got better (<span class='text-success'>+2</span>)


Your faction standing with [Anti-mage](/faction/5002) got better (<span class='text-success'>+1</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/15014" data-url="15014" class="tooltip-link link">Spell: Strike</a> (+4400 exp)

 

elseif **Faction** >= Indifferent and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1003.png" alt="" /> <a
                                href="/item/10199" data-url="10199" class="tooltip-link link">Putrescent Heart</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1003.png" alt="" /> <a
                                href="/item/10199" data-url="10199" class="tooltip-link link">Putrescent Heart</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1003.png" alt="" /> <a
                                href="/item/10199" data-url="10199" class="tooltip-link link">Putrescent Heart</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1003.png" alt="" /> <a
                                href="/item/10199" data-url="10199" class="tooltip-link link">Putrescent Heart</a>) then 


>**Yeolarn Bronzeleaf says:** Praise Tunare!! You have done well young Initiate. Here the symbol of your station within our faith. Return to me when you are ready to [slay the necromancer] that has been creating the undead.


Your faction standing with [Clerics of Tunare](/faction/226) got better (<span class='text-success'>+15</span>)


Your faction standing with [King Tearis Thex](/faction/279) got better (<span class='text-success'>+15</span>)


Your faction standing with [Anti-mage](/faction/5002) got better (<span class='text-success'>+11</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_852.png" alt="" /> <a
                                href="/item/1570" data-url="1570" class="tooltip-link link">Initiate Symbol of Tunare</a> (+3250 exp)

 

elseif **Faction** >= Indifferent and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_852.png" alt="" /> <a
                                href="/item/1570" data-url="1570" class="tooltip-link link">Initiate Symbol of Tunare</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_852.png" alt="" /> <a
                                href="/item/1571" data-url="1571" class="tooltip-link link">Disciple Symbol of Tunare</a> (+4000 exp)

 

elseif **Faction** >= Indifferent and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_852.png" alt="" /> <a
                                href="/item/1571" data-url="1571" class="tooltip-link link">Disciple Symbol of Tunare</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_582.png" alt="" /> <a
                                href="/item/1599" data-url="1599" class="tooltip-link link">Powder of Unanimation</a>) then 


>**Yeolarn Bronzeleaf says:** Praise Tunare!! I will have our sorcerers examine this power immediately to see if we can reproduce it in quantities enough to eliminate the undead plague. I award you the rank of Warden of Tunare, the All Mother smiles upon you, Soandso!


Your faction standing with [Clerics of Tunare](/faction/226) got better (<span class='text-success'>+40</span>)


Your faction standing with [King Tearis Thex](/faction/279) got better (<span class='text-success'>+40</span>)


Your faction standing with [Anti-mage](/faction/5002) got better (<span class='text-success'>+30</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_852.png" alt="" /> <a
                                href="/item/1572" data-url="1572" class="tooltip-link link">Warden Symbol of Tunare</a> (+5000 exp)

 

elseif **Faction** >= Indifferent and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/18780" data-url="18780" class="tooltip-link link">A tattered note</a>) then 


>**Yeolarn Bronzeleaf says:** Welcome, friend, to the Clerics of Tunare. I am Yeolarn Bronzeleaf, head of the guild and devout follower of Tunare. Here is your guild tunic - it will help to protect you against this world's evils.


Your faction standing with [Clerics of Tunare](/faction/226) got better (<span class='text-success'>+100</span>)


Your faction standing with [King Tearis Thex](/faction/279) got better (<span class='text-success'>+100</span>)


Your faction standing with [Anti-mage](/faction/5002) got better (<span class='text-success'>+75</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_678.png" alt="" /> <a
                                href="/item/13590" data-url="13590" class="tooltip-link link">Faded Gold Training Tunic*</a> (+20 exp)

 

else


>**Yeolarn Bronzeleaf says:** Your faith has not grown strong enough to undertake that task young one.

**This NPC *should* return incorrect items given.**
;

