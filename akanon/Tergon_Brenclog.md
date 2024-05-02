# Tergon Brenclog


## Dialog

**You say:** `hail`



>**Tergon Brenclog says:** Eh!!? What do I see before me? A young upstart? Some child pretending to be a great mind? If you wish to test your mettle then you will assist Tergon. Will you [Help Tergon] or are you far [too superior] to deal with such things?

**You say:** `help`



if **Faction** >= Amiable then 



>**Tergon Brenclog says:** No!! You will help yourself. Your task shall find your skills tested. Succeed and knowledge is yours. Fail and death shall embrace you. Go to the Steamfont Mountains and seek out a troll named Bugglegupp. As a youngster I once tried to attack the beast with a device of mine. It sent an Iron Pellet deep into the beasts head. Kill Bugglegupp and return the Iron Pellet. I hope the Pellet does not get lost in the battle.


elseif( **Faction is** == Indifferent) then



>**Tergon Brenclog says:** There is much more you must do for the Library of Mechanimagica before such things can be revealed to you.  Perhaps fetching minotaur horns and returning them to Professor Theardor will earn you membership to the Library of Mechanimagica.


else



>**Tergon Brenclog says:** You dare to speak to a member of the Eldritch Collective! You had best leave before you find your soul displaced from your body.


**You say:** `too superior`



>**Tergon Brenclog says:** Well excuse me!! your majesty. Please forgive my arrogance. Now get out of here, before you stink this place up with that rotting grape you call a brain!

**You say:** `further tasks`



if **Faction** >= Amiable then 






>**Tergon Brenclog says:** Not all experience is gained upon the battlefield. We magicians must heighten our minds to become formidable opponents. I see much promise in you, Soandso. I will require you to [travel abroad] toward Freeport.


elseif( **Faction is** == Indifferent) then



>**Tergon Brenclog says:** There is much more you must do for the Library of Mechanimagica before such things can be revealed to you.  Perhaps fetching minotaur horns and returning them to Professor Theardor will earn you membership to the Library of Mechanimagica.


else



>**Tergon Brenclog says:** You dare to speak to a member of the Eldritch Collective! You had best leave before you find your soul displaced from your body.


**You say:** `travel abroad`



if **Faction** >= Amiable then 



>**Tergon Brenclog says:** You will go to Freeport and seek out the Academy of Arcane Science. There you shall find my brother Retlon. He has scribed some new spells in my [personal spellbook]. Hand him this note as proof of your alliance. He works closely with Master Dooly Jonkers.



 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_682.png" alt="" /> <a
                                href="/item/1717" data-url="1717" class="tooltip-link link">Sealed Letter</a>


elseif( **Faction is** == Indifferent) then



>**Tergon Brenclog says:** There is much more you must do for the Library of Mechanimagica before such things can be revealed to you.  Perhaps fetching minotaur horns and returning them to Professor Theardor will earn you membership to the Library of Mechanimagica.


else



>**Tergon Brenclog says:** You dare to speak to a member of the Eldritch Collective! You had best leave before you find your soul displaced from your body.


**You say:** `defector`



if **Faction** >= Amiable then 



>**Tergon Brenclog says:** It seems a gnome magician by the name of Toko Binlittle has gone and left the guild. He joined forces with the [Pirates of Gunthak]. Find him. He must be destroyed. Our secrets cannot be known. Return his head to me and I shall give you the [Elemental Grimoire].


elseif( **Faction is** == Indifferent) then



>**Tergon Brenclog says:** There is much more you must do for the Library of Mechanimagica before such things can be revealed to you.  Perhaps fetching minotaur horns and returning them to Professor Theardor will earn you membership to the Library of Mechanimagica.


else



>**Tergon Brenclog says:** You dare to speak to a member of the Eldritch Collective! You had best leave before you find your soul displaced from your body.


**You say:** `pirates of gunthak`



>**Tergon Brenclog says:** From what I know, the Pirates of Gunthak are from the southern Gulf of Gunthak. It seems as though a small band of them has been operating within the Ocean of Tears, leagues from their own territory.

**You say:** `elemental grimoire`



if **Faction** >= Indifferent then 



>**Tergon Brenclog says:** The Elemental Grimoire contains the knowledge which will advance your techniques in research. With it you shall learn to research spells and scribe them for your own spellbook.


else



>**Tergon Brenclog says:** You dare to speak to a member of the Eldritch Collective! You had best leave before you find your soul displaced from your body.


**You say:** `personal spellbook`



if **Faction** >= Amiable then 



>**Tergon Brenclog says:** My spellbook is very important to me. It is impossible for anyone to open it. I have magically locked it. Only my brother Retlon knows the words to release its secrets.


elseif( **Faction is** == Indifferent) then



>**Tergon Brenclog says:** There is much more you must do for the Library of Mechanimagica before such things can be revealed to you.  Perhaps fetching minotaur horns and returning them to Professor Theardor will earn you membership to the Library of Mechanimagica.


else



>**Tergon Brenclog says:** You dare to speak to a member of the Eldritch Collective! You had best leave before you find your soul displaced from your body.

end

## Turn-Ins



if **Faction** >= Amiable and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_734.png" alt="" /> <a
                                href="/item/13333" data-url="13333" class="tooltip-link link">Iron Pellet</a>) then


>**Tergon Brenclog says:** So, you have survived. There is no doubt in my mind that you achieved this solely with your own powers. Only a dim one requires the assistance of others. Take this. May it help you in your pursuit of greatness. [Further tasks] may bring you to that point.


Your faction standing with [Eldritch Collective](/faction/245) got better (<span class='text-success'>+15</span>)


Your faction standing with [Dark Reflection](/faction/238) got worse (<span class='text-danger'>-2</span>)


Your faction standing with [The Dead](/faction/239) got worse (<span class='text-danger'>-1</span>)


Your faction standing with [Gem Choppers](/faction/255) got better (<span class='text-success'>+2</span>)


Your faction standing with [King Ak`Anon](/faction/333) got better (<span class='text-success'>+2</span>)


 &#127873; **You receive:** eq.ChooseRandom( <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/15400" data-url="15400" class="tooltip-link link">Spell: Elementaling: Air</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/15397" data-url="15397" class="tooltip-link link">Spell: Elementaling: Earth</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/15399" data-url="15399" class="tooltip-link link">Spell: Elementaling: Fire</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/15398" data-url="15398" class="tooltip-link link">Spell: Elementaling: Water</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/15317" data-url="15317" class="tooltip-link link">Spell: Elementalkin: Air</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/15058" data-url="15058" class="tooltip-link link">Spell: Elementalkin: Earth</a>) (+150 exp)

 

elseif **Faction** >= Amiable and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_778.png" alt="" /> <a
                                href="/item/13387" data-url="13387" class="tooltip-link link">Tergon's Spellbook</a>) then


>**Tergon Brenclog says:** You have done well. I did not expect you for weeks. It is good to have my spellbook returned. It was a simple task. Now I have news of a larger matter. It has to do with a [defector].


Your faction standing with [Eldritch Collective](/faction/245) got better (<span class='text-success'>+10</span>)


Your faction standing with [Dark Reflection](/faction/238) got worse (<span class='text-danger'>-1</span>)


Your faction standing with [The Dead](/faction/239) got worse (<span class='text-danger'>-1</span>)


Your faction standing with [Gem Choppers](/faction/255) got better (<span class='text-success'>+1</span>)


Your faction standing with [King Ak`Anon](/faction/333) got better (<span class='text-success'>+1</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/15399" data-url="15399" class="tooltip-link link">Spell: Elementaling: Fire</a> (+150 exp)

 

elseif **Faction** >= Indifferent and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_777.png" alt="" /> <a
                                href="/item/17502" data-url="17502" class="tooltip-link link">Elemental Grimoire</a> (+300 exp)

 

**This NPC *should* return incorrect items given.**
