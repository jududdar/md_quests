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



**You receive:**  [Sealed Letter](/item/1717)


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



if **Faction** >= Amiable and  **You turn in:** [Iron Pellet](/item/13333)


>**Tergon Brenclog says:** So, you have survived. There is no doubt in my mind that you achieved this solely with your own powers. Only a dim one requires the assistance of others. Take this. May it help you in your pursuit of greatness. [Further tasks] may bring you to that point.


* __Faction:__ [Eldritch Collective](/faction/245) (15)


* __Faction:__ [Dark Reflection](/faction/238) (-2)


* __Faction:__ [The Dead](/faction/239) (-1)


* __Faction:__ [Gem Choppers](/faction/255) (2)


* __Faction:__ [King Ak`Anon](/faction/333) (2)


 **You receive:** eq.ChooseRandom( [Spell: Elementaling: Air](/item/15400), [Spell: Elementaling: Earth](/item/15397), [Spell: Elementaling: Fire](/item/15399), [Spell: Elementaling: Water](/item/15398), [Spell: Elementalkin: Air](/item/15317), [Spell: Elementalkin: Earth](/item/15058)) (+150 exp)

elseif **Faction** >= Amiable and  **You turn in:** [Tergon's Spellbook](/item/13387)


>**Tergon Brenclog says:** You have done well. I did not expect you for weeks. It is good to have my spellbook returned. It was a simple task. Now I have news of a larger matter. It has to do with a [defector].


* __Faction:__ [Eldritch Collective](/faction/245) (10)


* __Faction:__ [Dark Reflection](/faction/238) (-1)


* __Faction:__ [The Dead](/faction/239) (-1)


* __Faction:__ [Gem Choppers](/faction/255) (1)


* __Faction:__ [King Ak`Anon](/faction/333) (1)


 **You receive:**  [Spell: Elementaling: Fire](/item/15399) (+150 exp)

elseif **Faction** >= Indifferent and  **You turn in:** [Teir\`Dal Head](/item/13388)


>**Tergon Brenclog says:** The Elemental Grimoire contains the knowledge which will advance your techniques in research. With it you shall learn to research spells and scribe them for your own spellbook.


* __Faction:__ [Eldritch Collective](/faction/245) (20)


* __Faction:__ [Dark Reflection](/faction/238) (-3)


* __Faction:__ [The Dead](/faction/239) (-1)


* __Faction:__ [Gem Choppers](/faction/255) (3)


* __Faction:__ [King Ak`Anon](/faction/333) (3)


 **You receive:**  [Elemental Grimoire](/item/17502) (+300 exp)

**This NPC *should* return incorrect items given.**
