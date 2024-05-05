# Primalist Saosith



[Primalist Saosith](/npc/202224) is a level 60 Barbarian Shopkeeper that spawns in [Plane of Knowledge](/zone/202).




## Dialog

**You say:** `hail`



e.self:Say("Welcome, traveler, to New Tanaan. All citizens of New Tanaan have come together in welcoming Norrath's curious travelers who crave knowledge and a path to better themselves individually. What little help I alone can offer is extended to the Beastlords of Norrath, for as I was once one of them in a time long since past. If you are a Beastlord, then perhaps what spells that I have penned, though neither unique nor rare to your world, would be of use. If through your endeavors upon the planes you happen to come across fledgling manuscripts 
end



## Turn-Ins



local ethereal =  **You turn in:**  { <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_862.png" alt="" /> <a
                                href="/item/29112" data-url="29112" class="tooltip-link link">Ethereal Parchment</a>}

local spectral =  **You turn in:**  { <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_683.png" alt="" /> <a
                                href="/item/29131" data-url="29131" class="tooltip-link link">Spectral Parchment</a>}

local glyphed =  **You turn in:**  { <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_967.png" alt="" /> <a
                                href="/item/29132" data-url="29132" class="tooltip-link link">Glyphed Rune Word</a>}

if(ethereal > 0) then


repeat



>**Primalist Saosith says:** The magic you have given me is quite potent, it should be a simple task to use primal forces to focus its magic into a spell.



>*Primalist Saosith closes her eyes and the object glows slightly in her hands.*



>**Primalist Saosith says:** Here, I hope this will prove of some use to you.



 &#127873; **You receive:** eq.ChooseRandom( <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/28544" data-url="28544" class="tooltip-link link">Spell: Infusion of Spirit</a>,  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/28545" data-url="28545" class="tooltip-link link">Spell: Healing of Sorsha</a>,  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/21629" data-url="21629" class="tooltip-link link">Spell: Scorpion Venom</a>,  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/28547" data-url="28547" class="tooltip-link link">Spell: Spiritual Vigor</a>,  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/28548" data-url="28548" class="tooltip-link link">Spell: Spirit of Arag</a>) 

 



ethereal = ethereal - 1;


until ethereal == 0;

if(spectral > 0) then


repeat



>**Primalist Saosith says:** The magic you have given me is quite potent, it should be a simple task to use primal forces to focus its magic into a spell.



>*Primalist Saosith closes her eyes and the object glows slightly in her hands.*



>**Primalist Saosith says:** Here, I hope this will prove of some use to you.



 &#127873; **You receive:** eq.ChooseRandom( <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/28549" data-url="28549" class="tooltip-link link">Spell: Arag's Celerity</a>,  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/28550" data-url="28550" class="tooltip-link link">Spell: Spirit of Rellic</a>,  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/21630" data-url="21630" class="tooltip-link link">Spell: Frost Spear</a>,  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/28551" data-url="28551" class="tooltip-link link">Spell: Spiritual Dominion</a>,  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/28552" data-url="28552" class="tooltip-link link">Spell: Spirit of Sorsha</a>) 

 



spectral = spectral - 1;


until spectral == 0;

if(glyphed > 0) then


repeat



>**Primalist Saosith says:** The magic you have given me is quite potent, it should be a simple task to use primal forces to focus its magic into a spell.



>*Primalist Saosith closes her eyes and the object glows slightly in her hands.*



>**Primalist Saosith says:** Here, I hope this will prove of some use to you.



 &#127873; **You receive:** eq.ChooseRandom( <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/28553" data-url="28553" class="tooltip-link link">Spell: Sha's Revenge</a>,  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/28554" data-url="28554" class="tooltip-link link">Spell: Ferocity</a>) 

 



glyphed = glyphed - 1;


until glyphed == 0;

**This NPC *should* return incorrect items given.**





