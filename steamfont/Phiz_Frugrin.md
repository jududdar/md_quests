# Phiz Frugrin



[Phiz Frugrin](/npc/56115) is a level 25 Gnome Wizard that spawns in [Steamfont Mountains](/zone/56).










## Dialog

**You say:** `Hail`



>**Phiz Frugrin says:** Hello my friend. Good to meet you.

**You say:** `lens`



if( **Faction is** >= Amiable) then



>**Phiz Frugrin says:** Oh my. I have bad news. It was stolen by a dark elf rogue. She fled very quickly. My little legs could not keep up. Here. She dropped this. You must find her. Get it back. We have very few Lenses.



 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/18867" data-url="18867" class="tooltip-link link">A Filthy Towel</a>


elseif( **Faction is** == Indifferent) then



>**Phiz Frugrin says:** There is much more you must do for the Library of Mechanimagica before such things can be revealed to you.  Perhaps fetching minotaur horns and returning them to Professor Theardor will earn you membership to the Library of Mechanimagica.


else



>**Phiz Frugrin says:** You dare to speak to a member of the Eldritch Collective! You had best leave before you find your soul displaced from your body.


end
