# Guntrik



[Guntrik](/npc/49046) is a level 61 Ogre GM Warrior that spawns in [Oggok](/zone/49).



## Dialog

**You say:** `hail`



>**Guntrik says:** Mmmph!!  Who you?  Oh. you Soandso.  You supposed to be promising Craknek.  Me need you.  There bad things in swamp.  You want [help Crakneks] or you [want Guntrik bash your face]!!?

**You say:** `what crakneks`



>**Guntrik says:** Crakneks warriors!!  They be far back.  Through last caves.  They smash and bash.  They no like Greenbloods.  Bouncers keep thems from bashing.

**You say:** `bash`



>**Guntrik says:** OK!! Me bash!!  You hurt!!


**Guntrik attacks you.**

**You say:** `help crakneks`



if **Faction** >= Indifferent then




>**Guntrik says:** Go to swamps. Find noble hunters of humans and elves. All have house crests. Return to me and I give things. If you find special item says where hunters sleep, give to me. If meat founded then give to Clurg's cook. She make fine stew and give coins for meat.


else



>**Guntrik says:** Me smell the blood of Craknek enemy. Hey! It you!


end



## Turn-Ins



if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/18787" data-url="18787" class="tooltip-link link">A tattered note</a>) then


>**Guntrik says:** Ahh..  good..  good..  here. take..  Now you Craknek! You bash good. Bash lizards. Bash froggies. Bash mushrooms. Remember. you no help Greenbloods. Crakneks stronger than Greenbloods.


Your faction standing with [Craknek Warriors](/faction/232) got better (<span class='text-success'>+100</span>)



Your faction standing with [Clurg](/faction/228) got better (<span class='text-success'>+15</span>)



Your faction standing with [Green Blood Knights](/faction/261) got worse (<span class='text-danger'>-15</span>)



 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_678.png" alt="" /> <a
                                href="/item/13525" data-url="13525" class="tooltip-link link">Mud Stained Skin Tunic*</a> (+20 exp)

 

elseif **Faction** >= Amiable and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_754.png" alt="" /> <a
                                href="/item/13361" data-url="13361" class="tooltip-link link">A Nobles Crest</a>) then


>**Guntrik says:** One less trouble. Hunhuh!! You do good work. Keep up. Remember to bring any special things to Guntrik. Here junk for good work. Go away now.


Your faction standing with [Craknek Warriors](/faction/232) got better (<span class='text-success'>+15</span>)



Your faction standing with [Clurg](/faction/228) got better (<span class='text-success'>+2</span>)



Your faction standing with [Green Blood Knights](/faction/261) got worse (<span class='text-danger'>-2</span>)



 &#127873; **You receive:** eq.ChooseRandom( <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_519.png" alt="" /> <a
                                href="/item/5030" data-url="5030" class="tooltip-link link">Bronze Two Handed Sword</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_568.png" alt="" /> <a
                                href="/item/5037" data-url="5037" class="tooltip-link link">Bronze Two Handed Battle Axe</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_567.png" alt="" /> <a
                                href="/item/6021" data-url="6021" class="tooltip-link link">Bronze Two Handed Hammer</a>) (+500 exp)

 

elseif **Faction** >= Amiable and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/18883" data-url="18883" class="tooltip-link link">Tattered Parchment</a>) then


>**Guntrik says:** Ooh! This where hunters stay. You must go to Rathe Mountains and find Drinn's Inn. Kill all. Bring owners' scalps back and me give good junk. You get more warriors to help. Say Guntrik command them. You will need all help you get.


Your faction standing with [Craknek Warriors](/faction/232) got better (<span class='text-success'>+2</span>)



Your faction standing with [Clurg](/faction/228) got better (<span class='text-success'>+1</span>)



Your faction standing with [Green Blood Knights](/faction/261) got worse (<span class='text-danger'>-1</span>)



 &#127873; **You receive:** 0 (+1000 exp)

 

**This NPC *should* return incorrect items given.**
